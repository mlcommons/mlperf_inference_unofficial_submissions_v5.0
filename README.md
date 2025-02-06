Please download [summary.xlsx](summary.xlsx) to view the most recent results. 
 ```
[2025-02-06 05:55:54,988 submission_checker.py:3263 INFO] Results=41, NoResults=0, Power Results=0
[2025-02-06 05:55:54,988 submission_checker.py:3270 INFO] ---
[2025-02-06 05:55:54,988 submission_checker.py:3271 INFO] Closed Results=25, Closed Power Results=0

[2025-02-06 05:55:54,988 submission_checker.py:3276 INFO] Open Results=16, Open Power Results=0

[2025-02-06 05:55:54,988 submission_checker.py:3281 INFO] Network Results=0, Network Power Results=0

[2025-02-06 05:55:54,988 submission_checker.py:3286 INFO] ---
[2025-02-06 05:55:54,988 submission_checker.py:3288 INFO] Systems=5, Power Systems=0
[2025-02-06 05:55:54,988 submission_checker.py:3292 INFO] Closed Systems=3, Closed Power Systems=0
[2025-02-06 05:55:54,988 submission_checker.py:3297 INFO] Open Systems=4, Open Power Systems=0
[2025-02-06 05:55:54,988 submission_checker.py:3302 INFO] Network Systems=0, Network Power Systems=0
[2025-02-06 05:55:54,988 submission_checker.py:3307 INFO] ---
[2025-02-06 05:55:54,988 submission_checker.py:3312 INFO] SUMMARY: submission looks OK
[2025-02-06 05:55:55,992 module.py:5487 INFO] -        ! call "postprocess" from /home/runner/MLC/repos/mlcommons@mlperf-automations/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType      | SystemName   | Platform                                      | Model               | MlperfModel         | Scenario     |       Result | Accuracy                |   number_of_nodes | host_processor_model_name           |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                        | framework      | operating_system                                  |   notes |   compliance |   errors | version   |   inferred | has_power   | Units        | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:----------------|:-------------|:----------------------------------------------|:--------------------|:--------------------|:-------------|-------------:|:------------------------|------------------:|:------------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:------------------------------------------------------------------------------------------------|:---------------|:--------------------------------------------------|--------:|-------------:|---------:|:----------|-----------:|:------------|:-------------|:--------------------|
|  0 | MLCommons      | available      | open       | edge            | 34127abc9663 | mlc-server-reference-gpu-pytorch_v2.2.2-cu124 | pointpainting       | pointpainting       | SingleStream |  1568.9      | mAP: 54.247453827643064 |                 1 | Intel(R) Xeon(R) Platinum 8480+     |                          2 |                          56 | NVIDIA H100 80GB HBM3    |                       8 | open/MLCommons/results/mlc-server-reference-gpu-pytorch_v2.2.2-cu124/pointpainting/singlestream | pytorch v2.2.2 | Ubuntu 22.04 (linux-5.15.0-113-generic-glibc2.35) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | fp32                |
|  1 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | Server       |  1414.96     | nan                     |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/retinanet/server            | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
|  2 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | SingleStream |     1.72839  | nan                     |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/retinanet/singlestream      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  3 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | MultiStream  |     5.64586  | nan                     |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/retinanet/multistream       | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  4 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | Offline      |  1733.84     | nan                     |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/retinanet/offline           | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
|  5 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | Server       |   637.535    | nan                     |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/retinanet/server            | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
|  6 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | SingleStream |     1.69486  | nan                     |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/retinanet/singlestream      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  7 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | MultiStream  |    11.5954   | nan                     |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/retinanet/multistream       | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  8 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | retinanet           | retinanet           | Offline      |   871.582    | nan                     |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/retinanet/offline           | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
|  9 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | bert-99             | bert-99             | SingleStream |     1.01303  | F1: 90.26682135974633   |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/bert-99/singlestream        | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 10 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | bert-99             | bert-99             | Offline      |  3480.29     | F1: 90.15279313202916   |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/bert-99/offline             | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 11 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | Server       | 35342.5      | acc: 76.078             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/server             | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 12 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | SingleStream |     0.283089 | acc: 76.064             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/singlestream       | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 13 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | MultiStream  |     0.498402 | acc: 76.064             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/multistream        | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 14 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | Offline      | 44252.9      | acc: 76.078             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/offline            | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 15 | MLCommons      | available      | open       | edge            | gh_action    | gh_action-reference-gpu-pytorch_v2.5.1-cu124  | stable-diffusion-xl | stable-diffusion-xl | Offline      |     0.821368 | nan                     |                 1 | Intel(R) Xeon(R) Platinum 8480+     |                          2 |                          56 | NVIDIA H100 80GB HBM3    |                       8 | open/MLCommons/results/gh_action-reference-gpu-pytorch_v2.5.1-cu124/stable-diffusion-xl/offline | pytorch v2.5.1 | Ubuntu 22.04 (linux-5.15.0-113-generic-glibc2.35) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp32                |
| 16 | MLCommons      | available      | closed     | datacenter      | 5234c0b61ae3 | mlc-server-reference-gpu-pytorch_v2.4.0-cu124 | rgat                | rgat                | Offline      |   282.683    | acc: 72.838             |                 1 | Intel(R) Xeon(R) Platinum 8480+     |                          2 |                          56 | NVIDIA H100 80GB HBM3    |                       8 | closed/MLCommons/results/mlc-server-reference-gpu-pytorch_v2.4.0-cu124/rgat/offline             | pytorch v2.4.0 | Ubuntu 22.04 (linux-5.15.0-113-generic-glibc2.35) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp32                |
| 17 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | bert-99.9           | bert-99.9           | SingleStream |     2.17626  | F1: 90.88109554940347   |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/bert-99.9/singlestream    | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | fp16                |
| 18 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | bert-99.9           | bert-99.9           | Offline      |  3338.15     | F1: 90.8832407068292    |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/bert-99.9/offline         | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp16                |
| 19 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | 3d-unet-99          | 3d-unet-99          | SingleStream |   430.145    | DICE: 0.86236           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99/singlestream   | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 20 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | 3d-unet-99          | 3d-unet-99          | Offline      |     8.32011  | DICE: 0.86236           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99/offline        | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 21 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | bert-99             | bert-99             | SingleStream |     2.17626  | F1: 90.88109554940347   |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/bert-99/singlestream      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | fp16                |
| 22 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | bert-99             | bert-99             | Offline      |  3338.15     | F1: 90.8832407068292    |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/bert-99/offline           | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp16                |
| 23 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | Server       | 73725.3      | acc: 76.078             |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/resnet50/server           | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 24 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | SingleStream |     0.303654 | acc: 76.064             |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/resnet50/singlestream     | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 25 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | MultiStream  |     0.504392 | acc: 76.064             |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/resnet50/multistream      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 26 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | Offline      | 87871.6      | acc: 76.078             |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/resnet50/offline          | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 27 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | 3d-unet-99.9        | 3d-unet-99.9        | SingleStream |   430.145    | DICE: 0.86236           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/singlestream | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 28 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia-gpu-TensorRT-default_config  | 3d-unet-99.9        | 3d-unet-99.9        | Offline      |     8.32011  | DICE: 0.86236           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/offline      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-52-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 29 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | bert-99.9           | bert-99.9           | SingleStream |     2.17059  | F1: 90.88109554940347   |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/bert-99.9/singlestream    | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | fp16                |
| 30 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | bert-99.9           | bert-99.9           | Offline      |  1671.64     | F1: 90.8832407068292    |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/bert-99.9/offline         | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp16                |
| 31 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | 3d-unet-99          | 3d-unet-99          | SingleStream |   433.237    | DICE: 0.86236           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/3d-unet-99/singlestream   | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 32 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | 3d-unet-99          | 3d-unet-99          | Offline      |     4.1695   | DICE: 0.86236           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/3d-unet-99/offline        | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 33 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | bert-99             | bert-99             | SingleStream |     1.01086  | F1: 90.26682135974633   |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/bert-99/singlestream      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 34 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | bert-99             | bert-99             | Offline      |  4128.85     | F1: 90.15279313202916   |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/bert-99/offline           | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 35 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | Server       | 35342.5      | acc: 76.078             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/server           | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 36 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | SingleStream |     0.282067 | acc: 76.064             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/singlestream     | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 37 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | MultiStream  |     0.453847 | acc: 76.064             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/multistream      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 38 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | resnet50            | resnet              | Offline      | 44390.5      | acc: 76.078             |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/resnet50/offline          | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 39 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | 3d-unet-99.9        | 3d-unet-99.9        | SingleStream |   433.237    | DICE: 0.86236           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/singlestream | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 40 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia-gpu-TensorRT-default_config  | 3d-unet-99.9        | 3d-unet-99.9        | Offline      |     4.1695   | DICE: 0.86236           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | closed/MLCommons/results/RTX4090x1-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/offline      | TensorRT       | Ubuntu 20.04 (linux-6.8.0-51-generic-glibc2.31)   |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |