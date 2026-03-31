# Machine Learning Models for Profit Prediction: Comparative Study

## 📌 Overview

This project presents a comparative analysis of multiple machine learning regression models for predicting company profits based on financial data. The implementation is provided as a Jupyter Notebook for easy step-by-step execution and understanding.

The study evaluates model performance across two datasets to analyze both predictive accuracy and generalization capability.

---

## 🎯 Objectives

* Compare multiple regression and ensemble models
* Identify the best model based on accuracy and stability
* Evaluate models using cross-validation
* Analyze generalization across datasets
* Interpret model predictions using SHAP

---

## 📊 Datasets

### Dataset 1: Companies Dataset

* Source: Kaggle
* Features:

  * R&D Spend
  * Administration
  * Marketing Spend
  * Total Spend (engineered feature)
* Target:

  * Profit

### Dataset 2: California Housing Dataset

* Source: Scikit-learn
* Used for evaluating model generalization

---

## ⚙️ Methodology

### Data Preprocessing

* Train-test split (80:20)
* Feature scaling using StandardScaler

### Models Used

* Ridge Regression
* Decision Tree Regressor
* Random Forest (with GridSearchCV tuning)
* Gradient Boosting Regressor
* XGBoost Regressor
* Stacking Ensemble Model

### Evaluation Metrics

* R² Score
* 5-fold Cross-Validation (mean ± standard deviation)

### Interpretability

* SHAP (SHapley Additive Explanations)

---

## 📈 Results Summary

### Dataset 1 (Companies)

* Random Forest showed best stability
* Stacking model achieved highest accuracy

### Dataset 2 (Housing)

* XGBoost and Stacking performed best

👉 Key Insight:
Model performance varies across datasets — no single model is universally optimal.

---

## 📊 Visualizations

The notebook includes:

* Model comparison plots
* Actual vs Predicted plots
* Residual analysis
* Feature importance
* SHAP summary plots

---

## ▶️ How to Run

1. Clone the repository:

```bash id="8k1d7f"
git clone https://github.com/your-username/profit-prediction-ml-comparison.git
```

2. Open the notebook:

```bash id="3g7k2l"
jupyter notebook
```

3. Run all cells step by step.

---

## 📦 Requirements

Install required libraries:

```bash id="2m4k9p"
pip install pandas numpy scikit-learn xgboost shap matplotlib seaborn
```

---

## 📁 Project Structure

```id="4n2h7x"
├── profit_prediction.ipynb
├── README.md
```

---

## 🔗 Code Availability

The complete implementation is available in this notebook for reproducibility and further research.

---

## 🔮 Future Work

* Apply deep learning models (LSTM, Neural Networks)
* Use time-series financial data
* Improve hyperparameter tuning
* Expand to more datasets
* Develop real-time prediction systems

---

## 👨‍💻 Author

Ramcharan Reddy Kandhuru

---

## 📜 License

This project is intended for academic and research purposes.
