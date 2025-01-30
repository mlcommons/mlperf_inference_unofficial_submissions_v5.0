*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-5.15.0-113-generic-x86_64-with-glibc2.35
* CPU version: x86_64
* Python version: 3.10.12 (main, Jan 17 2025, 14:35:34) [GCC 11.4.0]
* MLC version: 0.1.0

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U mlcflow

mlc rm cache -f

mlc pull repo anandhu-eng@mlperf-automations --checkout=4192cdb677ef913c863abd7734fe821ec6c46793


```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf,
 you should simply reload anandhu-eng@mlperf-automations without checkout and clean MLC cache as follows:*

```bash
mlc rm repo anandhu-eng@mlperf-automations
mlc pull repo anandhu-eng@mlperf-automations
mlc rm cache -f

```

## Results

Platform: mlc-server-reference-gpu-pytorch_v2.2.2-cu124

Model Precision: fp32

### Accuracy Results 
`mAP`: `54.24745`, Required accuracy for closed division `>= 0.54196`

### Performance Results 
`90th percentile latency (ns)`: `1568895029.0`
