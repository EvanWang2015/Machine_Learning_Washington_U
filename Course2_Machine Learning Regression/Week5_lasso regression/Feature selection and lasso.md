# Feature Selection and Lasso

### 1

The best fit model of size 5 (i.e., with 5 features) always contains the set of features from best fit model of size 4.


True


>False


### 2

Given 20 potential features, how many models do you have to evaluate in the all subsets algorithm?


>1048576


### 3

Given 20 potential features, how many models do you have to evaluate if you are running the forward stepwise greedy algorithm? Assume you run the algorithm all the way to the full feature set.


>210

### 4

Which of the plots could correspond to a lasso coefficient path? Select ALL that apply.

Hint: notice λ=∞ in the bottom right of the plots. How should coefficients behave eventually as λ goes to infinity?

![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/N5wvCpbOEeWZJxK6sR1SHQ_eb16c320cae86ffe1199a27505e042b4_Untitled-2.png?expiry=1517788800000&hmac=MDhJHAau4ecPmPPNnqSAX9LsPScUz-Pjz5WcFyaG9IA)

![alt text](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/gTyaW5bOEeWZJxK6sR1SHQ_1366dbe76f0fb3d80c9953b325e5514e_Untitled-3.png?expiry=1517788800000&hmac=m9txG0RkAOV0Yolmul9edoenbdK6C50g_CrGH2-uTqs)



### 5

Which of the following statements about coordinate descent is true? (Select all that apply.)


>A small enough step size should be chosen to guarantee convergence.


To test the convergence of coordinate descent, look at the size of the maximum step you take as you cycle through coordinates.


Coordinate descent cannot be used to optimize the ordinary least squares objective.


Coordinate descent is always less efficient than gradient descent, but is often easier to implement.


### 6

Using normalized features, the ordinary least squares coordinate descent update for feature j has the form (with ρj defined as in the videos):


>w^j=ρj

w^j=(ρj)2

w^j=ρj−λ

w^j=ρj/2−λ

### 7

Using normalized features, the ridge regression coordinate descent update for feature j has the form (with ρj defined as in the videos):


w^j=ρj−λ

w^j=ρj/2−λ

>w^j=ρj/(λ+1)

w^j=ρj