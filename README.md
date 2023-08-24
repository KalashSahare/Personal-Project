# Personal-Project
Project done in the period 2019 to 2023
## Credit Card Fraud Detection 
Data set taken from kaggle  https://www.kaggle.com/mlg-ulb/creditcardfraud .  

There are 2848070 observations in the inflated credit card fraud dataset.

There are 31 variables in the dataset.

Build decision tree model using Sklearn and Snap ML

Build SVM using Sklearn and Snap ML

|  Model   | ROC_AUC | Hinge_Loss | Accuracy | 
|----------|----------|----------|------------|
|Scikit_Learn Dicision Tree|0.966263 | 1.090794 | 0.965743 |
| Snap_ML Dicision Tree | 0.966098 | 1.091387 | 0.965130 |
| Scikit_Learn SVM | 0.984496 |  0.233667 | 0.965743  |
| Snap_ML SVM | 0.984524 | 0.228495 | 0.965130 |

## Syndey Rain Prediction
Data set was taken from [Australian gov website](http://www.bom.gov.au/). 

no of rows 3271 and no of columns  22

algorithms: Linear Regression, KNN, Decision Trees, Logistic Regression, SVM 

metric: Accuracy Score, Jaccard Index, F1-Score, LogLoss, Mean Absolute Error, Mean Squared Error, R2-Score
### Linear Regression
MAE : 0.25631881597387884

MSE : 0.11572220135633016

R2 : 0.4271240949310029
### KNN k=4
Accuracy Score : 0.8183206106870229

Jaccard Index : 0.4251207729468599

F1 Score : 0.5966101694915255
### Decision Tree 
Accuracy Score : 0.8183206106870229

Jaccard Index : 0.48034934497816595

F1 Score : 0.6489675516224188
### Logistic Regression
Accuracy Score : 0.8366412213740458

Jaccard Index : 0.5091743119266054

F1 Score : 0.6747720364741641

Log Loss Score : 0.38106374371303714
### SVM
SVM Accuracy Score:  0.833587786259542

SVM Jaccard Index:  0.801094890510949

SVM F1 Score:  0.6625386996904025
## Yellow Taxi Tip projection
Data set is available on  NYC TLC website https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page (all rights reserved by Taxi & Limousine Commission(TLC), City of New York). The data was taken from https://s3.amazonaws.com/nyc-tlc/trip+data/yellow_tripdata_2019-06.csv

The data set was too large it was reduced to 500000 rows and 597 columns

Model used: Regression tress from Sklearn and Snap ML

[Decision Tree Regressor] Snap ML vs. Scikit-Learn speedup : 4.69x 

[Scikit-Learn] MSE score : 1.704

[Scikit-Learn] Mean Absolute error score : 0.733

[Snap ML] MSE score : 1.761

[Snap ML] Mean Absolute Error score : 0.733
## Vibration Analysis of wing
The link for the workbench files https://drive.google.com/drive/folders/1E5jwpiQeO-BtytcThAzSciiWuDHirnDm?usp=drive_link

##
