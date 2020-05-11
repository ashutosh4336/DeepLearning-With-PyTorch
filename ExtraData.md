### Types of Machine Learning

__Supervised Machine Learning__
	* In this type of Learning Machine learns under Guidance
	* Data is Labeled

__Unsupervised Machine Learning__
	* There is no Guidance for the Machine.
	* Data is not labeled
	* Machine has to find hidden Patterns to Predict Output.

__Reinforcement Machine Learning__
	* following Hit-and-Trail Concept  
	* Learns from Experience

Under Supervised Machine Learning there are 2 Classes of Problem
1. Classification
2. Regression


> __Classification__

* Classification is the task of Predecting a label
* In classification Problem data is calssified into one of two or more classes
* A classification Problem with two classes is called binary, more than two classes is called a Multi class classification
		
```
				--------> SPAM	
				|
-->   Mail------|
				|
				--------> Non-SPAM
```

> __Regression__

* Regression is the task of Predecting Continuous Quantity
* A regression problem with multiple input variable is called a multivariate regression probelm.
```
						Y   .----
						| ./	|
 -->					|./.. --| ================= Error (e)
	 Y Intercept (bo) ==|/========================= Slope(b1)
						|-------------------- x
```

Liner Regression is a method to predict depedent variable (Y) based on values of Indepedent varibales(X). It can be Used for the cases where we want to predict some continuous quantity.
	* Depedent Variable (Y) : The Response Varibale whose value needs to be Predicted.
	* Indepedent Varibale (X) : The predictor varibale used to predict the Response Varibale.

The following Equation is used to represent a linear regression model.

```
Y = bo + b1 x + e

		Y  = Depedent Variable
		bo = Y intercept
		b1 = Slope of the Line [Either -ve or +ve]
		e = Error

```
