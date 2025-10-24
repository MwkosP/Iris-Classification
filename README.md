# 🌸 Iris Classification (Multi-Model ML Pipeline)

A complete machine learning pipeline built on the classic **Iris dataset**, using multiple models, scalers, and automated hyperparameter tuning with `GridSearchCV`.

---

## ⚙️ Overview

- **Dataset:** Iris (150 samples, 4 numeric features, 3 species)  
- **Goal:** Predict iris species using geometric flower measurements  
- **Models tested:** `KNN`, `SVC`, `RandomForest`, `LogisticRegression`, `GradientBoosting`  
- **Preprocessing:** Scaling (`StandardScaler`, `MinMaxScaler`, `RobustScaler`, `Normalizer`)  
- **Optimization:** Full `GridSearchCV` pipeline with CV=5  
- **Metrics:** Accuracy, confusion matrix, classification report  

---

## 🧠 Best Result

| Model | Scaler | Accuracy |
|--------|---------|-----------|
| **KNN** | **Normalizer()** | **≈ 96–98%** |

Confusion matrix:
