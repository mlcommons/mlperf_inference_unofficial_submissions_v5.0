*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-6.8.0-51-generic-x86_64-with-glibc2.29
* CPU version: x86_64
* Python version: 3.8.10 (default, Jan 17 2025, 14:40:23) 
[GCC 9.4.0]
* MLC version: unknown

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U mlcflow

mlc rm cache -f

mlc pull repo mlcommons@mlperf-automations --checkout=eae72d8f53a7ab47fa8ff1446900348cbfa42aba


```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf,
 you should simply reload mlcommons@mlperf-automations without checkout and clean MLC cache as follows:*

```bash
mlc rm repo mlcommons@mlperf-automations
mlc pull repo mlcommons@mlperf-automations
mlc rm cache -f

```

## Results

Platform: RTX4090x1-nvidia-gpu-TensorRT-default_config

Model Precision: int8

### Accuracy Results 
`DICE`: `0.86236`, Required accuracy for closed division `>= 0.86084`

### Performance Results 
`Samples per second`: `4.1695`
