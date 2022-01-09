# Neural_Network_Charity_Analysis
# Project Overview
The purpose of this analysis is to use the knowledge of machine learning and neural networks considering the features provided in the dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
# Deliverable 1: Preprocessing Data for a Neural Network Model
The EIN and NAME columns were dropped. The number of unique values for each column was determined. The density plot to determine the distribution of the column values was created. This density plot was being used to create a cutoff point to bin "rare" categorical variables together in a new column, Other, and then check if the binning was successful. The categorical variables using one-hot encoding were encoded and placed in a new DataFrame. Lastly, the one-hot encoding DataFrame with the original DataFrame were merged, and the originals were dropped.
![image](https://user-images.githubusercontent.com/89113627/148702738-19ec7296-c264-4b30-b205-62b4283db03d.png)

# Deliverable 2: Compile, Train, and Evaluate the Model
Knowledge of TensorFlow will be used to design a neural network or deep learning model in order to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. It is imperative to think about how many inputs there are before determining the number of neurons and layers in the model. Once the step is completed, one will then compile, train, and evaluate binary classification model to calculate the model’s loss and accuracy. Below is the performance metrics of this model:
![image](https://user-images.githubusercontent.com/89113627/148703609-b86f85a5-0597-4d80-a498-da4fa8c81475.png)

# Deliverable 3: Optimize the Model
Using knowledge of TensorFlow, optimize the model in order to achieve a target predictive accuracy higher than 75%. If one can't achieve an accuracy higher than 75%, one will need to make at least three attempts to do so. The performance metrics is shown below:
![image](https://user-images.githubusercontent.com/89113627/148703859-1d701dc3-82ca-4953-81a1-60d76a93bd98.png)

# Summary
The above model does not achieve set target performance of above 75%. However, it is recommended to use a different model to solve the classification problem.
