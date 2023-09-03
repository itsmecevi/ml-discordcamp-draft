__

# ID

**Which Model?**

* Logistic regression
* Decision Tree
* Neural network
* etc

**Data Split:**
* Data training (60%)
* Data validation (data testing 1: 20%)
* Data testing (data testing 2: 20%)

**MCP:**
* Multiple comparisons problem (MCP): just by chance one model can be lucky and obtain good predictions.
* The test set can help to avoid the MCP. Obtaining the best model is done with the training and validation datasets (hyperparameter tuning), while the test dataset is used for assuring that the proposed best model is the best.

1. Split datasets in training, validation, and test. E.g. 60%, 20% and 20% respectively
2. Train the models (data training)
3. Evaluate the models (data validation)
4. Select the best model (accuracy): Hyperparameter Tuning
5. Apply the best model to the test dataset (data testing)
6. Compare the performance metrics of validation dataset and test dataset

by: itsmecevi.github.io
