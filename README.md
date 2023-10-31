# Divorce_Prediction
AIM
The aim of the project is to classify from the questions which couple is likely to divorce or happily married.

Dataset
The dataset used in this project is from the UCI machine learning repository, which originates from turkey. It is based on 54 questions been asked to 170 couples which are either divorce or happily married. The questions are graded on a 5 points scale from 0 to 4 where 0 is never ,1 is seldom,2 average, 3 frequently and 4 always.

Project Steps
The project follows these steps:
Step 1: Import all the necessary libraries and Load the Dataset.
Step 2: Carry out detailed statistical and exploratory data analysis
Step 3: Check for details of our class variable and confirm class imbalance. by plotting a graph to visually see the output
Step 4: we split our data set to input and target variable  then we run a random forest feature selection to select the  importance the machine is using to build the models(See code for details)
Step 6 Splitting the Data: The dataset was split using a 80% and 20% ratio for training and testing, respectively.
Step 7: train the model using the KNN classifier and the neural Network.

To evaluate our model, we using the classification Report and from both models the KNN has 0.97% accuracy while the neural network has about 99% Percent accuracy. Other evaluation metrics are precision,recall,F1 score,AUC-Score

Further analysis.
1.	We can try out other models to see if we will get better accuracy.
2.	We run hyper parameter tuning.
6. Training the Model and Selection of Hyperparameters: Four classifiers were initially used to train and make predictions. Due to size, only two were selected. Default parameters were initially used, followed by tuning hyperparameters to improve the accuracy of the models.

