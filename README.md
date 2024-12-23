Please download [summary.xlsx](summary.xlsx) to view the most recent results. 
 ```
[2024-12-23 03:38:09,313 submission_checker.py:3167 INFO] Results=2, NoResults=0, Power Results=0
[2024-12-23 03:38:09,313 submission_checker.py:3174 INFO] ---
[2024-12-23 03:38:09,313 submission_checker.py:3175 INFO] Closed Results=0, Closed Power Results=0

[2024-12-23 03:38:09,313 submission_checker.py:3180 INFO] Open Results=2, Open Power Results=0

[2024-12-23 03:38:09,313 submission_checker.py:3185 INFO] Network Results=0, Network Power Results=0

[2024-12-23 03:38:09,313 submission_checker.py:3190 INFO] ---
[2024-12-23 03:38:09,313 submission_checker.py:3192 INFO] Systems=1, Power Systems=0
[2024-12-23 03:38:09,314 submission_checker.py:3196 INFO] Closed Systems=0, Closed Power Systems=0
[2024-12-23 03:38:09,314 submission_checker.py:3201 INFO] Open Systems=1, Open Power Systems=0
[2024-12-23 03:38:09,314 submission_checker.py:3206 INFO] Network Systems=0, Network Power Systems=0
[2024-12-23 03:38:09,314 submission_checker.py:3211 INFO] ---
[2024-12-23 03:38:09,314 submission_checker.py:3216 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@mlperf-automations/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType      | SystemName   | Platform                                                       | Model        | MlperfModel   | Scenario     |    Result | Accuracy      |   number_of_nodes | host_processor_model_name            |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                        | framework   | operating_system                                |   notes |   compliance |   errors | version   |   inferred | has_power   | Units        | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:----------------|:-------------|:---------------------------------------------------------------|:-------------|:--------------|:-------------|----------:|:--------------|------------------:|:-------------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:----------------------------------------------------------------------------------------------------------------|:------------|:------------------------------------------------|--------:|-------------:|---------:|:----------|-----------:|:------------|:-------------|:--------------------|
|  0 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream | 437.265   | DICE: 0.86236 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Latency (ms) | int8                |
|  1 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1    | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |   4.13717 | DICE: 0.86236 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline      | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s    | int8                |