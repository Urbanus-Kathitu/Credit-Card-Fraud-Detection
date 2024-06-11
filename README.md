# Credit-Card-Fraud-Detection

# Credit Card Fraud Detection: Data Cleaning, Preprocessing, and EDA

Welcome to the Credit Card Fraud Detection project repository! This repository contains a comprehensive Google Colab notebook that covers the essential steps for detecting fraudulent transactions in a credit card dataset. The notebook focuses on data cleaning, preprocessing, and exploratory data analysis (EDA) to prepare the data for machine learning models.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Data Cleaning](#data-cleaning)
4. [Preprocessing](#preprocessing)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)

## Introduction

Credit card fraud is a significant issue that impacts financial institutions and customers. This project aims to build a robust pipeline for detecting fraudulent transactions using machine learning techniques. The primary focus is on data cleaning, preprocessing, and performing exploratory data analysis (EDA) to understand the dataset better and prepare it for model training.

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) available on Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred over two days, with 492 frauds out of 284,807 transactions.

## Data Cleaning

Data cleaning is a crucial step to ensure the quality and integrity of the dataset. The notebook includes:
- Handling missing values
- Removing duplicates
- Addressing outliers

## Preprocessing

Preprocessing transforms raw data into a suitable format for analysis and modeling. This section includes:
- Feature scaling (Standardization/Normalization)
- Encoding categorical variables
- Splitting the dataset into training and testing sets

## Exploratory Data Analysis (EDA)

EDA helps in understanding the underlying patterns and relationships in the dataset. Key steps include:
- Visualizing the distribution of features
- Analyzing correlations between features
- Identifying trends and anomalies
- Visualizing the frequency of fraudulent vs. non-fraudulent transactions

## Usage

To run the notebook:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   ```
2. Open the Google Colab notebook (`Credit_Card_Fraud_Detection.ipynb`) in your browser.
3. Follow the instructions in the notebook to execute the cells.

## Dependencies

The notebook requires the following Python libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install these dependencies using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Contributing

Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a new Pull Request.



Happy coding!
