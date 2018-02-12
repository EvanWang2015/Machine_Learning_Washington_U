# Implementing ridge regression via gradient descent

### 1

We run ridge regression to learn the weights of a simple model that has a single feature (sqft_living), once with l2_penalty=0.0 and once with l2_penalty=1e11.

What is the value of the coefficient for sqft_living that you learned with no regularization, rounded to 1 decimal place? Use American-style decimals (e.g. 30.5)


263.0

### 2

This question refers to the same model as the previous question.

What is the value of the coefficient for sqft_living that you learned with high regularization (l2_penalty=1e11)? Use American-style decimals (e.g. 30.5) and round your answer to 1 decimal place.


124.6


### 3

This question refers to the same model as the previous question.

Comparing the lines you fit with the with no regularization versus high regularization (l2_penalty=1e11), which one is steeper?


>Line fit with no regularization (l2_penalty=0)


Line fit with high regularization (l2_penalty=1e11)


### 4

This question refers to the same model as the previous question.

Using the weights learned with high regularization (l2_penalty=1e11), make predictions for the TEST data. In which of the following ranges does the TEST error (RSS) fall?


Between 8e13 and 2e14


Between 2e14 and 5e14


>Between 5e14 and 8e14


Between 8e14 and 1e15


Between 1e15 and 3e15


### 5

We run ridge regression to learn the weights of a model that has two features (sqft_living, sqft_living15), once with l2_penalty=0.0 and once with l2_penalty=1e11.

What is the value of the coefficient for sqft_living that you learned with no regularization, rounded to 1 decimal place? Use American-style decimals (e.g. 30.5).


245.1

### 6

This question refers to the same model as the previous question.

What is the value of the coefficient for sqft_living that you learned with high regularization (l2_penalty=1e11)? Use American-style decimals (e.g. 30.5) and round your answer to 1 decimal place.


91.5

### 7

This question refers to the same model as the previous question.

Using all zero weights, make predictions for the TEST data. In which of the following ranges does the TEST error (RSS) fall?


Between 8e13 and 2e14


Between 2e14 and 4e14


>Between 4e14 and 8e14


Between 8e14 and 1e15


Between 1e15 and 3e15


### 8

This question refers to the same model as the previous question.

Predict the price of the first house in the test set using the weights learned with no regularization. Do the same using the weights learned with high regularization. Which weights make better prediction for the first house in the test set?


The weights learned with no regularization (l2_penalty=0)


>The weights learned with high regularization (l2_penalty=1e11)