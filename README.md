# RatingPredictionPredictability

# README

## Overview

This project is designed to implement and evaluate various recommendation algorithms on multiple datasets. The goal is to assess the accuracy and predictability of these datasets while considering different feature sets. The project includes code for data processing, model training, evaluation, and result analysis.

## Table of Contents

1. [Installation](#installation)
2. [Datasets](#datasets)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Training](#model-training)
5. [Evaluation](#evaluation)
6. [Results](#results)
7. [References](#references)

## Installation

To set up the environment for running the code, please follow the instructions provided in the [RecBole repository](https://github.com/RUCAIBox/RecBole). This project is built upon the RecBole framework, which provides a comprehensive suite of tools for recommender systems research.

### Dependencies

Ensure that you have the following dependencies installed:

- Python 3.7 or higher
- PyTorch
- Numpy
- Pandas
- Scikit-learn

## Datasets

The datasets used in this project are divided into different categories to evaluate the performance of the recommendation algorithms under various conditions. We primarily focus on three datasets:

- **Movielens 20M**
- **Jester**
- **Book-Crossing**
- **Epinions**
- **Modcloth**

The datasets are preprocessed and split into training, validation, and test sets following the methods described in the [RecSysDatasets project](https://github.com/RUCAIBox/RecSysDatasets). This ensures consistency and comparability across different experiments.

### Dataset Download and Preprocessing

To download and preprocess the datasets, refer to the RecSysDatasets project. After downloading, ensure that the data is stored in the appropriate directories as expected by the code.

### Configuration

The training configurations are defined in the `config.yaml` file. This includes settings for batch size, learning rate, number of epochs, and other hyperparameters. Modify this file to tweak the model training process.

## Results

The results from the experiments are saved in the `results/` directory. Each experiment generates a report that includes the performance metrics, visualizations, and comparisons between models with and without temporal features.

### Result Analysis

The analysis focuses on the impact of including temporal features in the model training process. We observe how these features affect the accuracy and generalization ability of the models across different datasets.

## References

This project relies heavily on the following open-source projects:

1. **RecSysDatasets**: For dataset preparation and preprocessing. [GitHub Repository](https://github.com/RUCAIBox/RecSysDatasets)
2. **RecBole**: For the implementation and evaluation of recommendation algorithms. [GitHub Repository](https://github.com/RUCAIBox/RecBole)

For more details on how these projects are used in our work, please refer to their respective documentation.
