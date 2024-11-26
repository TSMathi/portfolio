Loan Approval Prediction
📄 Overview
This project aims to predict loan approvals based on a dataset of applicant details. Using a preprocessing pipeline and a Logistic Regression model, the final model achieved an accuracy of 89%.

✨ Features
Data Preprocessing: Imputation, scaling, and encoding.
Model Training: Logistic Regression classifier with optimized preprocessing.
Model Evaluation: Metrics include accuracy, confusion matrix, and classification report.
📊 Dataset
The dataset includes:

Applicant Information: Features like age, income, and employment status.
Loan Details: Information such as loan amount, tenure, and purpose.
Loan Status: Target variable indicating loan approval (1) or rejection (0).


🧠 Model
Logistic Regression Classifier
The dataset was split into:

Training Set: 64% of the data.
Validation Set: 16% of the data
Test Set: 20% of the data for final evaluation

Preprocessing Steps
Numerical Features:
Missing values replaced with the mean.
Standardized using StandardScaler.
Categorical Features:
Missing values replaced with the most frequent value.
Encoded using OneHotEncoder (handle_unknown='ignore').

🔍 Results
Model Accuracy: 89% on the test set.
Confusion Matrix: Analysis of true positives, false positives, etc., is available in the project notebook.
Classification Report: Precision, recall, and F1-score metrics.

🛠️ Tools and Libraries
Python 3.x
scikit-learn: For preprocessing, modeling, and evaluation.
pandas: For data manipulation.
numpy: For numerical computations.
matplotlib/seaborn: For data visualization.

🚀 How to Run the Project
Clone the repository:
bash
Copiar código
git clone <repository-url>
Install dependencies:
bash
Copiar código
pip install -r requirements.txt
Run the Jupyter Notebook:
bash
Copiar código
jupyter notebook Loan_Approval_Prediction.ipynb

📈 Future Enhancements
Test additional classifiers like Random Forest or Gradient Boosting.
Perform hyperparameter optimization with GridSearchCV.
Add more features from the dataset to improve model performance.
🙌 Acknowledgments
This project is inspired by the need for efficient loan approval systems to help banks streamline their decision-making processes.
