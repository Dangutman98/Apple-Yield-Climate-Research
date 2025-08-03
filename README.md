# 🌾 Crop Yield Prediction  

This repository contains a project for predicting crop yield using **machine learning models (XGBoost, LSTM, Random Forest)** based on climatic and economic variables.  

---

## 📂 Project Structure  
- 📓 **Notebooks** – Jupyter/Colab `.ipynb` files for data analysis, model training, and evaluation  
- 📊 **Results** – Performance comparisons and visualizations  
- 📁 **Data** – Dataset files (not included due to size -> see below)  

---

## 📌 Features  
- ✅ Descriptive statistics (mean, median, standard deviation)  
- ✅ Data distribution tests (Histogram, Q-Q Plot, Shapiro-Wilk, Pearson)  
- ✅ Models: XGBoost, LSTM, Random Forest  
- ✅ Evaluation using RMSE vs. STD  

---

## 📊 Results Summary  
- **XGBoost with feature combination** achieved more accurate predictions compared to linear regression.  
- **RMSE significantly lower than STD** indicates high prediction accuracy.  
- **LSTM and Random Forest** performed weaker in this case.  

---

## 🚀 How to Use  

### 1️⃣ Clone the repository  
```bash
git clone https://github.com/<your-username>/<repository-name>.git
cd <repository-name>
```
### 2️⃣ Open the notebooks
Open the .ipynb files directly in Jupyter Notebook, VS Code, or Google Colab (you can open them in Colab straight from GitHub).

### 3️⃣ Run step by step
Perform data preprocessing

Train the models

Evaluate results

📦 Data
📌 Dataset is not included due to size limitations.
➡️ You need to upload your own dataset when running the notebooks.

📈 Model Evaluation
Model	Test STD	RMSE	Zone / Approach
XGBoost	2.497	2.244	Individual zone – Yonatan
XGBoost	2.071	1.364	Combined zones + economic data
LSTM	2.497	2.316	Individual zone – Yonatan
Random Forest	2.532	2.271	Combined zones + economic data

👨‍💻 Authors
Dan Gutman
Tal Krispin
Shahar Ben Laiche

Collaborators
Volcani - Israel's national powerhouse of innovation.
