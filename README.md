📘 Logistic Regression – Binary Classification
📌 Overview

This project implements Logistic Regression for a binary classification problem using the Breast Cancer Wisconsin dataset.
The goal is to train a model that predicts whether a tumor is malignant (0) or benign (1) based on several medical features.

📂 Project Structure

task4-logistic-regression/

│
├── LogisticRegression.ipynb

└── README.md


(Dataset is loaded directly from sklearn, so no CSV is required.)

🛠️ Tools & Libraries

Python

NumPy

Pandas

Scikit-Learn

Matplotlib

Seaborn

📊 Steps Performed

Loaded Breast Cancer dataset from scikit-learn

Converted it into a DataFrame

Performed train–test split (80/20)

Standardized features using StandardScaler

Trained Logistic Regression model

Evaluated model using:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

ROC Curve & AUC

Plotted Precision-Recall curve

Checked feature importance using coefficients

🔍 Key Findings

Model achieved high accuracy and AUC score (exact numbers depend on your run).

ROC curve showed strong separation between classes.

Precision and Recall both performed well, indicating reliable predictions.

Threshold tuning demonstrated how Precision–Recall tradeoff changes.

Important features were identified using regression coefficients.

▶️ How to Run

Open the notebook in Google Colab or Jupyter Notebook

Run all cells — no dataset download is required

Review the evaluation metrics and plots

✅ Conclusion

Logistic Regression performed strongly on this dataset, making it a good baseline model for binary medical classification tasks.
