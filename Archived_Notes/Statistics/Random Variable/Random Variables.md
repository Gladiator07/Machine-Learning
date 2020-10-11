
# Random Variables

## What is a Random Variable ?

In probability and statistics, a random variable, a random quantity, aleaory variable or stochastic variable is described informally as a variable whose values depends on outcomes of a random phenomenon

A random variable possible values might represent the possible outcomes of a yet-to-be performed experiment. In other words, a random variable is defined as a variable whose possible values are outcomes of a random phenomenon. In specific terms, it is a function that maps the outcomes of an unpredictable process in numerical terms, often represented as a real number.

As it is subject to randomness, it takes different values

## Why Random Variables ?

Random Variables allows us to ask questions in mathematical way

If we flip 5 coins and want to answers questions like:

- What is the probability of getting exactly 3 heads?
- What is the probability of getting less than 4 heads?
- What is the probability of getting more than 1 head?

Then our general way of writing would be:

- P(Probability of getting exactly 3 heads when we flip a coin 5 times)
- P(Probability of getting less than 4 heads when we flip a coin 5 times)
- P(Probability of getting more than 1 head when we flip a coin 5 times)

But if we use random variables to represent above questions then we would write:

- P(X=3)
- P(X<4)
- P(X>1)
  
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

We use capital letter for random variables to avoid confusion with traditional variables.

In summary,

***Random variable is function that maps a sample space(set of all possible outcomes of an experiment) to a set of discrete real values.***


Random variables can be either discrete or continuous.

If a variable can take countable number of distinct values then it’s a discrete random variable.

For example: In an experiment of tossing 2 coins, we need to find out the possible number of heads.

In this case, X is the random variable and the possible values taken by it is 0, 1 and 2 which is discrete.
Therefore X= {0, 1, 2}

A random variable is said to be continuous if it takes infinite number of values in an interval.

For example: Suppose the temperature in a city lies between 30⁰ and 45⁰ centigrade. The temperature can take any value in the interval 30⁰ to 45⁰. So the temperature can be either 30.13⁰ or 40.15⁰ or it may be in 30.13⁰ and 40.15⁰. When we say temperature is 38⁰, it means it lies somewhere between 37.5 and 38.5. So there is nothing exact or discrete observation in continuous random variable.


## Random Variables in Machine Learning

Random variables are an invaluable tool within applications of machine learning. As a neural network makes decisions using machine learning, it creates functions for understanding possible outcomes. These possible outcomes are often defined by random variables.

