Credit card fraud detection using XGBoostClassifier

Here the given Dataset is imbalanced so I have used the upsampling method to balance the given dataset 

Accuracy: 

XGBClassifier resulted in 99.99995 % accuracy 
RandomForestClassifier resulted in 99.99997 % accuracy

Confusion Matrix:

XGBClassifier misclassified 7 not fraud details as fraud and correctly classified all the fraud details
RandomForestClassifier misclassified 4 not fraud details as fraud and correctly classified all the fraud details

Precision:

XGBClassifier resulted in 99.9901 % precision 
RandomForestClassifier resulted in 99.9943 % precision

Recall:

XGBClassifier resulted in 100 % recall 
RandomForestClassifier resulted in 100 % recall

F1-score

XGBClassifier resulted in 99.9950 % f1-score 
RandomForestClassifier resulted in 99.9971 % f1-score

logloss:

XGBClassifier resulted in 0.0017  loss 
RandomForestClassifier resulted in 0.00097 loss
