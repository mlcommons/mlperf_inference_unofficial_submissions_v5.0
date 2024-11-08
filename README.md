Please download [summary.xlsx](summary.xlsx) to view the most recent results. [This page](https://docs.google.com/spreadsheets/d/e/2PACX-1vSCu8F7Hwck-AGJ5kWxi2G3xhO5MJoc_igybvsxjCt-2fEEYyf2BIcR0rTXW0eUzg/pubhtml) shows the results which may not be the latest. 
 ```
[2024-11-08 15:41:48,078 submission_checker.py:3108 INFO] Results=22, NoResults=0, Power Results=0
[2024-11-08 15:41:48,078 submission_checker.py:3115 INFO] ---
[2024-11-08 15:41:48,079 submission_checker.py:3116 INFO] Closed Results=19, Closed Power Results=0

[2024-11-08 15:41:48,079 submission_checker.py:3121 INFO] Open Results=3, Open Power Results=0

[2024-11-08 15:41:48,079 submission_checker.py:3126 INFO] Network Results=0, Network Power Results=0

[2024-11-08 15:41:48,079 submission_checker.py:3131 INFO] ---
[2024-11-08 15:41:48,079 submission_checker.py:3133 INFO] Systems=3, Power Systems=0
[2024-11-08 15:41:48,079 submission_checker.py:3137 INFO] Closed Systems=3, Closed Power Systems=0
[2024-11-08 15:41:48,079 submission_checker.py:3142 INFO] Open Systems=1, Open Power Systems=0
[2024-11-08 15:41:48,079 submission_checker.py:3147 INFO] Network Systems=0, Network Power Systems=0
[2024-11-08 15:41:48,079 submission_checker.py:3152 INFO] ---
[2024-11-08 15:41:48,079 submission_checker.py:3157 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@cm4mlops/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType      | SystemName    | Platform                                                       | Model        | MlperfModel   | Scenario     |       Result | Accuracy              |   number_of_nodes | host_processor_model_name   |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                          | framework   | operating_system                                | notes                             |   compliance |   errors | version   |   inferred | has_power   | Units        | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:----------------|:--------------|:---------------------------------------------------------------|:-------------|:--------------|:-------------|-------------:|:----------------------|------------------:|:----------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:------------------------------------------------------------------------------------------------------------------|:------------|:------------------------------------------------|:----------------------------------|-------------:|---------:|:----------|-----------:|:------------|:-------------|:--------------------|
|  0 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  6061.49     | F1: 90.25897829249658 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server              | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  1 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  8204.1      | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline             | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  2 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.0405   | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  3 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia-gpu-TensorRT-default_config                   | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.29596  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/offline                        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  4 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia-gpu-TensorRT-default_config                   | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.158    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/singlestream                   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  5 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | Server       | 73015.2      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/server                         | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  6 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | Offline      | 87471.2      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/offline                        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  7 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | SingleStream |     0.342055 | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/singlestream                   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  8 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | MultiStream  |     0.951987 | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/multistream                    | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  9 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Server       |     0.888629 | F1: 90.89074704580993 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/server          | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 10 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  3314.54     | F1: 90.8832407068292  |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline         | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 11 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  6061.44     | F1: 90.25897829249658 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 12 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  8219.2      | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 13 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.04535  | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 14 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99   | 3d-unet-99    | Offline      |     8.26286  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99/offline        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 15 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99   | 3d-unet-99    | SingleStream |   431.212    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 16 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 73743.9      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 17 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 87803.5      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline          | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 18 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.323576 | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream     | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 19 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     1.01767  | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 20 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.26286  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 21 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.212    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X   |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |