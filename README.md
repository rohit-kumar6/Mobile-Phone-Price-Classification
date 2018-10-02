# Mobile-Phone-Price-Classification

It is a machine learning based project to solve the following problem
https://www.techgig.com/practice/question/ajErdEI2NlRTWmJ2K1lKTVMyZlljdz09

## Problem Description

Prabhat has started his own mobile company. He wants to give tough fight to big companies like Apple,Samsung etc.

He does not know how to estimate price of mobiles his company creates. In this competitive mobile phone market you cannot simply assume things. To solve this problem he collects sales data of mobile phones of various companies.

Prabhat wants to find out some relation between features of a mobile phone(eg:- RAM,Internal Memory etc) and its selling price. But he is not so good at Machine Learning. So he needs your help to solve this problem.  In this problem you do not have to predict actual price but a price range indicating how high the price is.

## Data Description

The data has been divided into 2 groups : • Training Set (train.csv) • Test Set (test.csv) The training set should be used to build your machine learning models. For the training set we provide the outcome( also known as target or class label) for each mobile sales data point. The test set should be used to see how well your model performs on unseen data. For the test set we do not provide the outcome(target variable) for each mobile sales data point. For each data point in the test set use the model you trained to predict price range. The training set contains 2000 data points. Each data point has 20 features and one target variable.

The test set contains 1000 data points. Each data point has 20 features.

| Feature name | Feature description | Type |
| ------------ | :-----------------: | ---: |
| id	       | ID |	Numeric |
| battery_power	|Total energy a battery can store in mAh  |	Numeric |
| blue |	Has bluetooth or not	| Boolean |
|clock_speed|	Speed at which microprocessor executes instructions	|Numeric|
|dual_sim|	Has dual sim support or not	|Boolean|
|fc	Front| Camera mega pixels|	Numeric|
|four_g	|Has 4G or not	|Boolean|
|int_memory|	Internal Memory in Gigabytes|	Numeric|
|m_dep|	Mobile Depth in cm|	Numeric|
|mobile_wt|	Weight of mobile phone	|Numeric|
|n_cores|	Number of cores of processor|	Numeric|
|pc|	Primary Camera mega pixels	|Numeric|
|px_height|	Pixel Resolution Height	|Numeric|
|px_width|	Pixel Resolution Width	|Numeric|
|ram	|Random Access Memory in Megabytes	|Numeric|
|sc_h	|Screen Height of mobile in cm	|Numeric|
|sc_w	|Screen Width of mobile in cm	|Numeric|
|talk_time|	Longest time that battery will last by a call	|Numeric|
|three_g|	Has 3G or not	|Boolean|
|touch_screen|	Has touch screen or not	|Boolean|
|wifi|	Has wifi or not	|Numeric|


## Outcome binary metrics:

| Model name |	Accuracy |
| ------------ | -----------------: |
Logistic regression	|95.4 %
KNN classifier 	|93.6 %	
Linear regression|	90.8 %


[Submit the solution and Check the Accuracy](https://www.techgig.com/practice/question/ajErdEI2NlRTWmJ2K1lKTVMyZlljdz09)
