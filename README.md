# Churn Modeling using Neural Networks and Hyperparameter Tuning (TensorFlow and Keras)

### Introduction
Business problem: A bank has a problem with customer turn-over rates.

Dataset: We have a log of 10,000 customers with their information such as credit score, gender, age, balance, and a yes/no if they exited the bank or not.

Solution: Utilize Neural Networks and Hyperparameter Tuning methods to develop a churn rate modeler which will predict whether a customer will leave the bank or not.

### Steps
* Data Visualization
* Data Preprocessing
* Developing the Neural Network
* Making Predictions and Evaluating the Model
* Test Neural Network Model
* Evaluating and Tuning the Neural Network

### Conclusion
Our original model scored a 84.15%. With hyper parameter tuning, the average was increased by a percent, up to 85.11%.
Possible improvements could be increasing the batch size to 64 and increasing the epoch to 1000 to see if there could be better accuracy rates. However, there would be a need of a GPU for this application. Just this notebook alone took 10 hours to run on an i5-6400 CPU.
