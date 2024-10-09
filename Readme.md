# Assignment 47
### Machine Learning
### Perceptron 2 (Perception Neuron)


# 1 . Surgical  🏨 🩺 

+ In first problem I've done a classification on surgical database with perceptron.
perceptron algorithm is used for both classification and regression problems.
when we want to use it for classification, we must use an activation function to map our output to numbers that relates to our classes.

+ There are different activation function that we can use them in different situation for example: logestic(sigmoid),relu,step,tanh,...


+ then I calculate and plot confusion matric.

## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Surgical.ipynb file in jupyter notebook
```


## Results
## Activation Function = Sigmoid


Model Accuracy with Sigmoid
<img src="Output\Accuracy_Sigmoid.png" width="550">

Model Loss with Sigmoid
<img src="Output\Loss_Sigmoid.png" width="550">



Confusion Matric with Sigmoid
<img src="Output\Matric_Sigmoid.png" width="550">

## Activation Function = relu

Model Accuracy with relu
<img src="Output\Accuracy_relu.png" width="550">



Model Loss with relu

<img src="Output\Loss_relu.png" width="550">



Confusion Matric with relu
<img src="Output\Matric_relu.png" width="550">



## Activation Function = tanh

Model Accuracy with tanh
<img src="Output\Accuracy_tanh.png" width="550">



Model Loss with tanh

<img src="Output\Loss_tanh.png" width="550">



Confusion Matric with tanh
<img src="Output\Matric_tanh.png" width="550">


## Activation Function = unitstep

Model Accuracy with unitstep
<img src="Output\Accuracy_unitstep.png" width="550">



Model Loss with unitstep

<img src="Output\Loss_unitstep.png" width="550">



Confusion Matric with unitstep
<img src="Output\Matric_unitstep.png" width="550">

## Activation Function = Sign

Model Accuracy with Sign
<img src="Output\Accuracy_Sign.png" width="550">



Model Loss with Sign

<img src="Output\Loss_Sign.png" width="550">



Confusion Matric with Sign
<img src="Output\Matric_Sign.png" width="550">

## Activation Function = piece-wise-linear

Model Accuracy with piece-wise-linear




Model Loss with piece-wise-linear





Confusion Matric with piece-wise-linear

-----------------------------------------

# 2.Weather Prediction ⛅

+ weather dataset is the second dataset that I used it to test my perceptron algorithm.

+ At first I add another column to dataset for days. In fact I use 'Formatted Date' column to calculate the day number of each rows in a year, for example I use 12
for 2006-01-12 because this date is equal to 12th days in year.
+ then I calculate the mean temperature of each days in each years. and then I plot the temperature by day number for all years in dataset.

+ then I used another perceptron class to solve these regression problem. In regression problem we don't need activation function and we cant calculate accuracy.

+ So I use evaluate function to calculate loss and then I write a predict function that could predict temperature with day number.
for example you give 200 to it as input and it return the temperature of 200th day of year.

+ Finally I plot wieghts and biases and losses for training steps iterations.

## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Weather.ipynb file in jupyter notebook
```


### Results Table


##### Table For Date Temp Day of Year
<img src="Output\Data_Temperature.png" width="550">

##### Model Accuracies and Losses
<img src="Output\Accuracies_Loss.png" width="550">

##### Fitted Line
<img src="Output\Data_Temperature_Predict.png" width="550">


## I Saved Bias In [Bias](./Output\weight_bias.npy) And Weight In [Weight](./Output\weight_weights.npy)

-----------------------------------------
