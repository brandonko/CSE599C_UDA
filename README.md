# Reproduction and Extension of ["Unsupervised Data Augmentation for Consistency Training"](https://arxiv.org/pdf/1904.12848.pdf)

## NLP

The `NLP_code.ipynb` contains all the code used throughout our project for the NLP experiments, including setting up the CoLA dataset, loading and finetuning BERT, and our UDA implementation.

## Computer Vision
The files `ComputerVision_AllLabeled.ipynb` and `ComputerVision_SomeLabeled.ipynb` contain the code used for the computer vision experiments, including loading the CIFAR and SVHN datasets, pretraining and finetuning Wide-ResNet-28-2, and our UDA implementation. In `ComputerVision_AllLabeled.ipynb`, all images are treated as both labeled and unlabeled when computing loss. In `ComputerVision_SomeLabeled.ipynb`, a portion of the images are treated as labeled and the remaining images are treated as unlabeled when computing loss.
