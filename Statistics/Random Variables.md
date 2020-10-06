---
title: Random Variables
created: '2020-10-06T13:31:44.957Z'
modified: '2020-10-06T13:33:25.421Z'
---

# Random Variables

## What is a Random Variable ?

In probability and statistics, a random variable, a random quantity, aleaory variable or stochastic variable is described informally as a variable whose values depends on outcomes of a random phenomenon

A random variable possible values might represent the possible outcomes of a yet-to-be performed experiment. In other words, a random variable is defined as a variable whose possible values are outcomes of a random phenomenon. In specific terms, it is a function that maps the outcomes of an unpredictable process in numerical terms, often represented as a real number.

As it is subject to randomness, it takes different values

## Why Random Variables ?

Random Variables allows us to ask questions in mathematical way

If we flip 5 coins and want to answers questions like:

What is the probability of getting exactly 3 heads?
What is the probability of getting less than 4 heads?
What is the probability of getting more than 1 head?
Then our general way of writing would be:

P(Probability of getting exactly 3 heads when we flip a coin 5 times)
P(Probability of getting less than 4 heads when we flip a coin 5 times)
P(Probability of getting more than 1 head when we flip a coin 5 times)
But if we use random variables to represent above questions then we would write:

P(X=3)
P(X<4)
P(X>1)
As we can see above random variables makes our task much easier to quantify results of any random process and apply math and perform further computation.

Suppose we have a random process/experiment of flipping a coin. One of the two possible outcomes could be either head or a tail. Here, we use X to denote random variable, which represents the outcomes of this random process.

We can write:

X = 1, if the outcome is head

X = 0, if the outcome is tail

Here, the random variable X is mapping the outcomes of the random process (flipping a coin) to the numerical values (1 or 0).

![image](https://images.deepai.org/glossary-terms/random-variable-4279649.jpg)


### Summarizing in three points

*We have an experiment*

*We give values to each event*

*These set of values is a random variable*


## How Random Variable are different from traditional variables used in algebra ?

In algebra, we use variables like x, y, z. x can be number of students, y can be number of boys and z can be number of girls in a class.

So we can represent x as:

x = y + z

Traditional variables are just alphabetical characters used to denote an unknown or known number. Variables used in algebra cannot have more than a single value at a time.

Whereas, a random variable can hold a set of values.

If random variable X={0,1,2,3}, then X could be 0,1,2 or 3 randomly where each of them might have a different probability of occurring.

In summary,

***Random variable is function that maps a sample space(set of all possible outcomes of an experiment) to a set of discrete real values.***



