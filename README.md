# Credit_Card_Fraud_Detection
Created a machine learning model to detect fraudulent credit card transactions. Balanced the data using SMOTE and trained models like Logistic Regression and Random Forest. Focused on improving accuracy and recall to catch fraud effectively.


**📄 Project Description**

This project aims to detect fraudulent credit card transactions using machine learning techniques. Since fraudulent activities are very rare compared to normal transactions, the dataset is highly imbalanced. We applied data preprocessing, balancing techniques, trained multiple models, and evaluated them to identify frauds efficiently.

**🚩 Problem Statement**

Credit card fraud causes significant financial losses globally. Early detection is critical but challenging due to the small number of fraud cases. The goal is to accurately classify transactions as fraudulent or legitimate, minimizing false negatives while maintaining high precision. 

**📊 Dataset**

The dataset contains anonymized credit card transactions.

Features: V1 to V28 (PCA-transformed), Time, Amount, and Class (0 = Normal, 1 = Fraud).

Source: Kaggle - Credit Card Fraud Detection Dataset   


**🛠 Approach**

1. Data Exploration:

   Analyzed data distribution and correlation between features.

2. Data Preprocessing:
      Handled class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
      Scaled 'Amount' and 'Time' features using StandardScaler.

3. Model Building:
      Trained models like Logistic Regression, Decision Tree, Random Forest, and XGBoost.

4. Hyperparameter Tuning:
      Used GridSearchCV to find optimal model parameters.

5. Model Evaluation:
     Evaluated models based on Precision, Recall, F1-Score, and ROC-AUC. 


  **🤖 Models Used**
  
Logistic Regression

Decision Tree

Random Forest 


**📈 Evaluation Metrics**

Precision: Correct fraud predictions out of all predicted frauds.

Recall (Sensitivity): Correct fraud predictions out of all actual frauds.

F1-Score: Balance between precision and recall.

ROC-AUC Score: Area under the Receiver Operating Characteristic curve. 


**🏆 Results** 

Random Forest and XGBoost achieved the highest performance.

Focused on maximizing recall to ensure most fraudulent transactions are detected.

Achieved a ROC-AUC score of approximately 0.98 (depending on parameter tuning).





