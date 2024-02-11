# risk-classification-challenge

Risk report

The purpose of this analysis is to explain the model for predicting healthy loans versus high risk loans. It includes an analysis of the initial training and test results.


- The accuracy score is 99%, meaning that the model will accurately determine which classification the loan should go into the majority of the time.
- The preciion score for healthy loans is 100%, meaning it will always properly classify healthy loans. The precision for unhealthy loans is 87, meaning there may be some misclassifications in this class. This could be remediated with more training data for unhealthy loans.
- The recall score for healthy loans is 100%, while the recall score for unhealthy loans is 89%. This is the measure of capured positives over actual positives, meaning the model may have an occasional mistake.



To summarize, the model has a high accuracy, and very high precision when predicting healthy loans. For this reason I can reccomend the model for determining when a loan may be healthy, but when determining unhealthy loans some human intervention may be required. Due to the imperfect precision of the unhealthy loan predictions, I cannot recommend using the model to only determine if a loan is unhealthy.
