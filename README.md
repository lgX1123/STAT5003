# STAT5003
UK Accidents 10 years history with many variables

Dataset from [Kaggle](https://www.kaggle.com/datasets/benoit72/uk-accidents-10-years-history-with-many-variables).

The original datasets were large, with 1.6 million, 3M and 2.2 million instances, with 32, 22 and 15 features per section respectively. Then merge Vehicles with Accidents by “Accident_Index” and then merge it with Casualties by (“Accident_Index”, “Vehicle_Reference”). After merging, the final dataset consists of 3.3M rows and 66 columns. “Accident_Severity” is target which is what we need to predict.

Several models were created including Random Forest, Decision tree with bagging, **XGBoost**, Naive Bayes.
