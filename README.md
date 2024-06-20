# credit-risk-classification


Overview of the Analysis

Explain the purpose of the analysis. 

The purpose of this analysis is to create and evaluate the accuracy of a data model that predicts the credit worthiness of potential borrowers from lending services

Results

* Class 0 Performance:
    * Precision and Recall: Both are extremely high (close to 1.00), indicating that the model is almost perfect in predicting class 0.
    * F1-Score: The F1-score is also 1.00, confirming the model's excellent performance for class 0.

* Class 1 Performance:
    * Precision (0.85): The model's ability to identify positive instances of class 1 is good but not perfect.
    * Recall (0.91): The model correctly identifies 91% of the actual class 1 instances, which is quite strong.
    * F1-Score (0.88): This value suggests a good balance between precision and recall.
    
    * Overall Model Performance:
        * Accuracy (0.99): The model performs exceptionally well overall, correctly classifying 99% of the instances.
    
Summary


The model performs well as per the accuracy score of 99%. The number of low-risk loans outweighs the number of high-risk loans indicating that the model would predict loan status's as healthy better than being able to predict loan status's as non-healthy. According to the classification report, the model predicted healthy loans [0] 100% of the time and predicted non-healthy loans [1] 85% of the time.

