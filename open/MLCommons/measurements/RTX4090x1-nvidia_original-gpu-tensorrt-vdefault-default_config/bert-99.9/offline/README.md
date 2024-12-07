This experiment is generated using the [MLCommons Collective Mind automation framework (CM)](https://github.com/mlcommons/cm4mlops).

*Check [CM MLPerf docs](https://docs.mlcommons.org/inference) for more details.*

## Host platform

* OS version: Linux-6.8.0-48-generic-x86_64-with-glibc2.29
* CPU version: x86_64
* Python version: 3.8.10 (default, Sep 11 2024, 16:02:53) 
[GCC 9.4.0]
* MLCommons CM version: 3.4.1

## CM Run Command

See [CM installation guide](https://docs.mlcommons.org/inference/install/).

```bash
pip install -U cmind

cm rm cache -f

cm pull repo gateoverflow@cm4mlops --checkout=d63d6b560994f51a9a794073effaee741785af95

cm run script \
	--tags=app,mlperf,inference,generic,_nvidia,_bert-99.9,_tensorrt,_cuda,_valid,_r4.1-dev_default,_offline \
	--quiet=true \
	--env.CM_QUIET=yes \
	--env.CM_MLPERF_IMPLEMENTATION=nvidia \
	--env.CM_MLPERF_MODEL=bert-99.9 \
	--env.CM_MLPERF_RUN_STYLE=valid \
	--env.CM_MLPERF_SKIP_SUBMISSION_GENERATION=False \
	--env.CM_DOCKER_PRIVILEGED_MODE=True \
	--env.CM_MLPERF_BACKEND=tensorrt \
	--env.CM_MLPERF_SUBMISSION_SYSTEM_TYPE=datacenter,edge \
	--env.CM_MLPERF_CLEAN_ALL=True \
	--env.CM_MLPERF_DEVICE=cuda \
	--env.CM_MLPERF_SUBMISSION_DIVISION=closed \
	--env.CM_MLPERF_USE_DOCKER=True \
	--env.CM_NVIDIA_GPU_NAME=rtx_4090 \
	--env.CM_HW_NAME=RTX4090x1 \
	--env.CM_RUN_MLPERF_SUBMISSION_PREPROCESSOR=yes \
	--env.CM_MLPERF_INFERENCE_PULL_CODE_CHANGES=yes \
	--env.CM_MLPERF_INFERENCE_PULL_SRC_CHANGES=yes \
	--env.OUTPUT_BASE_DIR=/home/arjun/gh_action_results \
	--env.CM_MLPERF_INFERENCE_SUBMISSION_DIR=/home/arjun/gh_action_submissions \
	--env.CM_MLPERF_SUBMITTER=MLCommons \
	--env.CM_USE_DATASET_FROM_HOST=yes \
	--env.CM_USE_MODEL_FROM_HOST=yes \
	--env.CM_MLPERF_LOADGEN_ALL_SCENARIOS=yes \
	--env.CM_MLPERF_LOADGEN_COMPLIANCE=yes \
	--env.CM_MLPERF_SUBMISSION_RUN=yes \
	--env.CM_RUN_MLPERF_ACCURACY=on \
	--env.CM_RUN_SUBMISSION_CHECKER=yes \
	--env.CM_TAR_SUBMISSION_DIR=yes \
	--env.CM_MLPERF_SUBMISSION_GENERATION_STYLE=full \
	--env.CM_MLPERF_INFERENCE_VERSION=4.1-dev \
	--env.CM_RUN_MLPERF_INFERENCE_APP_DEFAULTS=r4.1-dev_default \
	--env.CM_MLPERF_LOADGEN_ALL_MODES=yes \
	--env.CM_MLPERF_INFERENCE_SOURCE_VERSION=4.1.23 \
	--env.CM_MLPERF_LAST_RELEASE=v4.1 \
	--env.CM_TMP_PIP_VERSION_STRING= \
	--env.CM_MODEL=bert-99.9 \
	--env.CM_MLPERF_CLEAN_SUBMISSION_DIR=yes \
	--env.CM_RERUN=yes \
	--env.CM_MLPERF_LOADGEN_EXTRA_OPTIONS= \
	--env.CM_MLPERF_LOADGEN_MODE=performance \
	--env.CM_MLPERF_LOADGEN_SCENARIO=Offline \
	--env.CM_MLPERF_LOADGEN_SCENARIOS,=Offline,Server \
	--env.CM_MLPERF_LOADGEN_MODES,=performance,accuracy \
	--env.CM_OUTPUT_FOLDER_NAME=valid_results \
	--env.CM_DOCKER_REUSE_EXISTING_CONTAINER=no \
	--env.CM_DOCKER_DETACHED_MODE=yes \
	--add_deps_recursive.submission-checker-src.tags=_branch.dev \
	--add_deps_recursive.compiler.tags=gcc \
	--add_deps_recursive.coco2014-original.tags=_full \
	--add_deps_recursive.coco2014-preprocessed.tags=_full \
	--add_deps_recursive.imagenet-original.tags=_full \
	--add_deps_recursive.imagenet-preprocessed.tags=_full \
	--add_deps_recursive.openimages-original.tags=_full \
	--add_deps_recursive.openimages-preprocessed.tags=_full \
	--add_deps_recursive.openorca-original.tags=_full \
	--add_deps_recursive.openorca-preprocessed.tags=_full \
	--add_deps_recursive.coco2014-dataset.tags=_full \
	--add_deps_recursive.igbh-dataset.tags=_full \
	--add_deps_recursive.get-mlperf-inference-results-dir.tags=_version.r4_1-dev \
	--add_deps_recursive.get-mlperf-inference-submission-dir.tags=_version.r4_1-dev \
	--add_deps_recursive.mlperf-inference-nvidia-scratch-space.tags=_version.r4_1-dev \
	--adr.submission-checker-src.tags=_branch.dev \
	--adr.compiler.tags=gcc \
	--adr.coco2014-original.tags=_full \
	--adr.coco2014-preprocessed.tags=_full \
	--adr.imagenet-original.tags=_full \
	--adr.imagenet-preprocessed.tags=_full \
	--adr.openimages-original.tags=_full \
	--adr.openimages-preprocessed.tags=_full \
	--adr.openorca-original.tags=_full \
	--adr.openorca-preprocessed.tags=_full \
	--adr.coco2014-dataset.tags=_full \
	--adr.igbh-dataset.tags=_full \
	--adr.get-mlperf-inference-results-dir.tags=_version.r4_1-dev \
	--adr.get-mlperf-inference-submission-dir.tags=_version.r4_1-dev \
	--adr.mlperf-inference-nvidia-scratch-space.tags=_version.r4_1-dev \
	--v=False \
	--print_env=False \
	--print_deps=False \
	--dump_version_info=True \
	--env.OUTPUT_BASE_DIR=/cm-mount/home/arjun/gh_action_results \
	--env.CM_MLPERF_INFERENCE_SUBMISSION_DIR=/cm-mount/home/arjun/gh_action_submissions \
	--env.MLPERF_SCRATCH_PATH=/home/cmuser/CM/repos/local/cache/5b2b0cc913a4453a
```
*Note that if you want to use the [latest automation recipes](https://docs.mlcommons.org/inference) for MLPerf (CM scripts),
 you should simply reload gateoverflow@cm4mlops without checkout and clean CM cache as follows:*

```bash
cm rm repo gateoverflow@cm4mlops
cm pull repo gateoverflow@cm4mlops
cm rm cache -f

```

## Results

Platform: RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config

Model Precision: fp16

### Accuracy Results 
`F1`: `90.88324`, Required accuracy for closed division `>= 90.78313`

### Performance Results 
`Samples per second`: `1666.39`
