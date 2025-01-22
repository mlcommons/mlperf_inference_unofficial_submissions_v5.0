*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-5.15.0-113-generic-x86_64-with-glibc2.35
* CPU version: x86_64
* Python version: 3.10.12 (main, Jan 17 2025, 14:35:34) [GCC 11.4.0]
* MLCommons CM version: 3.5.3

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U cmind

cm rm cache -f

cm pull repo mlcommons@mlperf-automations --checkout=3f93ae65d62eaace4e89b216a30157a687b4194f

cm run script \
	--tags=run-mlperf,inference,_submission \
	--execution_mode=valid \
	--batch_size=1 \
	--scenario=Offline \
	--submitter=MLCommons \
	--pull_changes=yes \
	--pull_inference_changes=yes \
	--model=sdxl \
	--backend=pytorch \
	--device=cuda \
	--scenario=Offline \
	--precision=float16 \
	--quiet \
	--adr.compiler.tags=gcc \
	--hw_name=gh_action \
	--results_dir=/root/tmpres/gh_action_results \
	--submission_dir=/root/gh_action_submissions \
	--clean
```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf (CM scripts),
 you should simply reload mlcommons@mlperf-automations without checkout and clean CM cache as follows:*

```bash
cm rm repo mlcommons@mlperf-automations
cm pull repo mlcommons@mlperf-automations
cm rm cache -f

```

## Results

Platform: gh_action-reference-gpu-pytorch_v2.5.1-cu124

Model Precision: fp32

### Accuracy Results 

### Performance Results 
`Samples per second`: `0.821368`
