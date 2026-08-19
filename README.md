Titanic Survival Prediction using Machine Learning

📌 Project Overview

This project builds a complete Machine Learning pipeline using the Titanic dataset to predict passenger survival. The project uses Logistic Regression as the baseline classification algorithm.

🎯 Objectives

- Clean and preprocess the Titanic dataset
- Handle missing values
- Encode categorical features
- Scale numerical features
- Train a Logistic Regression model
- Evaluate model performance
- Perform 5-Fold Cross-Validation
- Save and reload the trained model

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Joblib
- Google Colab / Jupyter Notebook

📊 Features Used

- Pclass
- Sex
- Age
- SibSp
- Parch
- Fare
- Embarked

Target: "Survived"

🔄 Workflow

1. Load the Titanic dataset
2. Select features and target
3. Handle missing values
4. Apply One-Hot Encoding
5. Standardize numerical features
6. Build a Scikit-learn Pipeline
7. Train Logistic Regression
8. Evaluate the model
9. Perform 5-Fold Cross-Validation
10. Save and reload the trained model

📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC

💾 Model Persistence

The trained pipeline is saved as:

"model.joblib"

The saved model is then reloaded and used to make predictions on sample data.

📝 Key Takeaways

- Logistic Regression provides a simple baseline for binary classification.
- Proper preprocessing is important for handling missing and categorical data.
- Cross-validation provides a more reliable performance estimate.
- Model persistence allows the trained pipeline to be reused later.
- Feature engineering and other machine learning models can be explored for further improvement.

📁 Deliverables

- "Task5.ipynb" – Jupyter/Colab notebook
- "model.joblib" – Saved trained model
- "images/" – Optional folder containing plots

👩‍💻 Internship Task

Data Science with Python Internship – Task 5
