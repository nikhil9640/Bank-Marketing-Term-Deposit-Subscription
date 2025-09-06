# Bank-Marketing-Term-Deposit-Subscription
This project analyzes data from a bank’s direct marketing campaign with the goal of predicting whether a client will subscribe to a term deposit. The dataset includes demographic, financial, and campaign-related attributes, providing a comprehensive view of client behavior.

# Objective
The main objectives of this project were:
To develop classification models that predict a client’s likelihood of subscribing to a term deposit.
To identify key factors influencing subscription decisions.
To provide actionable insights that can help the bank improve its marketing strategies.

# Outcome
Important predictors identified include contact method, previous campaign outcome (poutcome), campaign month, and call duration.
Subscription rates were higher during certain months (May, August) and for clients with longer call durations.
Among the tested models, ensemble methods (Random Forest) achieved the best predictive accuracy and robustness.
Data preprocessing (handling missing values, encoding, scaling) and EDA were critical to achieving reliable results.

# Methodology (high level):
1. Load data
2. Quick inspection & missingness
3. EDA (printing + saving basic plots)
4. Preprocessing (impute, encode, scale) with ColumnTransformer
5. Train/test split
6. Train baseline models (LogisticRegression, DecisionTree, RandomForest)
7. Evaluate (accuracy, precision, recall, f1, roc-auc) and plot ROC
8. Compare with/without duration (leakage)
9. (Optional) GridSearch for RandomForest
10. Feature importances + save model

# Conclusion
The analysis highlights that timing, communication channel, and client engagement quality play significant roles in determining whether a client subscribes to a term deposit. By focusing on these factors and leveraging predictive models, banks can optimize campaign strategies, improve customer targeting, and enhance conversion rates.
