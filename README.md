# 🌸 Iris Classification (Multi-Model ML Pipeline)

A full machine learning pipeline built on the classic **Iris dataset**, featuring multiple models, preprocessing strategies, and an interactive **3D PCA visualization** using Plotly.

---

## ⚙️ Overview

- **Dataset:** Iris (150 samples, 4 numeric features, 3 flower species)  
- **Goal:** Predict iris species (`setosa`, `versicolor`, `virginica`)  
- **Models tested:** `KNN`, `SVC`, `RandomForest`, `LogisticRegression`, `GradientBoosting`  
- **Preprocessing:** `StandardScaler`, `MinMaxScaler`, `RobustScaler`, `Normalizer`  
- **Optimization:** Full `GridSearchCV` pipeline with CV=5  
- **Metrics:** Accuracy, confusion matrix, classification report  
- **Visualization:** PCA (3D) with Plotly  

---
<img width="1123" height="550" alt="image" src="https://github.com/user-attachments/assets/dc368353-19a8-4fa2-b620-3849723728a4" />

## 🧠 Best Result

| Model | Scaler | Accuracy |
|--------|---------|-----------|
| **KNN** | **Normalizer()** | **≈ 96–98%** |

**Confusion Matrix:**
