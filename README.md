# 🩺 Maternal Health Risk Predictor

This machine learning project predicts maternal health risk levels — **Low**, **Mid**, or **High** — based on key clinical indicators.  
The model is trained on the UCI Maternal Health Risk dataset and optimized for both performance and interpretability.

---

## 📊 Model Overview

- **Final Model**: XGBoost Classifier  
- **Accuracy**: 82%  
- **Macro F1 Score**: 0.83  
- **Key Features**: Blood Pressure (Systolic/Diastolic), Blood Sugar, Body Temperature

---

### ✅ Classification Report (XGBoost)

| Class      | Precision | Recall | F1-score | Support |
|------------|-----------|--------|----------|---------|
| High Risk  | 0.85      | 0.87   | 0.86     | 47      |
| Low Risk   | 0.82      | 0.82   | 0.82     | 80      |
| Mid Risk   | 0.80      | 0.79   | 0.79     | 76      |

---

### 🧩 Confusion Matrix
[[41 1 5]
[ 4 66 10]
[ 3 13 60]]



---

## 🧠 What Was Done

- Preprocessed dataset and handled class imbalance using **SMOTE**
- Performed feature selection using Random Forest Importance
- Trained and compared multiple models (Random Forest, XGBoost)
- Hyperparameter tuning with performance evaluation using F1, Recall, and Confusion Matrix

---

## 📁 Files

- `maternalriskpredictor.ipynb` — Jupyter notebook with full model pipeline  
- `model.pkl` — Saved XGBoost model for deployment 
---

## 🚀 Next Steps

- Deploy model using **Streamlit**
- Integrate prediction **confidence levels**
- Extend system to mobile or offline-first platforms for field use

---

## 📌 Dataset Reference

- UCI Maternal Health Risk Data Set  
  [https://archive.ics.uci.edu/ml/datasets/Maternal+Health+Risk+Data+Set](https://archive.ics.uci.edu/ml/datasets/Maternal+Health+Risk+Data+Set)

---

## 💡 Author

**Olamide Idowu**  
*Data Scientist | ML Engineer*  
GitHub: [@OlamideIdowu](https://github.com/OlamideIdowu)
LinkedIn: https://www.linkedin.com/in/idowuolamide/
