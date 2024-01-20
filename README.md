# Insurance Premium Calculator

Data set obtained from: https://www.kaggle.com/datasets/simranjain17/insurance

## Overview
Insurance companies rely on actuarial methods to calculate premiums on their insurance policy offerings to customers. However, Machine Learning methods can be used to engineer a method to calculate premiums based on a given data set.
This sort of machine learning method would be very useful for companies in financial services industry who offer/ or have offered insurance policies and now require remediation/ compensation calculation work however don't have access to an actuarial team or no longer have access to an actuarial team (perhaps because the company sold the insurance business).

#### NOTE
Examining this dataset from Kaggle, one bit of data that is missing is the amount of cover that each customer has as well as what type of insurance policy each customer holds e.g. Life, TPD and/or Income Protection. If this machine learning method were to be used commercially, the business would ideally provide dataset containing this data as each customer's insurance needs are different and this is also a factor that influences premiums charged to the customer.
![image](https://github.com/TON369777/Insurance-Premium-Calculation/assets/156875448/1b9bc701-2647-46a8-8de7-43e215c20663)


## Machine Learning Model Chosen: Multiple Linear Regression

![image](https://github.com/TON369777/Insurance-Premium-Calculation/assets/156875448/d13922e7-4806-466f-a80c-2a5ce62684e4)

Other Models can be used to see if it would further optimise results. Workings show that this model is only ~74% accurate on test data.

## Co efficients determined
![image](https://github.com/TON369777/Insurance-Premium-Calculation/assets/156875448/56fbb4ea-527a-4721-9c7c-293ed40a7789)
Based on training data, The model has determined that smoking has a large influence on premiums.

## Calculating premiums on desired set of parameters

![image](https://github.com/TON369777/Insurance-Premium-Calculation/assets/156875448/4c96b0f1-6fff-475d-9d48-7f8f1e64ff0d)
![image](https://github.com/TON369777/Insurance-Premium-Calculation/assets/156875448/489c398f-b328-4eae-a114-92a9aec54e8c)
![image](https://github.com/TON369777/Insurance-Premium-Calculation/assets/156875448/bb987f37-78ef-4bc5-aac0-b665dfe7f326)
