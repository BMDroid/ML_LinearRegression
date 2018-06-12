# ML_LinearRegression
Implement the Linear Regression in Matlab and predict the profit of the bussiness related to the population of the city.

### 1. Be familiar with the data

The data is in the ex1data1.txt and the first coclum is the population of a city and the second column is the profit of the that city. And the negatve value of the profit suggests a loss in that city.

### 2. Plot the data

By plotting the data, we can understand the data better. We can see the profit will be increased with the increasing of the population. So we can make educated guess that our data can be processed by the linear progression.

<p align="center">  <img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/data.png" width="70%">
</p>                                                                                                
<br/>

### 3. Implement the Gradient Descent

Our objective is to minimize the cost function of the linear regression:

<img><p align="center">  <img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/J.png" width="45%">
</p>                                                                                                
<br/>

and our hypothesis is:

<img><p align="center">  <img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/h_theta.png" width="45%">
</p>                                                                                                
<br/>

and using gradient descent:

<img><p align="center">  <img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/gradient.png" width="45%">
</p>                                                                                                
<br/>

### 4. The result

<img><p align="center">  <img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/linear_regression.png" width="70%">
</p>                                                                                                
<br/>

### 5. Visualizing the cost function

By visualizing the cost function during gradient descent, we can check whether our cost function is decreasing and move to the the global optima while doing the iteration. 

We can use the visualizing to adjust our learning rate and debug.

  <img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/cost_func.png" width="60%" />

*This is the contour of the cost function*<img src="https://github.com/BMDroid/ML_LinearRegression/blob/master/figs/contour.png" width="60%" />

### 6. Linear regression with multiple variables

Linear regression with multiple variables is just like Linear regression with single variables. But we should do some data preprocessing at first. 

We should for the mean normalization on the dataset to eliminate the effects of different scale features.

To accomplish the mean normalization, we computer the mean and variance of each features and then deduct the mean from each features and divided by its standard variance.

Then we could get the dataset for later linear regression. 

