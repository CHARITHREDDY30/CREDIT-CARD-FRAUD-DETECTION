# Credit Card Fraud Detection

## Overview

This project aims to build a machine learning model to detect fraudulent credit card transactions using transaction data. The goal is to classify transactions as either **fraudulent** or **genuine** based on the features in the dataset.

## Table of Contents

- [Description](#description)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

## Description

In this project, I applied machine learning techniques to build a fraud detection system using historical credit card transaction data. The key steps include:

- Data preprocessing: Handling missing values and normalizing the dataset.
- Feature engineering: Selecting relevant features that contribute to fraud detection.
- Model selection: Using models like Logistic Regression or Random Forest.
- Model evaluation: Using metrics like precision, recall, and F1-score to assess performance.

## Dataset

The dataset used in this project is from a simulated credit card transaction log, where each transaction is labeled as either **fraudulent** or **genuine**. The dataset contains the following features:

- `Transaction_ID`: Unique identifier for each transaction.
- `Amount`: The amount of the transaction.
- `Time`: Time of the transaction.
- `Merchant`: Merchant where the transaction occurred.
- `Fraud`: 1 for fraudulent transactions and 0 for genuine transactions.

**Note**: Due to the size of the dataset, the actual data has been excluded from this repository. You can upload your own `creditcard.csv` file to test the model.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CHARITHREDDY30/CREDIT-CARD-FRAUD.git
   cd CREDIT-CARD-FRAUD
