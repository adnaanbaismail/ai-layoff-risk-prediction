# AI Layoff Risk Prediction

A multiclass machine learning pipeline built to predict employee layoff vulnerability (`Low`, `Medium`, `High`) based on company size, job role, industry, education level, and workforce exposure to AI automation.

The model achieves **93% overall accuracy** and balanced precision/recall across all three risk categories using a standardized Logistic Regression baseline.

---

## Model Performance & Evaluation

The model was evaluated on a test set of **4,000 samples** using Scikit-Learn's `classification_report`:

```text
              precision    recall  f1-score   support

    Low (0)       0.95      0.95      0.95      1296
 Medium (1)       0.91      0.89      0.90      1329
   High (2)       0.95      0.95      0.95      1375

    accuracy                           0.93      4000
   macro avg       0.93      0.93      0.93      4000
weighted avg       0.93      0.93      0.93      4000
