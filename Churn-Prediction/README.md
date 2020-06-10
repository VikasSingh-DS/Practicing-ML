# Churn-Prediction

There are still 7043 customers in the database, and 20 potential predictors.

The data are available in one data file with 7043 rows that combines the calibration and validation customers. “calibration” database consisting of 4000 customers and a “validation” database consisting of 3043 customers.

# Result

Comparing the two ROC curves, we can see the distance between blue and red line of XGBC is greater than the distance between blue and red line of LR. Hence it can safely be said that XGBC,in general, is better at discriminating between positives and negatives than LR. Also XGBC(~ 88.67%) auc score (which is the area under the roc curve) is greater than LR(~ 84.97%). It seems the higher the area, the further the classifier is off the red diagonal line and vice versa and hence more accurate. Since XGBC has more area under the ROC curve than LR, therefore XGBC is more accurate.
