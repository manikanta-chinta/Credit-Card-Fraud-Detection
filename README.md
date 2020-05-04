# Credit-Card-Fraud-Detection

## Dataset

The datasets contains credit card transactions over a two day collection period in September 2013 by European cardholders. There are a total of 284,807 transactions, of which 492 (0.172%) are fraudulent.

The dataset contains numerical variables that are the result of a principal components analysis (PCA) transformation. This transformation was applied by the original authors to maintain confidentiality of sensitive information. Additionally the dataset contains Time and Amount, which were not transformed by PCA. The Time variable contains the seconds elapsed between each transaction and the first transaction in the dataset. The Amount variable is the transaction amount, this feature can be used for example-dependant cost-senstive learning. The Class variable is the response variable and indicates whether the transaction was fraudulant.

The dataset was collected and analysed during a research collaboration of Worldline and the Machine Learning Group of Université Libre de Bruxelles (ULB) on big data mining and fraud detection.

## Model

Leveraged SMOTE technique to balance the data set and implemented XGBoost model.

## Performance

The final model achieves an overall f1 score of 0.86, with 87% sensitivity (recall) and 86% precision for the Fraud class. That is, the model correctly identifies 87% of the fraud cases (true positives) and also 86% of the transactions predicted as fraudulent were actually fraudulent. 

We are idenitifying as many fraudualent transactions as possible and at the same time not classifying too many valid transactions as fraudulent.
