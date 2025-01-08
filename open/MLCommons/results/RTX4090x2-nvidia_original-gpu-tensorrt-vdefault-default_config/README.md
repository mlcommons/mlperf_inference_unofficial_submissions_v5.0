
See the HTML preview [here](https://htmlpreview.github.io/?https://github.com/mlcommons/mlperf_inference_unofficial_submissions_v5.0/blob/refs/heads/auto-update/open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/summary.html)



<div class="resultpage">
 <div class="titlebarcontainer">
  <div class="logo">
   <a href="/" style="border: none"><img src="" alt="" /></a>
  </div>
  <div class="titlebar">
   <h1 class="title">MLPerf Inference v5.0</h1>
   <p style="font-size: smaller">Copyright 2019-2025 MLCommons</p>
  </div>
 </div>
 <table class="titlebarcontainer">
  <tr>
   <td class="headerbar" rowspan="2">
    <p>MLCommons     </p>
    <p>RTX4090x2    </p>
   </td>
  </tr>
 </table>
 <table class="datebar">
  <tbody>
   <tr>
    <th id="license_num"><a href="">MLPerf Inference Category:</a></th>
    <td id="license_num_val">datacenter,edge</td>
    <th id="test_date"><a href="">MLPerf Inference Division:</a></th>
    <td id="test_date_val">open</td>
   </tr>
   <tr>
    <th id="tester"><a href="">Submitted by:</a></th>
    <td id="tester_val">MLCommons</td>
    <th id="sw_avail"><a href="">Availability:</a></th>
    <td id="sw_avail_val">Available  as of February 2025</td>
   </tr>
  </tbody>
 </table>
  
<table>
            <tr><td><h3>Accelerator Details</h3><table><tr><td>accelerator_frequency</td><td>2520000 MHz</td></tr><tr><td>accelerator_host_interconnect</td><td>N/A</td></tr><tr><td>accelerator_interconnect</td><td>N/A</td></tr><tr><td>accelerator_interconnect_topology</td><td></td></tr><tr><td>accelerator_memory_capacity</td><td>23.64019775390625 GB</td></tr><tr><td>accelerator_memory_configuration</td><td>N/A</td></tr><tr><td>accelerator_model_name</td><td>NVIDIA GeForce RTX 4090</td></tr><tr><td>accelerator_on-chip_memories</td><td></td></tr><tr><td>accelerators_per_node</td><td>2</td></tr></table></td> <td><h3>Processor and Memory Details</h3><table><tr><td>host_memory_capacity</td><td>192G</td></tr><tr><td>host_memory_configuration</td><td>undefined</td></tr><tr><td>host_processor_caches</td><td>L1d cache: 1.1 MiB, L1i cache: 768 KiB, L2 cache: 48 MiB, L3 cache: 45 MiB</td></tr><tr><td>host_processor_core_count</td><td>24</td></tr><tr><td>host_processor_frequency</td><td>4800.0000</td></tr><tr><td>host_processor_interconnect</td><td></td></tr><tr><td>host_processor_model_name</td><td>Intel(R) Xeon(R) w7-2495X</td></tr><tr><td>host_processors_per_node</td><td>1</td></tr></table></td> </tr>
            <tr><td ><h3>Other Hardware Details</h3><table><tr><td>cooling</td><td>air</td></tr><tr><td>hw_notes</td><td></td></tr></table></td> <td><h3>Network and Interconnect Details</h3><table><tr><td>host_network_card_count</td><td>1</td></tr><tr><td>host_networking</td><td>Gig Ethernet</td></tr><tr><td>host_networking_topology</td><td>N/A</td></tr></table></td> </tr>
            <tr><td colspan="2"><h3>Software Details</h3><table><tr><td>framework</td><td>TensorRT</td></tr><tr><td>operating_system</td><td>Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31)</td></tr><tr><td>other_software_stack</td><td>Python: 3.8.10, GCC-9.4.0, Using Docker  , CUDA 12.2</td></tr><tr><td>sw_notes</td><td></td></tr></table></td> </tr>
            </table>

<h3>Results Table</h3>
<table>
    <tr>
        <th rowspan="2">Model</th>
        <th rowspan="2">Accuracy Target</th>
        <th colspan="3">Server</th>
        <th colspan="3">Offline</th>
    </tr>
    <tr><td> Accuracy </td>
    <td>Metric</td>
    <td>Performance</td><td> Accuracy </td>
    <td>Metric</td>
    <td>Performance</td>
    </tr><tr><td>resnet</td><td>acc: 75.6954</td><td>acc: 76.078</td><td>Queries/s</td> <td>73744.0</td><td>acc: 76.078</td><td>Samples/s</td> <td>88040.1</td><tr><td>retinanet</td><td>mAP: 37.1745</td><td>mAP: 37.320</td><td>Queries/s</td> <td>1414.99</td><td>mAP: 37.371</td><td>Samples/s</td> <td>1740.84</td><tr><td>bert-99</td><td>F1: 89.9653</td><td colspan="3"> N/A </td><td>F1: 90.15673510616978</td><td>Samples/s</td> <td>8245.93</td><tr><td>bert-99.9</td><td>F1: 90.7831</td><td colspan="3"> N/A </td><td>F1: 90.8832407068292</td><td>Samples/s</td> <td>3339.26</td><tr><td>3d-unet-99.9</td><td>DICE: 0.8608</td><td colspan="3"> N/A </td><td>DICE: 0.86236</td><td>Samples/s</td> <td>8.29797</td><tr><td>stable-diffusion-xl</td><td>CLIP_SCORE: 31.6863, FID_SCORE: 23.0109</td><td></td><td>Queries/s</td> <td>0.881818</td><td></td><td>Samples/s</td> <td>1.39663</td></table>

