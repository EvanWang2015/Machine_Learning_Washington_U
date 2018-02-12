# Predicting house price using k-nearest neighbors regression

### 1

From the section "Compute a single distance": we take our query house to be the first house of the test set.

What is the Euclidean distance between the query house and the 10th house of the training set? Enter your answer in American-style decimals (e.g. 0.044) rounded to 3 decimal places.


>0.058

### 2

From the section "Compute multiple distances": we take our query house to be the first house of the test set.

Among the first 10 training houses, which house is the closest to the query house? Enter the 0-based index of the closest house.


>8

### 3

From the section "Perform 1-nearest neighbor regression":

Take the query house to be third house of the test set (features_test[2]). What is the (0-based) index of the house in the training set that is closest to this query house?


>382

### 4

From the section "Perform 1-nearest neighbor regression":

Take the query house to be third house of the test set (features_test[2]). What is the predicted value of the query house based on 1-nearest neighbor regression? Enter your answer in simple decimals without comma separators (e.g. 300000), rounded to nearest whole number.


>249000


### 5

From the section "Perform k-nearest neighbor regression":

Take the query house to be third house of the test set (features_test[2]). Which of the following is NOT part of the 4 training houses closest to the query house? (Note that all indices are 0-based.)


training house with index 382


training house with index 1149


>training house with index 2818


training house with index 3142


training house with index 4087

### 6

From the section "Perform k-nearest neighbor regression":

Take the query house to be third house of the test set (features_test[2]). Predict the value of the query house by the simple averaging method. Enter your answer in simple decimals without comma separators (e.g. 241242), rounded to nearest whole number.


>413988

### 7

From the section "Perform k-nearest neighbor regression": Make prediction for the first 10 houses using k-nearest neighbors with k=10.

What is the predicted value of the house in this query set that has the lowest predicted value? Enter your answer in simple decimals without comma separators (e.g. 312000), rounded to nearest whole number.


> 350032

### 8

From the section "Perform k-nearest neighbor regression": We use a validation set to find the best k value, i.e. one that minimizes the RSS on validation set.

If we perform k-nearest neighbors with optimal k found above, what is the RSS on the TEST data? Choose the range that contains this value.


>Between 8e13 and 2e14


Between 2e14 and 5e14


Between 5e14 and 8e14


Between 8e14 and 1e15


Between 1e15 and 3e15