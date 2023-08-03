This is a credit risk model pertaining to retail loans. PD, LGD and EAD will be assessed.<br>
Dataset contains over 800,000 rows, and the dataset's period ranges from 2007 to 2015.

The Dataset has numerous categorical and continuous variables which will be binned using the WoE (Weight of Evidence) and IV method.
This model's probability of default prediction will be built using Decision Tree, Logistic Regression and Random Forest.

Lastly, the model's validation will be tested using AUC-ROC, Gini and KS curve as this is a largely imbalanced dataset. Hence, a normal accuracy TP FP test won't be an accurate assessment. 

The PD will then be converted into Scorecard via linear transformation, and respective cut-offs will be assigned. 
