# Maximum Likelihood Estimation of Ordered Statistics

Python code that calculates the MLEOS (Maximum Likelihood Estimation of Ordered Statistics)


## What is Order Statistic and why we're using it?

I will first address the 'why'. Imagine you have a machine that is about to generate $n = 50$ increasing datapoints, that is, for any $i \in [0,n-1]$  we'll have $x_i < x_{i+1}$. Now, say given the first $k$ data points, you're interested to estimate the distribution parameters of the data points. How can we acheive this? We cannot simply plug our k data points in a Maximum Likelihood estimation and derive the parameters. Why?? Because our $k$ data points are BIASED sample of the $n$ data points, in other words, they were not uniformly sampled. They are rather the $k$ smallest values of the $n$ data points.

## What is Orders Statistic?

In statistics, the $k^th$ order statistic of a statistical sample is equal to its $k^th$-smallest value.








