# Neural_Network_Charity_Analysis

## Overview of Project
 
#### *To create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.*

Working with Alphabet Soup’s business team, and a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

- Using Pandas and the Scikit-Learn’s StandardScaler(), preprocess the dataset in order to compile, train, and evaluate the neural network model.

- Then using TensorFlow, design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset.

- Lastly compile, train, and evaluate your binary classification model again and try and optimize the accuracy (calculate the model’s loss and accuracy, for both.)
 
![mobile](https://github.com/Atomickilroy/Neural_Network_Charity_Analysis/blob/main/png/Screenshot%202022-09-27%20001941.png))

 
## Purpose
 
**The purpose of this project was to start learning tools that work hand and hand with Deep Learning and Neural Networks:**
 
  - Compare the differences between the traditional machine learning classification and regression models and the neural network models.
  - Describe the perceptron model and its components.
  - Implement neural network models using TensorFlow.
  - Explain how different neural network structures change algorithm performance.
  - Preprocess and construct datasets for neural network models.
  - Compare the differences between neural network models and deep neural networks.
  - Implement deep neural network models using TensorFlow.
  - Save trained TensorFlow models for later use.
 
## Results: 

### Data Preprocessing

This is a critical step for this model. Although this model can technically take in the raw data, it could effect the accuracy score or the run time. So its best to take the time to consider what data is going to be needed and drop the rest.

![mobile](https://github.com/Atomickilroy/Neural_Network_Charity_Analysis/blob/main/png/Screenshot%202022-09-27%20001237.png)



### Compiling, Training, and Evaluating the Model
--- 
![mobile](https://github.com/Atomickilroy/Neural_Network_Charity_Analysis/blob/main/png/Train.png) 

#### Were you able to achieve the target model performance?
Initially I was able to achieve a higher score but due to time constraints I was unable to achive the 75% goal. I think I would add like to add in a 4th node and try and change the activation function to tahn. 

#### Before 
![mobile](https://github.com/Atomickilroy/Neural_Network_Charity_Analysis/blob/main/png/Screenshot%202022-09-26%20235709.png)

####After 
![mobile](https://github.com/Atomickilroy/Neural_Network_Charity_Analysis/blob/main/png/last.png)


#### What steps did you take to try and increase model performance?  
- Import dependencies.
- Import the input dataset.
- Generate categorical variable list.
- Create a OneHotEncoder instance.
- Fit and transform the OneHotEncoder.
- Add the encoded variable names to the DataFrame.
- Merge one-hot encoded features and drop the originals.
- Split the preprocessed data into features and target arrays.
- Split the preprocessed data into training and testing dataset.
- Create a StandardScaler instance.
- Fit the StandardScaler.
- Scale the data.
- Define the model.
- Add first and second hidden layers.
- Add the output layer.
- Check the structure of the model.
- Define the model - deep neural net
- First hidden layer
- Second hidden layer
- Third Hidden layer
- Output layer
-Restore the model weights
-Evaluate the model using the test data

 
 
 
 
