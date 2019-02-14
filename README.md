# tf-bionic-rocm-docker

These file were copied from [ROCmSoftwarePlatform/tensorflow-upstream]
(branch: `r1.12-rocm`) repository and modified to build a Docker image based
on Ubuntu 18.04.

[ROCmSoftwarePlatform/tensorflow-upstream]: https://github.com/ROCmSoftwarePlatform/tensorflow-upstream/tree/r1.12-rocm/tensorflow/tools/ci_build

## Building

```bash
$ cd /path/to/this/repo
$ docker build --tag=tf-bionic-rocm .
```
