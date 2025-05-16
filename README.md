# 🏡 Melbourne Housing Price Prediction

This project uses machine learning models to predict house prices in Melbourne, Australia based on various property features.

## 📊 Project Overview

The goal is to train and evaluate regression models that can estimate the sale price of a house using attributes like the number of rooms, land size, location, and more.

We compare different model configurations using **Mean Absolute Error (MAE)** to select the best-performing setup.

## 📁 Dataset

The dataset used is `melb_data.csv`, available in the `datasets/` directory.  
It contains historical data on Melbourne property sales, including:

## 🧠 Models Used

### 1. **Decision Tree Regressor**

- Explored multiple tree sizes (`max_leaf_nodes`)
- Selected the best size using validation MAE
- Trained the final model on the full dataset

### 2. **Random Forest Regressor**

- Trained and evaluated as an alternative model
- Typically more robust and accurate than a single tree

## 🧪 Evaluation Metric

- **Mean Absolute Error (MAE)**: Measures average absolute difference between predicted and actual prices.
