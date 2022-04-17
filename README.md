# Tensorflow-GPU-Conda-Env-Setup

## Basic commands

conda create -n tf-gpu python=3.8

conda activate tf-gpu

conda install cudnn (cudatoolkit-11.3.1, cudnn-8.2.1 current version as of April 16 2022)

pip install tf-nightly

## if you want to use spyder or jupyter notebook

pip install spyder

pip install jupyterlab

## install some other packages to work with data and images

pip install pillow

pip install numpy pandas sklearn matplotlib scipy
