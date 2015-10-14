# Model and Cost Function

Housing prices example

- Based on the price and size we can draw a linear line with slope or fix a function

Supervised Learning:
- Given the "right anser" for each data in the data

Regression Problem
- Predict real-valued output

In supervised learning we have a training set (ie of different housing prices)

#### Notation

m = Number of training examples

x's = "input" variable/features

y's = "output" variable / "target" variable

(x,y) = a single training example

(x^i , y^i) = ith training example

### How a supervised learning algorithm wors

Training Set -> Learning Algorithm -> Hypothesis (h)

Hypothesis takes input (size of house) and tries to estimate output (price)

h maps from x -> y

'Why a hypothesis' - Was used in early days of machine learning.

**How do we represent h?**

h\_theta =  \theta\_0 + theta\_1

Predict that y is a linear function of x. We assume it is some straight line function.

'Why a linear function?' -- simple building block to start with.

This is called: Linear Regression with one variable.

Univariate linear regression (also called)


# Cost Function

We have training set and hypothesis (h\_0(x) = theta\_0 + theta\_1x

- thetas are the parameter values.

We have different choices

In linear regression we have a training set... we want to come up with values st the straight line we provide is accurate over data set... how do we come up with  this?

Idea: Choose theta1 theta0 so that h\_theta(x) is close to y for our training example (x,y)

minimize(thet0,theta1)

we want (h\_theta(x) - y)^2

sum from i =1 to m  (h\_theta(x^i) - y^i)^2   *   1/2m

placing 1/2 in front makes math easier

The expression within summation is h\_theta(x^i) = theta0 + theta1x^i


J(theta0, theta1) = 1/2m sum(from i = 1 to m){ h\_theta(x^i) - y^i) ^ 2

minimize J(theta0, theta1)

The squared error function works well for most problems.. The square error function is the most common 












































