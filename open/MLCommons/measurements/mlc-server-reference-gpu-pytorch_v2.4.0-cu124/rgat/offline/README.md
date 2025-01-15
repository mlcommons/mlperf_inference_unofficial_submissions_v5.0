*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-5.15.0-113-generic-x86_64-with-glibc2.35
* CPU version: x86_64
* Python version: 3.10.12 (main, Nov  6 2024, 20:22:13) [GCC 11.4.0]
* MLCommons CM version: 3.5.2

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U cmind

cm rm cache -f

cm pull repo mlcommons@mlperf-automations --checkout=86f785f2f02ddcbfb4ab4d997ea914e516cc94aa

cm run script \
	--tags=run-mlperf,inference,_r5.0-dev,_full \
	--model=rgat \
	--implementation=reference \
	--framework=pytorch \
	--category=datacenter \
	--scenario=Offline \
	--execution_mode=valid \
	--device=cuda \
	--quiet \
	--threads=2 \
	--batch_size=2048 \
	--division=closed
```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf (CM scripts),
 you should simply reload mlcommons@mlperf-automations without checkout and clean CM cache as follows:*

```bash
cm rm repo mlcommons@mlperf-automations
cm pull repo mlcommons@mlperf-automations
cm rm cache -f

```

## Results

Platform: mlc-server-reference-gpu-pytorch_v2.4.0-cu124

Model Precision: fp32

### Accuracy Results 
`acc`: `72.813`, Required accuracy for closed division `>= 0.72131`

### Performance Results 
`Samples per second`: `316.253`
