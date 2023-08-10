# credit-risk-classification

We create a logistic regression, whereby the loan status is equal to 0(healthy-loan) and 1(risky_loan). We output of the logistic goes as followed.

                precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.89      0.88       625

    accuracy                           0.99     19384
   macro avg       0.94      0.94      0.94     19384
weighted avg       0.99      0.99      0.99     19384

The model has a high overall accuracy of 99% thereby this model did great. Loan Status 0 has a 100% precision, recall, and F1-score. This model coorectly identifies all instances of loan status 0. Loan status 1 has slightly lower precision (87%), recall (89%), and F1-score (88%). The model is generally good at identifying loan status 1; there are some false positives and false negatives. The macro and weighted averages of precision, recall, and F1-score are at 94%, indicating a good overall performance.

We perform another logistic execept this time we use resampled training data. The output goes as followed.

               precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      1.00      0.93       625

    accuracy                           1.00     19384
   macro avg       0.94      1.00      0.96     19384
weighted avg       1.00      1.00      1.00     19384

The model has a high overall accuracy of 100% thereby this model did amazing. Loan Status 0 has a 100% precision, recall, and F1-score. This model correctly identifies all instances of loan status 0. Loan status 1 has slightly lower precision (87%), recall (89%), and F1-score (93%) compared to Loan status 0. This model is nominally better at identifying loan status 1 than the previous model; there are some false positives and false negatives. The macro and weighted averages of precision, recall, and F1-score are at 94%, indicating a good overall performance and is also equal to the previous model.
