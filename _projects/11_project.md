---
layout: page
title: Jupyter GPU Docker Image
description: Pre-configured Docker image for GPU-accelerated deep learning with JupyterLab
img: assets/img/8.jpg
importance: 9
category: ai
github: devn913/jupyter-gpu-image
---

A **ready-to-use Docker image** for GPU-accelerated deep learning and data science, featuring JupyterLab with CUDA support — eliminating environment setup friction for ML experiments.

## Features

- CUDA-enabled PyTorch and TensorFlow pre-installed
- JupyterLab with useful extensions
- Common ML libraries: Scikit-learn, Pandas, Matplotlib, Seaborn
- GPU passthrough via NVIDIA Container Toolkit
- Single command to launch a full ML environment

## Usage

```bash
docker run --gpus all -p 8888:8888 devn913/jupyter-gpu-image
```

## Tech Stack

`Docker` · `CUDA` · `PyTorch` · `JupyterLab` · `NVIDIA Container Toolkit`
