Customer Churn Prediction

📌 Overview
This project predicts whether a customer is likely to churn (leave the company) using Machine Learning.
The project follows an end-to-end Machine Learning workflow, from data preprocessing and EDA to model training, evaluation, hyperparameter tuning, and model saving.

🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

🔄 Project Workflow

Problem Understanding

Data Understanding

Data Cleaning

Exploratory Data Analysis (EDA)

Handling Missing Values

Categorical Encoding

Train-Test Split

Feature Scaling

SVM Model Training

Model Evaluation

Cross-Validation

Hyperparameter Tuning using GridSearchCV

Pipeline Creation

Final Model Evaluation

🤖 Machine Learning Model
I used Support Vector Machine (SVM) for binary classification.

GridSearchCV was used to tune the model hyperparameters.

Best Parameters
C: 0.1
Kernel: Linear
Gamma: Scale

📊 Final Results

The final model was evaluated on unseen test data.
Metric	Score

1. Accuracy : 78.85%

2. Churn Precision :	62%

3. Churn Recall : 53%

4. Churn F1-Score	: 57%

5. ROC-AUC :	82.62%

💡 Key Learning

Through this project, I learned how to build an end-to-end Machine Learning classification project, including:
* Data preprocessing

* EDA

*Feature encoding

*Feature scaling

*SVM classification

*Cross-validation

*Hyperparameter tuning

*Model evaluation

*ML Pipeline

*Model saving and loading

📁 Project Files

Customer_Churn_Prediction.ipynb — Complete Jupyter Notebook containing the analysis, model building, evaluation, and results.

README.md

🚀 Future Improvements

Feature engineering

Compare multiple classification algorithms

Improve churn recall

Deploy the model using a REST API
