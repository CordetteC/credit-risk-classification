Credit Risk Analysis Report
Overview of the Analysis:
This analysis aims to assess borrowers' creditworthiness using a logistic regression model. By utilizing historical lending data, the model predicts whether a loan is high risk (1) or healthy (0), in order to help financial institutions make informed decisions.
Model Results:
•	Overall Accuracy: 99.30%  
•	Precision:
-	Healthy Loans (0): 99.79%  
-	High-Risk Loans (1): 86.08%  
•	Recall:
-	Healthy Loans (0): 99.49%  
-	High-Risk Loans (1): 93.89%  
•	F1-score:
-	Healthy Loans (0): 99.64%  
-	High-Risk Loans (1): 89.81% 
Results Summary:
This logistic regression model performs extremely well in healthy loans, with 99.79% prediction precision and 99.49% recall, which is the % of successfully identified healthy loans. The model shows some weakness in identifying high-risk loans, with both lower precision (86.08%) and recall (93.89%). This suggests there may be cases of unnecessary loan denial, but despite this shortcoming, the overall performance of the model is incredibly strong (99.30%). Based on these findings, this model is recommended for use.
