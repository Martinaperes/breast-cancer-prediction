# 🧠 Breast Cancer Prediction

This project predicts whether a breast tumor is **benign (non-cancerous)** or **malignant (cancerous)** using supervised machine learning models.

---

## 📊 Dataset
- **Source:** [Breast Cancer Wisconsin (Diagnostic) Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- Each row represents a patient’s tumor measurements.
- The **target** column (`diagnosis`) has two values:
  - `M` = Malignant  
  - `B` = Benign
---

## 🧮 Machine Learning Models
We trained and compared two models:
1. **Decision Tree Classifier**
2. **Random Forest Classifier**

---

## ⚙️ Libraries Used
```python pandas, numpy, matplotlib, seaborn
pandas, numpy, matplotlib, seaborn
scikit-learn (train_test_split, StandardScaler, DecisionTreeClassifier, RandomForestClassifier)
