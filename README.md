# Music-Genre-Classification

## Overview
This project focuses on classifying music into different genres using machine learning techniques. The goal is to automatically assign genre labels to audio files based on their acoustic features.

## Dataset
The dataset used for training and evaluation consists of a collection of audio files labeled with their corresponding genres. Each audio file is associated with a genre label such as rock, jazz, classical, pop, etc. The dataset is preprocessed to extract relevant features from the audio signals, which are used as input to the machine learning models.

## Models
Several machine learning models are explored for this classification task, including but not limited to:

Logistic Regression
Support Vector Machines (SVM)
Decision Tree
Random Forest
K-Nearest Neighbours (KNN)
Each model is trained and evaluated using cross-validation to assess its performance in classifying music genres accurately. Hyperparameter tuning and feature selection techniques are applied to optimize each model.

## Evaluation
The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Confusion matrices and ROC curves are also analyzed to understand the strengths and weaknesses of each model in classifying different genres.

## Requirements
To run the code in this repository, the following dependencies are required:

Python 3.x
NumPy
Pandas
Scikit-learn
TensorFlow (for NN models)
Jupyter Notebook (optional, for running the notebooks)
