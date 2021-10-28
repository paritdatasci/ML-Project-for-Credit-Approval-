# Machine-Learning-for-Credit-Approval-
- This project is to build ML model to classify if credit should be approved or not.
- The data is from UC Irvine Machine Learning Repository (http://archive.ics.uci.edu/ml/machine-learning-databases/credit-screening/crx.data)
- The data doesn't provide information of each column because they are personal data which is sensitive.
- To summarize the process that I did in my jupyter notebook:
     1.prepare data 
        1.1 missing value
        1.2 data imputation
        1.3 check imbalanced classification problem
     3. explore data to see relationship and select features to be used for ML models
     4. I tried three models which are SVM, Logistic Regression and K-Nearest Neighbors.
     5. The model that provide the prominent result is Logistic Regression at thresholds 0.72. The reason that I used threshold = 0.72 instead of 0.5 is that I place an importance on approving credit to the right person while a bank is still be able to earn some profit since ,in my opinion, the key success factor in lending business is risk management. 
- What should be done further is to try other models such as RandomForestClassifier and XGBoost. 

