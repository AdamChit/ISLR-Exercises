# ISLR-Exercises
This repo has my answers to the Exercises in introduction to statistical learning

# Chapter 2 - Statistical Learning 

## Question 1					 							
**For each of the parts (a) through (d), indicate whether we would generally expect the performance of a flexible statistical learning method to be better or worse than an inflexible method. Justify your answer.**
### a

**The sample size n is extremely large, and the number of predic- tors p is small.**

With a large sample size n and the number of predictors p is small then I would expect a flexible model to perform better mainly because with a large sample size we are less likely to overfit and a more flexible model will reduce over bias

### b

**The number of predictors p is extremely large, and the number of observations n is small.**

With a small sample size a flexible model is likely to overfit so there will be a larger inflation in variance compared to bias 

### c

**The relationship between the predictors and response is highly non-linear.** 

Flexible model would have better performance because inflexible model won’t be able to find the non linear effect.

### d

**The variance of the error terms, i.e. σ2 = Var(ε), is extremely high.**

An inflexible model will perform better because a flexible model will follow the noise too much which will cause the variance error to greatly increase, more than 

## Question 2

**Explain whether each scenario is a classification or regression prob- lem, and indicate whether we are most interested in inference or pre- diction. Finally, provide n and p.**



### a

**We collect a set of data on the top 500 firms in the US. For each firm we record profit, number of employees, industry and the CEO salary. We are interested in understanding which factors affect CEO salary.**

Type: Classification, Inference 

N: 500

P: profit, number of employees, industry and the CEO salary

### b

**We are considering launching a new product and wish to know whether it will be a success or a failure. We collect data on 20 similar products that were previously launched. For each prod- uct we have recorded whether it was a success or failure, the price charged for the product, marketing budget, competition price, and ten other variables.**

Type: Classification, Prediction 

N: 20

P: price charged for the product, marketing budget, competition price, and ten other variables

### c

**We are interested in predicting the % change in the US dollar in relation to the weekly changes in the world stock markets. Hence we collect weekly data for all of 2012. For each week we record the % change in the dollar, the % change in the US market, the % change in the British market, and the % change in the German market.**

Type: Regression, Prediction

N: 52

P:  % change in the dollar, the % change in the US market, the % change in the British market, and the % change in the German market.





## Question 3

**We now revisit the bias-variance decomposition.**

### a

**Provide a sketch of typical (squared) bias, variance, training error, test error, and Bayes (or irreducible) error curves, on a sin- gle plot, as we go from less flexible statistical learning methods towards more flexible approaches. The x-axis should represent the amount of flexibility in the method, and the y-axis should represent the values for each curve. There should be five curves. Make sure to label each one.**

### b 

**Explain why each of the five curves has the shape displayed in part (a).**

## Question 4

**You ing. will now think of some real-life applications for statistical learning**

### a

**Describe three real-life applications in which classification might be useful. Describe the response, as well as the predictors. Is the goal of each application inference or prediction? Explain your answer.**

### b 

**Describe three real-life applications in which regression might be useful. Describe the response, as well as the predictors. Is the goal of each application inference or prediction? Explain your answer.**

### c

**Describe three real-life applications in which cluster analysis might be useful.**

## Question 5

**What are the advantages and disadvantages of a very flexible (versus a less flexible) approach for regression or classification? Under what circumstances might a more flexible approach be preferred to a less flexible approach? When might a less flexible approach be preferred?**

## Question 6

**Describe the differences between a parametric and a non-parametric statistical learning approach. What are the advantages of a para- metric approach to regression or classification (as opposed to a non- parametric approach)? What are its disadvantages?**

## Question 7 

**The table below provides a training data set containing six observa- tions, three predictors, and one qualitative response variable.** 

| Obs.        | X_1           | X_2  | X_3    | Y | 
| ------------- |:-------------:| :-----:| :-----:|--:|
| 1     | 0 | 3 |   0     | Red  |
| 2     | 2 | 0 |   0     | Red  |
| 3     | 0 | 1 |   3     | Red  |
| 4     | 0 | 1 |   2     | Green  |
| 5     | -1 | 0 |   1     | Green  |
| 6     | 1 | 1 |   1     | Red  |

**Suppose we wish to use this data set to make a prediction for Y when X1 = X2 = X3 = 0 using K-nearest neighbors.** 

### a

**Compute the Euclidean distance between each observation and thetestpoint,X1 =X2 =X3 =0.**

### b

**What is our prediction with K = 1? Why?**

### c

**What is our prediction with K = 3? Why?**

### d 

**If the Bayes decision boundary in this problem is highly non- linear, then would we expect the best value for K to be large or small? Why?**



