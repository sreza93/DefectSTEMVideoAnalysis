# Defect STEM Video Analysis

This project provides the source code for the paper  [A Deep Learning Based Automatic Defect Analysis Framework for In-situ TEM Ion Irradiations](https://doi.org/10.1016/j.commatsci.2021.110560)

## Installation

Our code is modified from [qqwweee/keras-yolo3](https://github.com/qqwweee/keras-yolo3). It is build on `Python 3.6` with `Keras` and `Tensorflow` as backend engine. It was tested on `CUDA 9.0` with `cudnn` and `cudatoolkit`.

## Run

You first need to download the weights we trained. You can download it from [this FigShare Link](https://doi.org/10.6084/m9.figshare.13217495.v1)

If you want to train for original YOLO weights, following instructions described [here](https://github.com/uw-cmg/DefectSTEMVideoAnalysis/tree/master/codes)

* [our trained weights for the paper](https://github.com/uw-cmg/DefectSTEMVideoAnalysis/blob/master/codes/model_data/NicolaosVII.h5)

You can run the training with the following command

```

python3 train.py

```
You can run the demo of the code in this [Notebook](https://github.com/uw-cmg/DefectSTEMVideoAnalysis/blob/master/YOLODemo.ipynb) via Google Colab.

