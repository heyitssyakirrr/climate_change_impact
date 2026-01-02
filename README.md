# 🌿 CSC4600 Data Mining Project: Climate Change Impact on Agriculture

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange?logo=tensorflow&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview

This project applies **Data Mining** and **Machine Learning** techniques to analyze the critical impact of climate change on global agriculture.

Using the **Climate Change Impact on Agriculture 2024** dataset, the project aims to predict effective **Adaptation Strategies** (e.g., *Crop Rotation*, *Water Management*) based on a complex interplay of environmental and agronomic factors.

---

## 📂 Dataset

The dataset used in this project is sourced from **Kaggle**: `climate_change_impact_on_agriculture_2024.csv`.

It contains **10,000 records** categorized by the following key features:

| Category | Key Features |
| :--- | :--- |
| **🌍 Environmental Factors** | Average Temperature, Total Precipitation, CO2 Emissions, Extreme Weather Events |
| **🌾 Agronomic Factors** | Crop Type & Yield, Irrigation Access, Pesticide & Fertilizer Use, Soil Health Index |
| **📍 Location** | Country, Region |
| **🎯 Target Variable** | **`Adaptation_Strategies`** (Categorical: *Water Management, Crop Rotation, No Adaptation, etc.*) |

---

## 🛠️ Technologies Used

* **Language:** ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-Learn`
* **Deep Learning:** `TensorFlow` / `Keras`

---

## ⚙️ Project Workflow

### 1. Data Loading
* Imported the raw CSV dataset into the environment.

### 2. Exploratory Data Analysis (EDA)
* ✅ **Data Integrity:** Checked for null values (verified dataset is clean).
* 📊 **Distributions:** Analyzed distributions of regions, countries, and crop types.
* 📉 **Correlations:** Visualized relationships between environmental factors and agricultural output.

### 3. Data Preprocessing
* **One-Hot Encoding:** Applied to categorical features:
    * `Country`, `Region`, `Crop_Type`
* **Label Encoding:** Applied to the target variable:
    * `Adaptation_Strategies`

### 4. Modeling
* Implemented a **Deep Learning model** using **TensorFlow/Keras**.
* Utilized standard classification metrics to evaluate performance.

---

## 📊 Results

The model was trained to classify the best adaptation strategy for a given set of environmental conditions.

| Metric | Score | Note |
| :--- | :---: | :--- |
| **Accuracy** | `19.6%` | Initial baseline performance. |
| **Precision** | *Varied* | Dependent on class balance within the dataset. |
| **Recall** | *Varied* | Dependent on class balance within the dataset. |

> **Note:** The baseline accuracy suggests high complexity in the dataset or a need for further feature engineering and hyperparameter tuning in future iterations.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
