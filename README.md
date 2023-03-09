# HETEROGENEOUS-ENSEMBLE-Insurance
Here is a code snippet that demonstrates how to create a heterogeneous ensemble for an insurance dataset.
The goal is to predict the medical cost of a patient based on various features such as age, sex, BMI, etc. For this task, we will use three different models: a Random Forest, a Support Vector Machine (SVM), and a Gradient Boosting Regressor.

In this project, you first load the insurance dataset and split it into features and target. We then split the data into train and test sets and scale the features using StandardScaler. We define three different base models: a Random Forest, an SVM, and a Gradient Boosting Regressor. We then train each model on a different subset of the data and make predictions using each model. Finally, we combine the predictions using simple averaging and evaluate the performance of the ensemble and each individual model using the mean squared error (MSE).
