# Bulldozer Price Prediction 🏗️💰

This project predicts the **auction sale prices of bulldozers** using historical sales data and machine learning techniques.  
It is inspired by the Kaggle competition: *"Blue Book for Bulldozers"*.

---

## 📌 Project Overview
- Objective: Build a regression model that can predict the sale price of bulldozers given their features (year, model, usage, etc.).
- Dataset: [Kaggle Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers).
- Approach: Data preprocessing → Feature engineering → Model training → Evaluation.

---

## 🚀 Getting Started  

### 1. Clone the repository  
git clone https://github.com/YR-raj/Bulldozer-Price-prediction-project.git

### 2. Go to project folder
cd Bulldozer-Price-prediction-project

### 3. Create a virtual environment
conda create --name bulldozer_env python=3.9 -y

### 3. Activate environment
conda activate bulldozer_env

### 4. Install dependencies
conda env update --file environment.yml --prune

### 5. Run the notebook
jupyter notebook notebook.ipynb

---

## ⚙️ Tech Stack
- **Python**
- **Pandas, NumPy** (Data processing)
- **Matplotlib** (Visualization)
- **Scikit-learn** (Machine Learning)
- **Jupyter Notebook**

---

## 🚀 Steps in the Project
1. Data cleaning and preprocessing  
2. Feature engineering  
3. Model training using **RandomForestRegressor** (and other ML algorithms)  
4. Model evaluation with RMSLE metric  
5. Hyperparameter tuning for improved performance  

---

## 🔮 Results
- Best model achieved: **0.247 RMSLE score**
- Insights: Certain features like `YearMade` and `ProductSize` have high importance in predicting price.

---

## 📈 Future Work
- Experiment with Gradient Boosting and XGBoost 
- Making complete pipeline
- Deploy the model using Flask/Django or Streamlit

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.  

