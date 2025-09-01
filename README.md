# Imagenette Classification with VGG16

This repository contains a PyTorch implementation of image classification on the [Imagenette dataset](https://github.com/fastai/imagenette) using VGG16, both **from scratch** and **pre-trained with transfer learning**.

## Features

- Custom implementation of VGG16 with adaptive average pooling.
- Training from scratch on Imagenette.
- Transfer learning using pre-trained VGG16 weights from ImageNet.
- Data augmentation for training: random resized crop, horizontal flip, color jitter.
- Evaluation on validation and test sets.
- Visualization of multiple images with ground-truth and predicted labels.
- Memory management tips for running large models in limited GPU environments (Colab).

## Requirements

- Python 3.8+
- PyTorch 2.x
- Torchvision 0.15+
- Matplotlib
- Numpy

Install dependencies via pip:

## Optional

Adjust hyperparameters in the notebook:

* batch_size

* learning_rate

* Number of epochs

* Data augmentation parameters

## Results

* Training VGG16 from scratch: ~63% validation accuracy.

* Pre-trained VGG16 (feature extractor): >90% validation and test accuracy.
