# Linear Classifier Project

## Overview

This project demonstrates the process of training and evaluating a linear classifier model for both binary and multi-class classification problems. We used Python's `scikit-learn` library to generate a dataset, train linear classifiers, and evaluate their performance. Additionally, we visualized the decision boundaries and misclassified samples.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset Generation](#dataset-generation)
3. [Model Training and Evaluation](#model-training-and-evaluation)
4. [Visualization](#visualization)
5. [Results](#results)
6. [How to Run](#how-to-run)
7. [Future Work](#future-work)
8. [Conclusion](#conclusion)

## Introduction

In this project, we:
- Generated a synthetic dataset with 4 classes and 3 features.
- Trained linear classifiers to distinguish between the classes.
- Evaluated the performance of the classifiers using accuracy and other metrics.
- Visualized the decision boundaries and misclassified samples.

## Dataset Generation

We generated a dataset using `sklearn.datasets.make_classification` with the following parameters:
- 1000 samples
- 4 classes
- 3 features

The dataset was divided into training and testing sets to evaluate the performance of the models.

## Model Training and Evaluation

We used two different linear classifiers from `sklearn.linear_model`:
- Logistic Regression with default settings.
- Logistic Regression with the 'saga' solver for optimization.

The models were trained on the training set and evaluated on the test set. We chose appropriate hyperparameters such as the number of iterations and learning rate to optimize the model's performance.

## Visualization

We visualized the decision boundaries and the misclassified samples using scatter plots. This helped in understanding how well the models were able to separate the different classes and where they struggled.

## Results

The models were evaluated based on accuracy and other metrics.
The decision boundaries and misclassified samples were also plotted for better insight into the model's performance.

## How to Run

To reproduce this project, follow these steps:

1. Clone the repository:
   ```sh
   git clone <repository_url>
   cd <repository_directory>
