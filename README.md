🏦 Bank Loan Approval Prediction using PySpark
📌 Overview
This project presents a machine learning pipeline developed with PySpark to predict bank loan approvals. It leverages various classification algorithms, including Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Decision Trees, to evaluate applicant eligibility based on historical data.

🔍 Problem Statement
Financial institutions often face challenges in assessing loan applications efficiently and accurately. This project aims to automate the loan approval process by building predictive models that analyze applicant data to determine loan eligibility, thereby enhancing decision-making and reducing manual workload.

🧰 Features and Methodology
Data Preprocessing
Handling Missing Values: Imputation techniques to address null entries.

Feature Engineering: Creation of new features such as Combined Income and Income-to-Loan Ratio.

Encoding Categorical Variables: Utilizing StringIndexer and OneHotEncoder for categorical data.

Feature Scaling: Applying StandardScaler to normalize feature values.

Data Splitting: Dividing the dataset into training and testing sets.

Addressing Class Imbalance: Implementing Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset.

Model Training and Evaluation
Algorithms Used:

Decision Tree

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Random Forest

Model Optimization: Hyperparameter tuning using GridSearchCV.

Evaluation Metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve

Results
The models were evaluated based on their performance metrics:


Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Decision Tree	78.38%	79.08%	78.38%	76.96%	0.73
SVM	80.00%	100.00%	44.00%	62.00%	0.78
KNN	74.32%	72.00%	98.00%	83.00%	0.66
Random Forest	81.08%	79.00%	96.00%	87.00%	0.83
The Random Forest model demonstrated the best overall performance, making it the preferred choice for deployment.

🛠️ Technologies Used
Programming Language: Python

Frameworks and Libraries:

PySpark (v3.x)

scikit-learn

matplotlib

seaborn

📦 Installation
To set up the project locally:

git clone https://github.com/yourusername/loan-approval-prediction.git
cd loan-approval-prediction
pip install -r requirements.txt

📄 Documentation
For a detailed explanation of the project, refer to the Project_Report.docx located in the docs directory.
