# Machine-Learning-for-Credit-Approval-
This project is to build ML model to classify if credit should be approved or not.
The data is from UC Irvine Machine Learning Repository (http://archive.ics.uci.edu/ml/machine-learning-databases/credit-screening/crx.data)
The data doesn't provide information of each column because they are personal data which is sensitive.
To summarize the process that I did in my jupyter notebook:
- 1. prepare data  -->
       a) missing value
       b) data imputation
       c) check imbalanced classification problem
- 2. explore data to see relationship 
- 3. features selection
- 4. Spliting data into (X_train,y_train), (X_val, y_val), (X_test,y_test)
- 5. I tried three models which are SVM, Logistic Regression and K-Nearest Neighbors.
- 6. Hyperparameter Tuning
- 7. The model that provide the prominent result is Logistic Regression at thresholds 0.72. The reason that I used threshold = 0.72 instead of 0.5 is that I place an importance on approving credit to the right person while a bank is still be able to earn some profit since ,in my opinion, the key success factor in lending business is risk management. Logistic Regression Model gives precision 94%, recall 72% and f1 score 81% by setting approve credit as Positive.  

What should be done further is to try other models such as RandomForestClassifier and XGBoost. 

