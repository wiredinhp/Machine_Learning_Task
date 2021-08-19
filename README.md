# Machine Learning Task (Regression model)
## 1)Linear Regression
We have been given two loss functions to analyse the linear regression model and further compare the two loss functions.
Let's first look at the models using the two loss functions as their criterion and their various plots.
### a)L3 function (mean cubic(absolute) loss)
Firstly let's have a look at our solution i.e. the plot showing aur linear regression model.
![Alt Text](https://github.com/wiredinhp/Machine_Learning_Task/blob/main/plot_linear_a_1.png) <br>
We can see that the plot looks good and seems to fit the data. Now let's look at the plot of our loss function.
![Alt Text](https://github.com/wiredinhp/Machine_Learning_Task/blob/main/plot_linear_a_2.png)
### b)L1 function (mean absolute loss)
Again let's have a look at our solution i.e. the plot showing aur linear regression model.
![Alt Text](https://github.com/wiredinhp/Machine_Learning_Task/blob/main/plot_linear_b_1.png) <br>
We can see that the plot looks good and seems to fit the data. Now let's look at the plot of our loss function.
![Alt Text](https://github.com/wiredinhp/Machine_Learning_Task/blob/main/plot_linear_b_2.png) <br>
We have worked on two loss functions - mean cubic error, mean absolute error. In mean cubic error
if we have outliers in our data , our prediction is not quite correct 
because in a large set of data if a single large value exist it really does not affect the 
prediction but in case of mean cubic error the value is raised to power 3 so it disturbs the 
hypothesis. This issue is solved in mean absolute error because it would not drastically increase the 
value as in mean cubic error.
Secondly, in mean absolute error the gradient is constant so when we reach the minimum 
value there is a chance that we jump up from minimum value (so i had taken very small 
alpha and adjusted iteration in order to get as close as possible). This issue is solved
in mean cubic error because the gradient decreases as we get close to minimum so we can 
smoothly arrive at minimum value.<br>
Hence mean absolute is more robust(for outliers) and the cubic one is more stable than absolute one.
## 2)Polynomial Regression (Second order)
As in first part here too we have been given two loss functions to analyse the linear regression model and further compare
the two loss functions. Let's first look at the models using the two loss functions as their criterion and their various plots.
### a)L4 function (power 4)
Firstly let's have a look at our solution i.e. the plot showing aur linear regression model.
![Alt Text](https://github.com/wiredinhp/Machine_Learning_Task/blob/main/plot_linear_c.png) <br>
We can see that the plot looks good and seems to fit the data.
### b)L7 function (power 7)
Again let's have a look at our solution i.e. the plot showing aur linear regression model.
![Alt Text](https://github.com/wiredinhp/Machine_Learning_Task/blob/main/plot_linear_d.png) <br>
We can see that the plot looks good and seems to fit the data.<br>
We have worked with 4 degree and 7 degree loss functions . As seen in Linear regression,
here too - the 7 degree loss drastically increases the value in case of outliers
as compared to 4 degree Polynomial. On the contrary the 7 degree polynomial is more smooth
near the minima so we would get more close to minima as compared to 4 degree polynomial.<br>
Hence the 4 degree loss is more robust(for outliers) and 7 degree loss is more stable than 4 degree loss.
