📌 Overview

This project demonstrates how to use Python and scikit-learn to classify breast cancer tumors as malignant or benign based on biological features from a public dataset.
It covers the complete machine learning pipeline:

    Loading biological data (Breast Cancer dataset from scikit-learn)

    Preprocessing (feature scaling)

    Training a Random Forest Classifier

    Evaluating the model's performance

The code is designed to run in a Jupyter Notebook without errors and can be easily extended for other datasets.

📊 Dataset

The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset included in sklearn.datasets.
It contains 30 numeric features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.
The target variable indicates whether the tumor is:

    0 → Malignant (cancerous)

    1 → Benign (non-cancerous)

🛠 Installation

To run this project, you need Python 3.8+ and the following libraries:

bash
pip install pandas scikit-learn

🚀 Usage

    Clone this repository:

bash
git clone [https://github.com/your-username/your-repo-name.git](https://github.com/Jawad-Alharake/Breast-Cancer-Classification-using-Machine-Learning/blob/main/Python%20code)

Open the Jupyter Notebook:

    bash
    jupyter notebook breast_cancer_classification.ipynb

    Run all cells to:

        Load the dataset

        Preprocess the features

        Train a machine learning model

        Evaluate the results

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

📜 License

This project is licensed under the MIT License — feel free to use, modify, and share it.
