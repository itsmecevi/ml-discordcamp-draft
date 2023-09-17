__

# ID

**Cross Validation:** Cross-validation is a statistical technique used in machine learning and statistics to assess the performance and generalization ability of a predictive model. Its primary purpose is to estimate how well a model will perform on unseen data, which is crucial for understanding its reliability and suitability for real-world applications. Cross-validation is especially important when you have a limited amount of data or when you want to avoid overfitting.

**Accuracy:** Accuracy is a common evaluation metric used in machine learning to measure the performance of a classification model. It represents the proportion of correctly classified instances (or samples) out of the total number of instances in the dataset. In other words, accuracy tells you how often the model's predictions are correct.

**Confusion Matrix:** A confusion matrix is a table or matrix that is commonly used in machine learning and classification tasks to evaluate the performance of a classification model. It provides a summary of the predictions made by the model compared to the actual class labels in the dataset. The confusion matrix is particularly useful for understanding the types of errors a model is making and assessing its overall performance.

|                   | Actual Positive | Actual Negative |
|-------------------|-----------------|-----------------|
| Predicted Positive |       TP        |       FP        |
| Predicted Negative |       FN        |       TN        |


**Precision:** A Precision is an evaluation metric used to assess the quality of a classification model's positive predictions, particularly in binary classification problems. Precision measures the proportion of true positive predictions (correctly predicted positive instances) out of all instances that the model predicted as positive (true positives plus false positives). In other words, it quantifies how well the model avoids making false positive errors.

> Precision:= TP/(TP+FP)

**Recall (Sensitivity):** It measures the proportion of true positive predictions (correctly predicted positive instances) out of all actual positive instances in the dataset.

> Recall: TP/(TP+FN)

**F1-Score:** the F1-score is a metric used to assess the balance between precision and recall, especially in binary classification problems. It provides a single numerical value that combines both precision and recall into a single measure of a model's overall performance.

> F1-score=2 x [(PrecisionxRecall)/(Precision+Recall)]

**Support:** It refers to the number of instances or samples in a dataset that belong to a specific class. It is the count of actual occurrences of each class in the dataset.


**ROC Curva:** The Receiver Operating Characteristic (ROC) curve is a graphical representation commonly used to assess the performance of binary classification models. It helps visualize the trade-off between the true positive rate (sensitivity) and the false positive rate (1 - specificity) across different decision thresholds for a given model.

**[7. Evaluation (Classification): Customer Churn Prediction Project](https://colab.research.google.com/drive/1Z773XC_nY0OvLsKBjqOBXyORRlJLULtb?usp=sharing)**

by: itsmecevi.github.io

