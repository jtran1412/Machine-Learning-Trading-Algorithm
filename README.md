# Machine-Learning-Trading-Algorithm
## Summary
I create 2 machine learning trading algorithms that create buy and sell signals. The goal is to beat a baseline buy and hold strategy. 
## Model explination
Both models uses a short and long window Simple Moving Average (SMA) to generate trading signals. One model uses the SVC classifier from the sklearn.SVM learning method to fit the training data and make predictions. The other model uses the LogisticRegression classifier from the sklearn.linear_model learning method.
## Result
The SVC classifier model beat the buy and hold strategy in a 6 year time period. The LogisticRegression classifier model did not beat the buy and hold strategy in a 6 year time period, but it did beat it in a 5 year period.
## Possible future work
If I had more time, I would try to use other machine learning classifiers such as:<br>
-k-Nearest Neighbors (k-NN)<br>
-Decision Trees<br>
-Neural networks<br>
-Naive Bayes<br>
-k-Means<br>
-Adaboost<br>
-Gradient Boosting Machines (GBMs)<br>
-XGBoost<br>
-CatBoost<br>
-LightGBM<br>
-Random Forest<br>





