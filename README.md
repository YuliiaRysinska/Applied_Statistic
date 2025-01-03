# Applied_Statistic
#### This repository includes 4 tasks and projects. All knowledge and work on this material was achieved by studying Applied_Statistic at ATU, lecturer Ian McLoughlin.
### Purpose: 
#### - Demonstrate ability in the following.

#### - Describe the stochastic nature of real-world measurements.

#### - Create source documentation to programmatically perform a statistical test.

#### - Select an appropriate statistical test to investigate a claim.

#### - Perform a statistical test on a data set.

# Task 1: Permutations and Combinations
#### Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six have tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first. Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells. Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error. Would you accept two errors? Explain.

# Task 2: NumPy's Normal Distribution
#### In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with a mean 10.0 and a standard deviation 3.0. Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output. Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.

# Task 3: t-Test Calculation
#### Consider the following dataset containing resting heart rates for patients before and after embarking on a two-week exercise program.

#### Patient ID	0	1	2	3	4	5	6	7	8	9
#### Before	63	68	70	64	74	67	70	57	66	65
#### After	64	64	68	64	73	70	72	54	61	63

#### Calculate the t-statistic based on this data set, using Python. Compare it to the value given by Scipy.stats. Explain your work and list any sources used.

# Task 4: ANOVA
#### In this test we will estimate the probability of committing a type II error in specific circumstances. To begin, create a variable called no_type_ii and set it to 0. Now use a loop to perform the following test 10,000 times. Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and the third a mean of 5.1. Perform one-way ANOVA on the three samples and add 1 to no_type_ii whenever a type II error occurs. Summarize and explain your results.

# ----------------------------------------------------------------

# Project
#### This project analyzes the PlantGrowth R dataset. You can find a short description of it on Vicent Arel-Bundock's R datasets page. The dataset contains two main variables, a treatment group and the weight of plants within those groups. The task is to perform t-tests and ANOVA on this dataset while describing the dataset and explanations. 
#### Steps:
#### 1) Downloading and saving the dataset to a repository.

#### 2) Describing the data set in a  notebook.

#### 3) Describing what a t-test is, how it works, and what the assumptions are.

#### 4) Performing a t-test to determine whether there is a significant difference between the two treatment groups trt1 and trt2.

#### 5) Performing ANOVA to determine whether there is a significant difference between the three treatment groups ctrl, trt1, and trt2.

#### 6) Explain why applying ANOVA rather than several t-tests is more appropriate when analyzing more than two groups.

### References:
#### Plant Growth: https://vincentarelbundock.github.io/Rdatasets/doc/datasets/PlantGrowth.html
#### Vicent Arel-Bund ock's R datasets page: https://vincentarelbundock.github.io/Rdatasets
#### Ian McLoughlin: https://github.com/ianmcloughlin/2425_applied_statistics/tree/main
#### PEP8: https://peps.python.org/pep-0008
#### Permutations and Combinations: https://betterexplained.com/articles/easy-permutations-and-combinations
#### Numpy's Normal Distribution: https://numpy.org/doc/2.0/reference/random/generated/numpy.random.normal.html
#### T-Test Calculation: https://datatab.net/tutorial/t-test
#### ANOVA: https://www.spotfire.com/glossary/what-is-analysis-of-variance-anova
#### AI: https://chatgpt.com
