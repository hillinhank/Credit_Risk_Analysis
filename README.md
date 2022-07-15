# Credit_Risk_Analysis
# Overview
The purpose of this analysis is to sample and predict credit risk using several different supervised machine learning models. Python libraries imbalanced-learn and scikit-learn were utilized,  in visual studio code via a Jupyter notebooks local server,  to create this analysis. The machine learning models used include: naive random oversampling, SMOTE, cluster centroids, SMOTEENN, Balanced Random Forest, and Easy Ensemble.

# Results
This credit risk assessments aim was to successfully identify individuals who are cause for concern for repayment i.e. poor credit history. It is important to note that the precision and recall metrics displayed below were used to aid in proper identification of high risk loans, and that this identification is displayed as a “positive result”.

•	RandomOverSampler: 67 high-risk cases and 10,558 low-risk cases were successfully identified in this model. Alternatively, there were 34 false negatives and 6546 false positives returned via this model. This resulted in an accuracy score of 64%, precision of 1%, and recall of 66%.

 

•	Smote: This model successfully predicted 62 high-risk cases and 11,787 low risk cases. However, 39 were false negatives, and 5,317 false positives. This model returned a balanced accuracy score of 65%, precision of 1%, and recall of 61%.


 

•	ClusterCentroids: This model successfully predicted 70 high-risk cases and 6,763 low risk cases. However, 31 were false negatives, and 10,341 false positives. This model returned a balanced accuracy score of 54%, precision of 1%, and recall of 69%.
 
•	Smoteen: This model successfully predicted 76 high-risk cases and 9,538 low-risk. Alternatively, 25 were false negatives, and 7,566 false positives. Resulting in a balanced accuracy score of 67%, precision of 1%, and recall of 73%.
 

# Summary
![image](https://user-images.githubusercontent.com/101481759/179178063-fc3fe9d6-6752-4711-905a-3c5d61babf34.png)
