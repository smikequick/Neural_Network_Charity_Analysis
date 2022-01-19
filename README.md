# Neural Network Charity Analysis
 
<p align="center">
<img height='460' width="618" alt="THS table" src="https://images.theconversation.com/files/374303/original/file-20201210-18-elk4m.jpg?ixlib=rb-1.1.0&rect=0%2C22%2C7500%2C5591&q=45&auto=format&w=926&fit=clip">
</p>

## **Overview of Analysis**

### ***Purpose***

The purpose of this project is to create a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup.

*Technologies used: Python, Google Colab*

## **Results**

**Data Preprocessing**

* The target for this model is the column IS_SUCCESSFUL.
* The features for this model include: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.
* EIN and NAME are neither targets nor features and they have been removed.

**Compiling, Training, and Evaluating the Model**

* Total neurons used 80 and 30
* Total layers used is 2
* Activation functions used was ReLU for the hidden layers and Sigmoid was used for the output layer.
* Multiple attempts were made to improve the model (i.e. increase hidden layers, change the activation function to Tanh) however neither improved the performance.
* Unfortunately, the target model performance of 75% was not achieved.

## **Summary**
The model utilized did not meet the target accuracy of 75% which essentially means the model isn't wildly effective yet. Given the circumstances call for a binary classification situation, further analysis using SVM for leveraging a Random Forest Classifier could be worthwhile in evaluating against the current model.
