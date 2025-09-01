📌 Overview

This project demonstrates how to use Python and scikit-learn to classify breast cancer tumors as malignant or benign based on biological features from a public dataset.
It covers the complete machine learning pipeline:

    Loading biological data (Breast Cancer dataset from scikit-learn)

    Preprocessing (feature scaling)

    Training a Random Forest Classifier

    Evaluating the model's performance

📊 Dataset

The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset included in sklearn.datasets.
It contains 30 numeric features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.
The target variable indicates whether the tumor is:

    0 → Malignant (cancerous)

    1 → Benign (non-cancerous)

📈 Example Output

When you run the notebook, you will see:

    Dataset preview (first 5 rows)

    Model accuracy score

    Detailed classification report with precision, recall, and F1-score

Example:

text
Model Accuracy: 0.97
Classification Report:
              precision    recall  f1-score   support

   malignant       0.95      0.97      0.96        43
      benign       0.98      0.97      0.97        71

accuracy                           0.97       114
macro avg       0.97      0.97      0.97       114
weighted avg    0.97      0.97      0.97       114
