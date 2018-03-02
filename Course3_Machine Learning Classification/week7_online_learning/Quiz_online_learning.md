# Hudge Datasets & Online Learning


### 1

(True/False) Stochastic gradient ascent often requires fewer passes over the dataset than batch gradient ascent to achieve a similar log likelihood.


>True


False

### 2

(True/False) Choosing a large batch size results in less noisy gradients


>True


False

### 3

(True/False) The set of coefficients obtained at the last iteration represents the best coefficients found so far.


True


>False

### 4

Suppose you obtained the plot of log likelihood below after running stochastic gradient ascent.

![alt text]( https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/VyRs8uBtEeWBDQ73-3lhaw_70d1c456f3deba4ffa876e53e041cf7a_Capture.PNG?expiry=1519776000000&hmac=hui2NyubyCpuyj6RYWl5SGrxpi0oRcUN5ZAcr04PXto)


Which of the following actions would help the most to improve the rate of convergence?


Increase step size


>Decrease step size


Decrease batch size

### 5

Suppose you obtained the plot of log likelihood below after running stochastic gradient ascent.

![alt text]( https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Ym5JpOBtEeWBDQ73-3lhaw_8f2bb6e530dc2b481646181bf6e72a80_Capture2.PNG?expiry=1519776000000&hmac=gfghPZ8MZxG3B9Vtxxkqq_mADABaUtyY_s7F7PzPrVw)

Which of the following actions would help to improve the rate of convergence?


Increase batch size


>Increase step size


Decrease step size

### 6

Suppose it takes about 1 milliseconds to compute a gradient for a single example. You run an online advertising company and would like to do online learning via mini-batch stochastic gradient ascent. If you aim to update the coefficients once every 5 minutes, how many examples can you cover in each update? Overhead and other operations take up 2 minutes, so you only have 3 minutes for the coefficient update.


180000

### 7

In search for an optimal step size, you experiment with multiple step sizes and obtain the following convergence plot.

![alt text]( https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/bS2ZaOBtEeWufRJaRfO1AQ_8d67c76c9a6715f27ebc78fb8df13c0a_Capture3.PNG?expiry=1519776000000&hmac=VUGOTbpzvanPSuQGBeJWoXWF67QI29dYe_QF8PQJTNA)


Which line corresponds to the best step size?


>(1)


(2)


(3)


(4)


(5)

###8 

Suppose you run stochastic gradient ascent with two different batch sizes. Which of the two lines below corresponds to the smaller batch size (assuming both use the same step size)?

![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/oj-RfOBtEeWOVQ68c1xy2w_6f018b2d10620f6857e5580f40c7eeb5_Capture4.PNG?expiry=1519776000000&hmac=6h4ZRv7bzKa3x8VqbLM-pXXd6NqKPiBRIpeLu8qeYhM）


>(1)


(2)

### 9

Which of the following is NOT a benefit of stochastic gradient ascent over batch gradient ascent? Choose all that apply.


Each coefficient step is very fast.


>Log likelihood of data improves monotonically.


Stochastic gradient ascent can be used for online learning.


Stochastic gradient ascent can achieve higher likelihood than batch gradient ascent for the same amount of running time.


>Stochastic gradient ascent is highly robust with respect to parameter choices.

### 10

Suppose we run the stochastic gradient ascent algorithm described in the lecture with batch size of 100. To make 10 passes over a dataset consisting of 15400 examples, how many iterations does it need to run?

1540