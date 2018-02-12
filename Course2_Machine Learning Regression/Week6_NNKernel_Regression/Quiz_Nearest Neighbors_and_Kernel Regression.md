# Nearest Neighbors & Kernal Regression

### 1

Which of the following datasets is best suited to nearest neighbor or kernel regression? Choose all that apply.


>A dataset with many features


A dataset with two features whose observations are evenly scattered throughout the input space


A dataset with many observations


>A dataset with only a few observations

### 2

Which of the following is the most significant advantage of k-nearest neighbor regression (for k>1) over 1-nearest neighbor regression?


Removes discontinuities in the fit


Better handles boundaries and regions with few observations


>Better copes with noise in the data

### 3

To obtain a fit with low variance using kernel regression, we should choose the kernel to have:


Small bandwidth λ


>Large bandwidth λ

### 4

In k-nearest neighbor regression and kernel regression, the complexity of functions that can be represented grows as we get more data.


>True


False

### 5

Parametric regression and 1-nearest neighbor regression will converge to the same solution as we collect more and more noiseless observations.


True


>False

### 6

Suppose you are creating a website to help shoppers pick houses. Every time a user of your website visits the webpage for a specific house, you want to compute a prediction of the house value. You are using 1-NN to make the prediction and have 100,000 houses in the dataset, with each house having 100 features. Computing the distance between two houses using all the features takes about 10 microseconds. Assuming the cost of all other operations involved (e.g., fetching data, etc.) is negligible, about how long will it take to make a prediction using the brute-force method described in the videos?


10 milliseconds


100 milliseconds


>1 second


10 seconds

### 7

For the housing website described in the previous question, you learn that you need predictions within 50 milliseconds. To accomplish this, you decide to reduce the number of features in your nearest neighbor comparisons. How many features can you use?


1 feature


>5 features


10 features


20 features


50 features