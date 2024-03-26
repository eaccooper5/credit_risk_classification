# Credit Risk Analysis
Module 20 Challenge Assignment

## Overview
The purpose of this module is to attempt to predict the accuracy of credit risk classifications for "high risk" and "low risk" loans. Determinations for whether a loan would be classified either high or low risk was based on the following factors: loan size, borrower income, total borrower debt, each borrower's debt-to-income ratio, the number of accounts each borrower had open, the number of derogatory marks the borrower had in their credit history, and the interest rate of the loan. Based on these factors, the model would predict whether an applicant's credit history was "healthy" or "unhealthy." With an "unhealthy" credit likely rating putting a prospective applicant in the "high risk" category.

## Results

- Accuracy Score: 0.99

- Precision Score [0]: 1.00
- Precision  Score [1]: 0.85

- Recall Score [0]: 0.99
- Recall Score [1]: 0.91


## Summary
The logistic regression model via the confusion matrix finds more "false positives" (102) than "false negatives" (52) which in this case means that more cases were flagged as "healthy loans" than "high risk loans." The accuracy score for the model overall was 0.99 with higher precision scores (1.00) for "low risk" loans and lower precision scores (0.85) for "high risk" loans. Recall scores also varied for "high risk" (0.91) and "low risk" (0.99) with "low risk" scores indicating higher accuracy in prediction.

This model yields results that may be friendly to borrowers in that the number of "false positives" for healthy loans would indicate that borrowers would be more likely to be considered "low risk" when applying for a loan. The lower precision and recall scores on "high risk" loans could indicate that while statistics like borrower income, debt-to-income ratio, and total debts might seem unfavorable they do not account for other factors such as a borrower's habit toward timely, regular payments or careful budgeting or the causes of each borrower's debts and expenses. With these considerations in mind, I would recommend this prediction model in that it leans toward a slightly more borrower friendly model while maintaining an acceptable margin of error for lending institutions.