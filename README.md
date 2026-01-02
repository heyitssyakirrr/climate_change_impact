## CSC4600 Data Mining Project: Climate Change Impact on Agriculture
## 📌 Project Overview
This project applies data mining and machine learning techniques to analyze the impact of climate change on agriculture. Using the Climate Change Impact on Agriculture 2024 dataset, the project aims to predict effective Adaptation Strategies (e.g., Crop Rotation, Water Management) based on various environmental and agronomic factors.

## 📂 Dataset
The dataset used in this project is sourced from Kaggle: climate_change_impact_on_agriculture_2024.csv.

It contains 10,000 records with the following key features:

Environmental: Average Temperature, Total Precipitation, CO2 Emissions, Extreme Weather Events.

Agronomic: Crop Type, Crop Yield, Irrigation Access, Pesticide/Fertilizer Use, Soil Health Index.

Location: Country, Region.

Target Variable: Adaptation_Strategies (Categorical: Water Management, Crop Rotation, No Adaptation, etc.)

## 🛠️ Technologies Used
Python 3.10+

Data Manipulation: Pandas, NumPy

Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-Learn

Deep Learning: TensorFlow / Keras

## ⚙️ Project Workflow
Data Loading: Imported the raw CSV dataset.

Exploratory Data Analysis (EDA):

Checked for null values (dataset is clean).

Analyzed distributions of regions, countries, and crop types.

Visualized relationships between environmental factors and agriculture.

Data Preprocessing:

One-Hot Encoding: Applied to categorical features (Country, Region, Crop_Type).

Label Encoding: Applied to the target variable (Adaptation_Strategies).

Modeling:

Implemented a Deep Learning model using TensorFlow/Keras.

Used standard classification metrics (Accuracy, Precision, Recall, F1-Score) to evaluate performance.

## 📊 Results
The model was trained to classify the best adaptation strategy for a given set of conditions.

Current Performance: The initial model achieved an accuracy of approximately 19.6%. (Note: Further hyperparameter tuning and feature engineering are recommended to improve predictive performance).
