# Credit Card Fraud Detection

## Overview
This project aims to detect credit card fraud using deep learning techniques, including a Multi-Layer Perceptron (MLP) and an Autoencoder. The project utilizes the Kaggle Credit Card Fraud Detection dataset and demonstrates how to preprocess data, handle class imbalances, build and train models, and integrate the model into a real-time API using Flask.

## Dataset
The dataset used in this project is the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains transactions made by credit cards in September 2013 by European cardholders. This dataset presents transactions that occurred over two days, with 492 frauds out of 284,807 transactions.

## Project Structure
- **Data Preparation**: Handle missing values and class imbalances.
- **MLP Model**: Build and train a Multi-Layer Perceptron (MLP) model for classification.
- **Autoencoder Model**: Build and train an Autoencoder model for anomaly detection.

## Installation
To run this project, you'll need to have Python installed. You can install the necessary packages using pip:
```bash
pip install pandas numpy scikit-learn imbalanced-learn tensorflow flask
