# MLP-Depth-Analysis-FashionMNIST
Reproducible MLP depth analysis on Fashion-MNIST, focusing on interpretability, learning behavior, and accessible, responsible AI education

Project Overview

This project explores how the depth of a Multi-Layer Perceptron (MLP) affects performance, training time, and model capacity on the Fashion-MNIST dataset. We compare Shallow, Medium, and Deep MLP models to evaluate accuracy, parameters, and learning behavior.

Objective

Analyze the effect of MLP depth on test accuracy and training efficiency.

Visualize learning curves and confusion matrices for each model.

Compare model performance based on the number of trainable parameters.

Dataset

Dataset: Fashion-MNIST (10 classes of fashion items)

Size: 60,000 training samples, 10,000 test samples

Preprocessing: Normalization to mean=0.5, std=0.5

The dataset is automatically downloaded via torchvision.datasets.FashionMNIST.

Models

Shallow MLP: 1 hidden layer

Medium MLP: 3 hidden layers with dropout and batch normalization

Deep MLP: 6 hidden layers with higher dropout and batch normalization
