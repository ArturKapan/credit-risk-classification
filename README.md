# credit-risk-classification

Analysis show that collected data can be effectively used to train and test the Machine Learning Classification Model. For better preditions solving the imbalance sampling issue is needed.

Randomly oversampling the data helps us to get higher balanced accuracy and recall scores. With higher recall value, model can predict risky loans more accurately.

With incorrect predictions we have two issues:

False positives (where users are flagged as risky, but are actually healthy)
False negatives (where users are not flagged as risky but are actually risky)
both cases have its costs. It is important to predict both 1s and 0s. Therefore, model should have good accuracy in terms of both.
