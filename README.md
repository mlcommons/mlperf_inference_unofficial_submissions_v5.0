Please download [summary.xlsx](summary.xlsx) to view the most recent results. 
 ```
[2025-01-17 23:08:49,198 submission_checker.py:3183 INFO] Results=1, NoResults=0, Power Results=0
[2025-01-17 23:08:49,198 submission_checker.py:3190 INFO] ---
[2025-01-17 23:08:49,198 submission_checker.py:3191 INFO] Closed Results=1, Closed Power Results=0

[2025-01-17 23:08:49,198 submission_checker.py:3196 INFO] Open Results=0, Open Power Results=0

[2025-01-17 23:08:49,198 submission_checker.py:3201 INFO] Network Results=0, Network Power Results=0

[2025-01-17 23:08:49,198 submission_checker.py:3206 INFO] ---
[2025-01-17 23:08:49,198 submission_checker.py:3208 INFO] Systems=1, Power Systems=0
[2025-01-17 23:08:49,198 submission_checker.py:3212 INFO] Closed Systems=1, Closed Power Systems=0
[2025-01-17 23:08:49,198 submission_checker.py:3217 INFO] Open Systems=0, Open Power Systems=0
[2025-01-17 23:08:49,198 submission_checker.py:3222 INFO] Network Systems=0, Network Power Systems=0
[2025-01-17 23:08:49,198 submission_checker.py:3227 INFO] ---
[2025-01-17 23:08:49,198 submission_checker.py:3232 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@mlperf-automations/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType   | SystemName   | Platform                                      | Model   | MlperfModel   | Scenario   |   Result | Accuracy    |   number_of_nodes | host_processor_model_name       |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                            | framework      | operating_system                                  |   notes |   compliance |   errors | version   |   inferred | has_power   | Units     | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:-------------|:-------------|:----------------------------------------------|:--------|:--------------|:-----------|---------:|:------------|------------------:|:--------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:------------------------------------------------------------------------------------|:---------------|:--------------------------------------------------|--------:|-------------:|---------:|:----------|-----------:|:------------|:----------|:--------------------|
|  0 | MLCommons      | available      | closed     | datacenter   | 5234c0b61ae3 | mlc-server-reference-gpu-pytorch_v2.4.0-cu124 | rgat    | rgat          | Offline    |  282.683 | acc: 72.838 |                 1 | Intel(R) Xeon(R) Platinum 8480+ |                          2 |                          56 | NVIDIA H100 80GB HBM3    |                       8 | closed/MLCommons/results/mlc-server-reference-gpu-pytorch_v2.4.0-cu124/rgat/offline | pytorch v2.4.0 | Ubuntu 22.04 (linux-5.15.0-113-generic-glibc2.35) |     nan |            1 |        0 | v5.0      |          0 | False       | Samples/s | fp32                |