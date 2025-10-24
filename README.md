# SVM_EG
🧠 Cancer Detection using Support Vector Machine (SVM)

This project uses Support Vector Machine (SVM) models to classify breast cancer data into malignant and benign categories.
It compares different SVM kernels — Linear, Polynomial, and RBF (Gaussian) — to find the best-performing model for cancer detection.

📂 Project Overview

The dataset is preprocessed and cleaned using Pandas.

Features are scaled using StandardScaler for optimal SVM performance.

Models are trained using Scikit-learn’s SVC with three kernel types:

Linear

Polynomial

RBF (Radial Basis Function)

Each model’s performance is evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

🧩 Tech Stack

Programming Language: Python

Libraries Used:

pandas

numpy

scikit-learn

matplotlib

seaborn

🧬 Dataset

Name: Cancer_Data.csv

Source: Breast Cancer Wisconsin (Diagnostic) Dataset

Target Column: diagnosis

M: Malignant

B: Benign

⚙️ Steps Performed

Import libraries and dataset

Data cleaning (remove unnecessary columns)

Feature and label separation

Feature scaling using StandardScaler

Train-test split

Model training with SVM (Linear, Poly, RBF)

Evaluation and performance comparison

📊 Results
Kernel	Accuracy	Remarks
Linear	~97%	Performs well on most datasets
Poly	~96%	Slightly lower due to overfitting
RBF	~98%	Best performance overall

(Results may vary slightly based on random state and dataset split)

📈 Sample Output
ACCURACY-SCORE OF SVC(kernel='rbf'): 0.982
CONFUSION MATRIX:
[[71  1]
 [ 2 40]]

💡 Future Enhancements

Add feature importance analysis

Try other ML algorithms (Random Forest, Logistic Regression, etc.)

Implement deep learning models for improved accuracy

👨‍💻 Author

Karthik L
📫 LinkedIn
 (www.linkedin.com/in/karthik-laiju)
💻 GitHub
 (https://github.com/I-Karthik-L)
