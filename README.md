This is an A-Score credit risk model pertaining to retail loans. <br>
Dataset contains over 800,000 rows and 75+ independent variables (financial and non-financial) which were originally extracted from Kaggle, and the dataset's period ranges from 2007 to 2015.

The Dataset has numerous categorical and continuous variables which will be binned using the WoE (Weight of Evidence) and IV method.

Lastly, the model's validation will be tested using AUC-ROC, Gini and KS curve as this is a largely imbalanced dataset.

The PD will then be converted into Scorecard via normalization, and respective cut-offs will be assigned. 

Other algorithms such as Decision Tree, Random Forest, XgBoost and Deep Learning (ANN) will be experimented to test against Logistic Regression results.
