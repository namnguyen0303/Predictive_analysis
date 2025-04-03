# Heart Failure Prediction Project

## Overview
Machine learning models to predict heart failure severity and mortality risk using clinical data.

Machine learning models to predict:
- **Severity Score** (Regression)
- **Mortality Risk** (Classification)

## 📌 Key Features
| Component          | Techniques Used                          |
|--------------------|------------------------------------------|
| Data Analysis      | EDA, Correlation Heatmaps, Feature Importance |
| Regression Models  | Linear, Ridge, Lasso, Kernel (RBF/Poly) |
| Classification     | Logistic Regression, SVM, Random Forest  |
| Model Evaluation   | MSE, R², Accuracy, Precision-Recall     |

## 🚀 Results Highlight
**Best Performing Models:**
```python
{
  "Regression": {
    "Best Model": "RBF Kernel Regression",
    "MSE": 0.7888,
    "R² Score": 0.7500
  },
  "Classification": {
    "Best Model": "Random Forest",
    "Accuracy": 83.33%,
    "Recall": 63.16%  # Critical for mortality prediction
  }
}
