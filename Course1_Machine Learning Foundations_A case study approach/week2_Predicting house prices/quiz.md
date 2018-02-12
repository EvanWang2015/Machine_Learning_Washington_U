# Regression： Predicting Houses Prices

### 1

Selection and summary statistics: We found the zip code with the highest average house price. What is the average house price of that zip code?

$75,000

$7,700,000

$540,088

> 2,160,607

'''
set_zipcode = set(sales['zipcode'])

for zipcode in set_zipcode:
    batch_sales_ave.append(sales[sales['zipcode'] == zipcode]['price'].mean())
# return max of a list
max(batch_sales_ave)

'''


### 2

Filtering data: What fraction of the houses have living space between 2000 sq.ft. and 4000 sq.ft.?

Between 0.2 and 0.29

Between 0.3 and 0.39

> Between 0.4 and 0.49

Between 0.5 and 0.59

Between 0.6 and 0.69


### 3

Building a regression model with several more features: What is the difference in RMSE between the model trained with my_features and the one trained with advanced_features?

> the RMSE of the model with advanced_features lower by less than $25,000