# Predicting-Customer-Churn-with-Artificial-Neural-Networks-A-Comprehensive-Analysis
1 Importing Libraries:In this exersise imported necessary libraries including NumPy, Pandas, and TensorFlow.

2 Data Preprocessing:
Imported a dataset (Churn_Modelling.csv).
Split the dataset into features (X) and target (y).
Encoded categorical data using Label Encoding for 'Gender' and One Hot Encoding for 'Geography'.
Split the dataset into training and test sets.
Applied feature scaling using StandardScaler. 

3 Building the Artificial Neural Network (ANN):
Initialized a sequential model.
Added input layer and two hidden layers with ReLU activation.
Added the output layer with sigmoid activation for binary classification.

4 Training the ANN:
Compiled the model specifying optimizer, loss function, and metrics.
Trained the model on the training set with specified batch size and epochs.

5 Making Predictions and Evaluating the Model:
Predicted whether a customer will leave the bank using the trained model for a specific set of input features.
Predicted test set results and evaluated the model using accuracy score and confusion matrix.

The provided code demonstrates building, training, and evaluating an ANN model for predicting customer churn based on various features. The accuracy score and confusion matrix provide insights into the model's performance on unseen data.




