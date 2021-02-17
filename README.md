DPCPP CUDA Examples Docker Image
=================================

This docker image uses a pre-built DPCPP CUDA compiler to set up an environment that can be used to run the SYCL for CUDA examples in https://github.com/codeplaysoftware/dpcpp-workshop.git.

The docker image is based on nvidia/cuda:latest, and requires nvidia-docker to run the CUDA applications.

To run the image:

```
sudo docker run --gpus all -it mehdigoli/dpcpp-workshop:latest
```
