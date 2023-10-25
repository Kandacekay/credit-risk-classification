# credit-risk-classification
print('-----------------------')

## Credit Risk Analysis Report

### Overview of the Analysis:
The purpose of this analysis was to build and evaluate machine learning models to predict credit risk. The objective was to assist the company in identifying potentially high-risk loans, enabling more informed lending decisions and reducing financial risks associated with loan defaults.

### Results:

#### - Logistic Regression Model (Original Data):

- Accuracy Score: 99%
- Balanced Accuracy Score: 95.20%
- Precision (Label 0 - Healthy Loans): 100%
- Recall (Label 0 - Healthy Loans): 99%
- Precision (Label 1 - High-Risk Loans): 85%
- Recall (Label 1 - High-Risk Loans): 91%

#### - Logistic Regression Model (Oversampled Data):

- Accuracy Score: 99%
- Balanced Accuracy Score: 99.37%
- Precision (Label 0 - Healthy Loans): 100%
- Recall (Label 0 - Healthy Loans): 99%
- Precision (Label 1 - High-Risk Loans): 84%
- Recall (Label 1 - High-Risk Loans): 99%

### Summary:
Both machine learning models, trained on the original data and oversampled data, demonstrated exceptional performance in predicting credit risk. The logistic regression model trained with the oversampled data exhibited outstanding accuracy, balanced accuracy, precision, and recall scores for both healthy and high-risk loans. This model correctly identified 99% of high-risk loans, minimizing the risk of lending to customers likely to default.

### Recommendation:
Based on the analysis, I highly recommend using the logistic regression model trained with oversampled data for credit risk prediction. Its high accuracy and balanced performance across various metrics make it a robust choice for identifying potential high-risk loans. This model can significantly enhance the company's lending decisions, ensuring more accurate risk assessment and reducing financial losses associated with loan defaults.