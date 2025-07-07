# ML-Model-Comparison-Project-Scikit-learn-

This project demonstrates a side-by-side comparison of three fundamental classification models using Scikit-learn:

K-Nearest Neighbors (KNN)

Logistic Regression

Support Vector Classifier (SVC)

All models are trained and evaluated on the classic Iris dataset.

🔧 What’s Included

Dataset loading via load_iris()

Train-test split (train_test_split)

Feature scaling with StandardScaler

Three models trained: KNN, Logistic Regression, and SVC

Evaluation using:

accuracy_score

confusion_matrix

Results printed in a loop for clean comparison

📁 Files & Structure

model_comparison.py – Main Python file with full code

README.md – This file

🛠️ Requirements

pip install scikit-learn

🚀 How to Run

python model_comparison.py

📌 Output Example

===== KNN =====
Accuracy: 1.0
Confusion Matrix:
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]

===== Logistic Regression =====
Accuracy: 0.9667
Confusion Matrix:
[[10  0  0]
 [ 0  9  1]
 [ 0  0 11]]

===== SVC =====
Accuracy: 0.9667
Confusion Matrix:
[[10  0  0]
 [ 0  9  1]
 [ 0  0 11]]

✅ What You’ll Learn

How to compare multiple models in a structured way

How to scale data for sensitive models (SVM, KNN)

How to evaluate with accuracy and confusion matrix

How to organize clean ML comparison projects

📌 Next Steps (Optional)

Add GridSearchCV for tuning

Use CSV-based datasets

Add visual comparison (bar chart of accuracy)

Build scikit-learn Pipeline

📜 License

MIT License. Free to use and modify.

