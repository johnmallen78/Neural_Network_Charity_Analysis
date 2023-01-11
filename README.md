# Neural_Network_Charity_Analysis

## Overview
We have been tasked with creating a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. We have received a data set from Alphabet Soup's business team with more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Analysis process
- Preprocess the data for a Neural Network Model
- Compile, Train and Evaluate the Model
- Optimize the Model
- Provide written analysis on the data and suggestion of possible other analysis that can be performed

## Data Preprocessing
We started by removing the columns EIN and Name that contain identification information from the input data. After that we identified that IS_SUCCESSFUL was the target for the neural network as it contained the binary data necessary on whether or not the charity donations were effective.

## Compile, Train and Evaluate
We started with a neural network with two hidden layers with 100 and 30 neurons respectively. We used the relu activation on each with sigmoid on the output neuron. The results of this were a loss of 0.55 and accuracy of 0.73 over 100 Epochs.

## Optimize
After the above analysis we attempted to optimize the model to see if we could reach a 75% accuracy model. We increased the number of nodes to 3 with the following neural setup:

- hidden_nodes_layer1 = 100
- hidden_nodes_layer2 = 80
- hidden_nodes_layer3 = 30

We also modified the activation methods to layer1 - relu, layer2 - sigmoid and layer3 - relu in attempt to generate better accuracy.

## Summary
We were unsuccessful in reaching the target of 75%, in fact the accuracy dropped slightly to 72% from the original 73%. We can surmise that the model is not outperforming based on these results. This being a binary classification we might suggest using a supervised machine learning model to better classify output and evaluate that data against the neural network outcome.

