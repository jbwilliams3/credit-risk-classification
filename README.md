# credit-risk-classification
Overview of the Analysis:

The purpose of this analysis is to develop a machine learning model for credit risk assessment. Specifically, we aim to build a logistic regression model capable of accurately classifying loans into two categories: healthy loans (class "0") and high-risk loans (class "1"). To address the challenge of imbalanced data, we employ oversampling techniques. The analysis focuses on evaluating the model's performance in predicting both classes, with an emphasis on precision, recall, and overall accuracy.

Results:

    Accuracy Score: The logistic regression model, trained with oversampled data, achieves an impressive accuracy score of 0.99. This indicates that the model correctly predicts the majority of loan classifications.

    Precision Score:
        For healthy loans (class "0"), the precision score is 1.00, signifying near-perfect accuracy in identifying truly healthy loans.
        For high-risk loans (class "1"), the precision score is 0.85, indicating a strong ability to accurately identify high-risk loans.

    Recall Score:
        Both for healthy loans (class "0") and high-risk loans (class "1"), the recall scores are 0.99. This means that the model correctly identifies nearly all actual instances of both classes.

Summary:

The logistic regression model, trained with oversampled data, demonstrates exceptional performance in credit risk assessment:

    Accuracy: With an accuracy score of 0.99, the model excels in making accurate loan classifications.

    Precision: The model achieves a precision score of 1.00 for healthy loans and 0.85 for high-risk loans. It rarely misclassifies truly healthy loans and maintains a strong ability to identify high-risk loans accurately.

    Recall: Both classes exhibit high recall scores of 0.99, indicating that the model captures almost all actual instances of both healthy and high-risk loans.

Given these outstanding results, I recommend the deployment of this logistic regression model for credit risk assessment within the company. The model's ability to accurately identify high-risk loans is crucial for risk management, enabling the company to make informed lending decisions and reduce potential losses. Moreover, its high precision and recall scores for both classes ensure a balanced and reliable performance. This model offers a valuable tool to enhance credit risk evaluation and support prudent lending practices.