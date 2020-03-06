Bulding a classifier using Naïve Bayesian technique 

dataset source:
https://www.kaggle.com/uciml/pima-indians-diabetes-database 

Evalute tarining data based on confusion matrix:

Classification Error: Overall, how often is the classifier correct?  
Accuracy = (TP + TN) / (TP + FP + TN +FN) 

Classifier Error: Overall, how often is the classifier correct? 
Error = (FP + FN) / (TP + FP + TN +FN) 

Classifier Sensitivity: When the actual value is positive, how often is the prediction correct? 
Sensitivity = TP / (FN + TP) 

Classifier Specificity: When actual value is negative, how often is the prediction correct? 
Specificity = TN / (TN/FP) 