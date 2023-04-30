---
title: "The Art of Fitting Lines: A Comprehensive Guide to Linear Regression and Gradient Descent"
datePublished: Sun Apr 30 2023 14:26:51 GMT+0000 (Coordinated Universal Time)
cuid: clh3i9avu000209k0fuz419fl
slug: the-art-of-fitting-lines-a-comprehensive-guide-to-linear-regression-and-gradient-descent
cover: https://cdn.hashnode.com/res/hashnode/image/stock/unsplash/jVZ_BKzDOJg/upload/54b7833ce96837182b68d913b947479c.jpeg
tags: ai, data-science, machine-learning, beginners

---

### I recently build my very own model using linear regression and gradient descent and I want to share my experience.

* So what is linear regression?
    
* and what is Gradient Descent?
    

As per my understanding the word ‘Linear’ is a straight line and the word ‘REGRESSSION’ is basically a math concept that is used to find patterns in data or what I like to call the “best-fit line”.The Majority of the data always has some kind of pattern.

In simple terms, linear regression is a method to find a line that best fits a set of data points. The goal is to find a line that passes as close to as many of the data points as possible for eg -:

if you were studying the relationship between height and weight in a group of people, you might find that as height increases, weight tends to increase as well.

‘Gradient descent ’ is a mathematical term used to measure how much something changes over a certain distance or period of time. for eg:

Let’s say you’re trying to climb a mountain. If the mountain is very steep, it might be hard to climb straight up. Instead, you might need to take a more gradual path that goes back and forth across the mountain. The gradient of the mountain is a measure of how steep it is. If the mountain has a high gradient, that means it gets steep very quickly. If the mountain has a low gradient, that means it gets steep more gradually. In math, gradients are often used to describe how things change over time or distance. For example, if you were graphing the temperature outside over the course of a day, you might use a gradient to describe how quickly the temperature is changing at different times. this is just a simple explanation of gradient descent.

## So how do we use the algorithm gradient descent in machine learning:

Gradient descent is used in Linear Regression to help the computer find the line that best fits the data.

## Here is how it works:

* First, we calculate how well the line fits the data. So this is done by first measuring the differences between the line’s prediction and the actual value in the data set. Then the computer or the algorithm adjusts the line to make it fit the data better by changing its slope and intercept.
    

represented by the equation:

## y = mx + b

where ‘SLOPE ’ is the “m” vertical distance divided by the horizontal distance between any two points on the line represented by the equation

m = rise over run or rise/run

and the ‘Y -INTERCEPT ’ is the “b” the value at which the regression line crosses the y-axis.

To completely understand this I recommend you to watch this video which clearly explains how to find the slope and the y-intercept

[https://youtu.be/lz8zVJxRFX8](https://youtu.be/lz8zVJxRFX8).

## What is the goal of gradient descent:

The goal of gradient descent is to minimize the cost function or the error between predicted and actual y. In order to do this, it requires two data points — a direction and a learning rate. These factors determine the partial derivative calculations of future iterations, allowing it to gradually arrive at a global minimum. (info: taken from IBM )

The cost function here is a measure of how well the model fits the training data. here it is used to evaluate the performance of the model by comparing the predicted output with the y value.

The Learning rate here is the speed at which the computer learns. When we want the computer to learn, we give it some examples like telling it that 2 + 2 = 4 or 4 + 4 = 8, then the computer tries to figure out the rules that connect the examples. so that it can learn the patterns and answer other questions like 3 + 3 = 6 ( ps- this is just a very simple explanation and I would recommend you to learn more from other sources .)

But the computer doesn’t get the rule right on the first try — it has to adjust its guess over and over again until it gets it right. This is where the learning rate comes in.

The learning rate is like the size of the steps that the computer takes when it adjusts its guess. If the learning rate is too big, the computer might overshoot and get the wrong answer. But if the learning rate is too small, the computer might take too long to learn.

PLEASE READ THIS FOR MORE DETAIL

[https://www.ibm.com/topics/gradient-descent](https://www.ibm.com/topics/gradient-descent).

Thank you so much for reading this :)

I hope this helps someone out there even though I cannot explain it in a better way.