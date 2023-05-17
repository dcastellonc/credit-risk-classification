# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to evaluate the performance of a logistic regression model in predicting loan default risks. The analysis involved splitting the lending data into training and testing sets, fitting a logistic regression model using the training data, and evaluating its performance.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

  * Description of Model 1 Accuracy, Precision, and Recall scores.
    - Accuracy Score: 0.952
    - Precision Score: 
      - (0) 1.00
      - (1) 0.85
    - Recall Score: 
      - (0) 0.99
      - (1) 0.91

## Summary

The model has a strong performance in predicting loan default risks. We see an accuracy score of 95.2%, where the model classifies loans accurately more often than not. The precision score for label 0 (healthy loans) stands at 1.00, which means that the model doesn't usually misclassify loans as healthy when they are not. 

For label 1 (high-risk loans), the precision score of 0.85 indicates a moderate level of false positives. This means that some loans predicted as high-risk may actually be healthy.

The model achieves a score of 0.99 for label 0 on recall, meaning it correctly identifies the majority of actual healthy loans. On the other hand, the recall score for label 1 is 0.91, showing that the model captures around 91% of high-risk loans. This may suggest a good ability to detect high-risk loans, but there is a chance that some actual high-risk loans might be missed.

We know that the performance of Choosing between precision and recall depends on the specific problem. The model's high recall for label 1 would be perfect if the focus is on minimizing false negatives, because it makes sure that most high-risk loans are identified. However, if avoiding false positives is a priority, a model with a higher precision score for label 1 should be considered.
