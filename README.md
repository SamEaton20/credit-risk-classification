# credit-risk-classification
# Overview
This code will help predict loan risk classification, healthy or high-risk, based on data in the CSV file.
# Results
- Accuracy
  - The model has an overall accuracy of 99%, meaning it correctly predicted the loan status (either healthy or high-risk) 99% of the time. 
 - Precision Score
   - For class 0 (healthy loans), the precision is 1.00, indicating that when the model predicts a loan as healthy, it is correct 100% of the time.
   - For class 1 (high-risk loans), the precision is 0.86, meaning 86% of the time when the model predicts a loan as high-risk, it is correct.
 - Recall Score
   - For class 0 (healthy loans), the recall is 0.99, meaning the model correctly identifies 99% of all healthy loans.
   - For class 1 (high-risk loans), the recall is 0.94, meaning the model correctly identifies 94% of all high-risk loans.
# Summary
The machine learning model demonstrates strong performance in predicting the classification of loans as either healthy or high-risk. With an overall accuracy of 99%, the model is highly reliable in correctly identifying the loan status. The precision and recall for each class also show promising results:

Healthy loans (class 0): The model has perfect precision (1.00), meaning that when it predicts a loan is healthy, it is always correct. The recall of 0.99 indicates that the model captures 99% of the healthy loans.

High-risk loans (class 1): While the model's precision for high-risk loans is slightly lower at 0.86, it still performs well, ensuring that most predictions of high-risk loans are correct. The recall of 0.94 means the model successfully identifies 94% of all high-risk loans, which is excellent for minimizing missed predictions of risky loans.

# Recommendation
Given the model's high accuracy, excellent F1-scores, and strong recall across both classes, it provides a reliable tool for loan classification. The model is especially effective in identifying healthy loans with near-perfect precision, which ensures that there will be minimal false positives in that category. While the model's performance with high-risk loans is slightly less perfect, it still maintains a strong recall of 94%, meaning the risk of missing a high-risk loan is low.

For these reasons, I recommend adopting this model for use by the company, as it offers high reliability in classifying both healthy and high-risk loans, supporting accurate decision-making and reducing the risk of incorrect loan classifications. 
