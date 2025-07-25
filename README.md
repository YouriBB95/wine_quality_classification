# 🍷 Wine Quality Classification

This project predicts the quality of red wine (scores 3–8) based on physicochemical properties using machine learning.

I explored both Logistic Regression and Random Forest models, handled class imbalance, and interpreted key features like alcohol and acidity to better understand what defines a high-quality wine.

### ✅ Key Highlights:
- Multi-class classification (6 classes)
- Feature scaling + stratified train/test split
- Model comparison (Logistic Regression vs Random Forest)
- GridSearchCV hyperparameter tuning
- Feature importance interpretation

### 📂 Files Included
- `wine_quality_classification.ipynb`: Main notebook
- `requirements.txt`: Dependencies for reproducibility

### 🧠 Most Predictive Features
- Alcohol content
- Sulphates
- Volatile acidity

### 📊 Best Model (Random Forest):
- Accuracy: ~67%
- Best Hyperparameters: `max_depth=20`, `n_estimators=100`, `min_samples_leaf=1`

---
