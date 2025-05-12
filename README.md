# 🏡 House Price Predictor

A machine learning project to predict housing prices based on structured data. This end-to-end pipeline covers data preprocessing, model training, evaluation, and prediction.

## 🔍 Problem Statement

Predict house prices using features like number of rooms, location, area, etc., to assist buyers and real estate agents with pricing decisions.

## ⚙️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- ZenML (for orchestration)
- MLflow (for experiment tracking)

## 🛠️ Pipeline Stages

- **Data Cleaning**: Handled missing values, removed outliers.
- **Feature Engineering**: Encoding categorical data, scaling numerical features.
- **Model Training**: Linear Regression, Random Forest, etc.
- **Experiment Tracking**: Used MLflow for logging metrics and artifacts.
- **Orchestration**: Implemented a reproducible pipeline with ZenML.

## 📊 Results

- Best RMSE: ~`your value here`
- Tracked model comparisons and runs via MLflow UI.

## 📁 Getting Started

Clone the repo and install dependencies:

```bash
git clone https://github.com/aryan2135/House-predictor.git
cd House-predictor
pip install -r requirements.txt
```
```bash
zenml up
python run_pipeline.py
