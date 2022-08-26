## Problem Statement
Suppose you are the product manager of the factory and you have the test results for some microchips on two different tests. 
- From these two tests, you would like to determine whether the microchips should be accepted or rejected. 
- To help you make the decision, you have a dataset of test results on past microchips, from which you can build a regularized logistic regression model.

## Solution

 
To demonstrate regularized logistic regression we will first fit the data better by creating more features from a single data point  
- We will map the features into all polynomial terms of $x_1$ and $x_2$ up to the sixth power 


For regularized logistic regression, the cost function is of the form
$$  J(\mathbf{w},b) = \frac{1}{m}\sum_{i=0}^{m-1} \left[ loss(f_{\mathbf{w},b}(\mathbf{x}^{(i)}), y^{(i)}) \right]$$

For regularized logistic regression, the cost function is of the form 

$$  J(\mathbf{w},b) = \frac{1}{m}\sum_{i=0}^{m-1} \left[ loss(f_{\mathbf{w},b}(\mathbf{x}^{(i)}), y^{(i)}) \right]+$$
