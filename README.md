# 🌾 Crop Yield Prediction

This repository contains a project for predicting crop yield using **machine learning models (XGBoost, LSTM, Random Forest)** based on climatic and economic variables.

---

## 📂 Project Structure

* 📓 **Notebooks** – Colab `.ipynb` files for data analysis, model training, and evaluation:

  * `ApplesProjectEDA.ipynb` – Exploratory Data Analysis and preprocessing.
  * `ApplesProjectModels.ipynb` – Model training and evaluation.
* 📈 **Results** – Performance comparisons and visualizations.
* 📁 **Data** – Dataset files (not included in the repository, see details below).

---

## 📌 Features

* ✅ Descriptive statistics (mean, median, standard deviation).
* ✅ Data distribution tests (Histogram, Q-Q Plot, Shapiro-Wilk, Pearson).
* ✅ Models: XGBoost, LSTM, Random Forest.
* ✅ Evaluation using RMSE vs. STD.

---

## 📈 Results Summary

| Model          | Test STD | RMSE  | Zone / Approach                |
| -------------- | -------- | ----- | ------------------------------ |
| XGBoost        | 2.497    | 2.244 | Individual zone – Yonatan      |
| XGBoost + Econ | 2.071    | 1.364 | Combined zones + economic data |
| LSTM           | 2.497    | 2.316 | Individual zone – Yonatan      |
| Random Forest  | 2.532    | 2.271 | Combined zones + economic data |

* **XGBoost with combined features** outperformed other models.
* **RMSE significantly lower than STD** indicates high prediction accuracy.
* **LSTM and Random Forest** underperformed in this specific scenario.

---

## 🚀 How to Use

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Dangutman98/Apple-Yield-Climate-Research.git
cd Apple-Yield-Climate-Research
```

### 2️⃣ Open the Notebooks in Google Colab

* Open `ApplesProjectEDA.ipynb` and run it step-by-step for EDA & preprocessing.
* Then run `ApplesProjectModels.ipynb` for model training and evaluation.

> **ℹ️ Note:**
> The datasets are **loaded directly from the authors' Google Drive** during notebook execution.
> You **do not need to upload any files manually**. Simply run the notebook cells as-is.

### 3️⃣ Recommended Run Order

1. Run `ApplesProjectEDA.ipynb` (mandatory for data preparation).
2. Run `ApplesProjectModels.ipynb` (after EDA is completed).

---

## 👨‍💻 Authors

* **Dan Gutman**
* **Tal Krispin**
* **Shahar Ben Laiche**

### Collaborators

* **Volcani Institute** – Israel's national powerhouse of agricultural innovation.

---

### ⚠️ Data Notice

* The dataset files are **not included in this repository** due to size constraints.
* The notebooks are pre-configured to **fetch the required files from a private Google Drive**. Ensure you have access via the shared links or modify paths accordingly.
