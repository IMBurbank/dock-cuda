# Dock-CUDA

Docker images with CUDA configurations not available from NVIDIA.

## Motivation

The first Dockerfile in this repo is an Ubuntu 18.04 image with CUDA 9.0. Nvidia doesn't offer CUDA 9.0 images with any distribution after 16.04.

I use this image in the `dock-tf` repo to build a tensorflow image with 18.04 and python 3.6 instead of their current 16.04/python3.5 image. 

This image can be accessed from Docker Hub from `dget/dock-cuda:9.0-base-ubuntu18.04`.