## Problem Statement
Suppose you are the product manager of the factory and you have the test results for some microchips on two different tests. 
- From these two tests, you would like to determine whether the microchips should be accepted or rejected. 
- To help you make the decision, you have a dataset of test results on past microchips, from which you can build a regularized logistic regression model.

## Solution

#### Feature Mapping  
To demonstrate regularized logistic regression we will first fit the data better by creating more features from a single data point  
- we will map the features into all polynomial terms of $x_1$ and $x_2$ up to the sixth power
