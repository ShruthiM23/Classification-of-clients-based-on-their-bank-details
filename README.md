# Classification-of-clients-based-on-their-bank-details

# Problem Statement

The classification of clients applying for loan into bad clients and good clients with respect to the various details regarding the client provided to the bank so the bank could make informative decision to avoid risk of non-repayment of loan and hence reduce liquid damage to the bank.

# Feature Description:

![image](https://user-images.githubusercontent.com/85027425/129475277-af1919d8-9477-484d-83ae-a4a37f0db7da.png)

# Project Workflow:

1. Explanatory Data Analysis<br>
2. Logistic Regression<br>
3. Logistic Regression(balanced data)<br>
4. Logistic RFE Regression<br>
5. Gaussian Naive Bayes	<br>
6. KNN classifier	<br>
7. Decision Tree<br>
8. Random Forest<br>
9. XGBoost<br>
10. 10.Stacked model with final estimator as XGBoost<br>

# Summary of the model performace with evaluation metrics:

![image](https://user-images.githubusercontent.com/85027425/129475461-8f9d2e45-b3b8-44cb-8e1a-5e4f0fe3bd18.png)

# Conclusion:

As per the table above XG Boost model gives the best results with an AUC score of 97% and an accuracy score of 92% . However, scores are not only the criteria to decide the best model we also have to take overfitting/underfitting into consideration. XGBoost of course gives best score but is slightly overfitted. Stacked model being 1% less accurate is better balanced than XGBoost and hence, best model is concluded as Stacked model with final estimator as XGBoost.


