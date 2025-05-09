# Customer Purchase Prediction

## Overview
This project predicts whether a customer will purchase a product based on the **Bank Marketing Dataset** from the UCI Machine Learning Repository. A **Decision Tree Classifier** is used to model demographic and behavioral features to predict purchase decisions (`yes`/`no`).

## Dataset
- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- File: `data/bank-additional-full.csv`
- Size: 41,188 records, 21 columns
- Target: `y` (`yes` = purchase, `no` = no purchase)
- Features: Demographic (e.g., `age`, `job`), behavioral (e.g., `duration`, `campaign`)

## Project Structure
Customer-Purchase-Prediction/
├── data/
│   └── bank-additional-full.csv        # Dataset
├── images/
│   ├── confusion_matrix.png            # Confusion matrix plot
│   ├── feature_importance.png          # Feature importance plot
├── notebooks/
│   └── eda.ipynb                       # Main notebook (data loading, modeling, evaluation)
├── scripts/                            # Empty (for future scripts)
├── .gitignore                          # Ignores venv/, pycache/
├── README.md                           # Project documentation
├── requirements.txt                    # Dependencies