# Neural_Network_Charity_Analysis
# Project Overview
The purpose of this analysis is to use the knowledge of machine learning and neural networks considering the features provided in the dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
# Deliverable 1: Preprocessing Data for a Neural Network Model
The EIN and NAME columns were dropped. The number of unique values for each column was determinned. The ensity plot to determine the distribution of the column values was created. This density plot was being used to create a cutoff point to bin "rare" categorical variables together in a new column, Other, and then check if the binning was successful. The categorical variables using one-hot encoding were encoded and placed in a new DataFrame. Lastly, the one-hot encoding DataFrame with the original DataFrame were merged, and the originals were dropped.
![image](https://user-images.githubusercontent.com/89113627/148702738-19ec7296-c264-4b30-b205-62b4283db03d.png)

# Deliverable 2: Compile, Train, and Evaluate the Model
Knowledge of TensorFlow will be used to design a neural network or deep learning model in other to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. It is imperative to think about how many inputs there are before determining the number of neurons and layers in the model. Once the step is completed, one will then compile, train, and evaluate binary classification model to calculate the model’s loss and accuracy.
