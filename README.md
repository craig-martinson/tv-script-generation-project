# Recurrent Neural Networks (RNNs)

Recurrent Neural Networks (RNNs) project developed for Udacity's Deep Learning Nanodegree. The goal of this project is to generate Simpsons TV scripts using RNNs.

## Getting Started

### Setup Environment

#### Clone the Repository

``` batch
git https://github.com/craig-martinson/tv-script-generation-project.git
cd tv-script-generation-project
```

#### Setup Linux

Tested on the following environment:

- Ubuntu 16.04.4 LTS
- NVIDIA GTX1080 (driver version 384.130)
- CUDA® Toolkit 9.0
- cuDNN v7.0

Create a Linux Conda environment with **CPU** backend and upgrade tensorflow:

``` batch
conda env create tv-script-project
conda activate tv-script-project
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.8.0-cp36-cp36m-linux_x86_64.whl
python -m ipykernel install --user --name tv-script-project --display-name "tv-script-project"
 ```

Create a Linux Conda environment with **GPU** backend and upgrade tensorflow:

``` batch
conda env create tv-script-project
conda activate tv-script-project
pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow_gpu-1.8.0-cp36-cp36m-linux_x86_64.whl
python -m ipykernel install --user --name tv-script-project --display-name "tv-script-project"
```

#### Setup Windows

Tested on the following environment:

- Windows 10 Pro, 64-bit
- NVIDIA GTX1080 (driver version 385.54)
- CUDA® Toolkit 9.0
- cuDNN v7.0

Create a Windows Conda environment with **CPU** backend and upgrade tensorflow:

``` batch
conda env create tv-script-project
conda activate tv-script-project
pip install --ignore-installed --upgrade tensorflow
python -m ipykernel install --user --name tv-script-project --display-name "tv-script-project"
 ```

Create a Windows Conda environment with **GPU** backend and upgrade tensorflow:

``` batch
conda env create tv-script-project
conda activate tv-script-project
pip install --ignore-installed --upgrade tensorflow-gpu
python -m ipykernel install --user --name tv-script-project --display-name "tv-script-project"
```

## Jupyter Notebooks

The following jupyter notebooks were developed to support this project:

Description | Link
--- | ---
Project notebook provided by Udacity, demonstrates RNNs with TensorFlow | [TV Script Generation Notebook](./dlnd_tv_script_generation.ipynb)

## References

The following resources were used in developing this project: 

