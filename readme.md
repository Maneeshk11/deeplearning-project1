# Deep Learning Project 1

## Overview

In this Kaggle competition you are tasked with coming up with a modified residual
network (ResNet) architecture with the highest test accuracy on a held-out portion of
a version of the CIFAR-10 image classification dataset, under the constraint that your
model has no more than 5 million parameters.

## Features

- Custom ResNet architecture with ~4.7M parameters
- Data augmentation pipeline including:
  - Random rotations, crops, and flips
  - Color jitter and sharpness adjustments
  - Random erasing for improved robustness
- Learning rate scheduling with MultiStepLR
- Model training with SGD optimizer and momentum
- Alternative ResNet18 implementation with Adam optimizer
- Loss functions:
  - Cross-entropy loss
  - Cross-entropy with label smoothing (0.1)
- Evaluation metrics:
  - Top-1 accuracy
  - Training and validation loss curves
- Training/validation split (80/20) for model evaluation

## Team Members

- Maneesh Kolli (mk9697)
- Srijan Yendluri (sy4417)
- Julio Rodriguez (jr6924)
