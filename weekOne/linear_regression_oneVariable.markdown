#Linear Regression with One Variable

## Model Representation
	- Taking input variables and trying to map the output onto a continuous expected result function.

This is also known as "univariate linear regression"

	- Used when you want to predict a single output value from a single input value.


## The Hypothesis Function

General Form:

![alt tag](https://github.com/amsully/machine_learning.stanford_mooc/blob/master/weekOne/resources/Hypothesis_Function.jpg)

We are trying to create a function called h\_theta that is able to reliably map our input data (x) to our output data (y)

## Cost Function

Measure accuracy of hypothesis function by using a **cost function** 

- Takes an average of all results of the hypothesis with inputs from x's compared to the actual output y's


![alt tag](https://github.com/amsully/machine_learning.stanford_mooc/blob/master/weekOne/resources/Cost_Function.jpg)

This is 1/2 * x^hat where x^hat is the mean of the squares of h\_theta(x^(i))-y^(i) , or the difference between the predicted value and actual value.

Function is otherwised called "Squared Error Function" or "Mean Squared Error"

We use this to concretely measue the accuracy of our predictor function against the correct results we have so that we can predict new results we dont have

## Gradient Descent

We use GD to automatically improve our hypothesis function.

Imagine: We are not graphing x and y, but the guesses of our hypothesis function theta\_0 and theta\_1

We put theta\_0 on the x-axis and theta\_1 oon the z axis and the cost function on the vertical y axis

- Points on our graph will be cost function using our hypothesis with those specific theta parameters

- We know we have succeeded when our cost function is at the very bottom of the puts in our graph (ie when its value is a minimum)

- The way we do this is by taking the **derivative** of our cost function 
	- The slope of the tangent is the derivative at that point and will give us a direction to move towards

repeat until convergence:
![alt tag](https://github.com/amsully/machine_learning.stanford_mooc/blob/master/weekOne/resources/Gradient_Descent.jpg)

for j = 0 and j = 1

alpha is the learning rate

intuitively:

theta\_j := theta\_j - alpha[Slope of tangent aka derivative]

## Gradient Descent for Linear Regression

Parital Derivative in Gradient Descent for Two Variables [TO DO]: http://math.stackexchange.com/questions/70728/partial-derivative-in-gradient-descent-for-two-variables/189792#189792


repeat until convergence: {


![alt tag](https://github.com/amsully/machine_learning.stanford_mooc/blob/master/weekOne/resources/GradientDescent_LinearRegression.jpg)

}

When m is the size of the training set

theta\_0 is a constant that will be changing simultaneously with theta\_1 

x^i and y^i are values of the given training set




















