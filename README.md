Please download [summary.xlsx](summary.xlsx) to view the most recent results. 
 ```
[2024-12-25 04:46:44,711 submission_checker.py:3167 INFO] Results=35, NoResults=0, Power Results=0
[2024-12-25 04:46:44,711 submission_checker.py:3174 INFO] ---
[2024-12-25 04:46:44,711 submission_checker.py:3175 INFO] Closed Results=0, Closed Power Results=0

[2024-12-25 04:46:44,711 submission_checker.py:3180 INFO] Open Results=35, Open Power Results=0

[2024-12-25 04:46:44,711 submission_checker.py:3185 INFO] Network Results=0, Network Power Results=0

[2024-12-25 04:46:44,711 submission_checker.py:3190 INFO] ---
[2024-12-25 04:46:44,711 submission_checker.py:3192 INFO] Systems=2, Power Systems=0
[2024-12-25 04:46:44,711 submission_checker.py:3196 INFO] Closed Systems=0, Closed Power Systems=0
[2024-12-25 04:46:44,711 submission_checker.py:3201 INFO] Open Systems=2, Open Power Systems=0
[2024-12-25 04:46:44,711 submission_checker.py:3206 INFO] Network Systems=0, Network Power Systems=0
[2024-12-25 04:46:44,711 submission_checker.py:3211 INFO] ---
[2024-12-25 04:46:44,711 submission_checker.py:3216 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@mlperf-automations/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType      | SystemName   | Platform                                                       | Model               | MlperfModel         | Scenario     |       Result | Accuracy              |   number_of_nodes | host_processor_model_name            |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                               | framework   | operating_system                                |   notes |   compliance |   errors | version   |   inferred | has_power   | Units        | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:----------------|:-------------|:---------------------------------------------------------------|:--------------------|:--------------------|:-------------|-------------:|:----------------------|------------------:|:-------------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:-----------------------------------------------------------------------------------------------------------------------|:------------|:------------------------------------------------|--------:|-------------:|---------:|:----------|-----------:|:------------|:-------------|:--------------------|
|  0 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | MultiStream  |     5.65444  | mAP: 37.356           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/multistream            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  1 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | Server       |  1415        | mAP: 37.338           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/server                 | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
|  2 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | SingleStream |     1.73635  | mAP: 37.366           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/singlestream           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  3 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | Offline      |  1735.67     | mAP: 37.332           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/offline                | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
|  4 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | MultiStream  |     0.502795 | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  5 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | Server       | 73744        | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server                  | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
|  6 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | SingleStream |     0.303433 | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  7 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | Offline      | 88086.9      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline                 | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
|  8 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9           | bert-99.9           | SingleStream |     2.17312  | F1: 90.88109554940347 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/singlestream           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | fp16                |
|  9 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9           | bert-99.9           | Offline      |  3347.07     | F1: 90.8832407068292  |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline                | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp16                |
| 10 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9        | 3d-unet-99.9        | SingleStream |   430.368    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 11 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9        | 3d-unet-99.9        | Offline      |     8.30473  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 12 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99             | bert-99             | SingleStream |     1.02989  | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 13 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99             | bert-99             | Offline      |  8268.76     | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline                  | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 14 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | stable-diffusion-xl | stable-diffusion-xl | Server       |     0.881818 | nan                   |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/stable-diffusion-xl/server       | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 15 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | stable-diffusion-xl | stable-diffusion-xl | SingleStream |  1400.03     | nan                   |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/stable-diffusion-xl/singlestream | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 16 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2    | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | stable-diffusion-xl | stable-diffusion-xl | Offline      |     1.39663  | nan                   |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/stable-diffusion-xl/offline      | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 17 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | MultiStream  |    11.6644   | mAP: 37.314           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/multistream            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 18 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | Server       |   637.175    | mAP: 37.311           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/server                 | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 19 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | SingleStream |     1.70244  | mAP: 37.341           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/singlestream           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 20 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet           | retinanet           | Offline      |   871.799    | mAP: 37.353           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/offline                | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 21 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | MultiStream  |     0.454539 | acc: 76.064           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 22 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | Server       | 35357.8      | acc: 76.078           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server                  | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 23 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | SingleStream |     0.282357 | acc: 76.064           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 24 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50            | resnet              | Offline      | 44318.2      | acc: 76.078           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline                 | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 25 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9           | bert-99.9           | Server       |  1414.95     | F1: 90.89127264236201 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/server                 | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | fp16                |
| 26 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9           | bert-99.9           | SingleStream |     2.17509  | F1: 90.88109554940347 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/singlestream           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | fp16                |
| 27 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9           | bert-99.9           | Offline      |  1673.62     | F1: 90.8832407068292  |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline                | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | fp16                |
| 28 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9        | 3d-unet-99.9        | SingleStream |   433.76     | DICE: 0.86236         |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 29 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9        | 3d-unet-99.9        | Offline      |     4.16825  | DICE: 0.86236         |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 30 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99             | bert-99             | Server       |  3841.13     | F1: 90.25897829249658 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server                   | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Queries/s    | int8                |
| 31 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99             | bert-99             | SingleStream |     1.01659  | F1: 90.26682135974633 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 32 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99             | bert-99             | Offline      |  4119.08     | F1: 90.15673510616978 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline                  | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |
| 33 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | stable-diffusion-xl | stable-diffusion-xl | SingleStream |  1423.59     | nan                   |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/stable-diffusion-xl/singlestream | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
| 34 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | stable-diffusion-xl | stable-diffusion-xl | Offline      |     0.698813 | nan                   |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/stable-diffusion-xl/offline      | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |