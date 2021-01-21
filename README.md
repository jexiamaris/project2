# Texas Housing
This project used deferent Machine Learning models to predict home prices in Texas

## Data 
* This project used data from 2010 to 2020. The data included home prices, number of bedroom, average days in the market, and the Texas's regions. [Kaggle](https://www.kaggle.com/paultimothymooney/zillow-house-price-data?select=DaysOnZillow_City.csv)
* This project also used data 2010 to 2020 of 30 years fixed rate mortgages in Texas including the number of houses sold, the average price, and the interest rate. [ATM_Real_State_Center](https://www.recenter.tamu.edu/data/housing-activity/#!/activity/State/Texas)
  [Freddiemac](http://www.freddiemac.com/pmms/pmms30.html)

## Deep Learning Model 
For this model we used number of bedroom, average days in the market, and the Texas's regions as features and home price as target, which we later separated 70% for training data and 30% for testing data. To create the model, we used three layers with the activation function RELU and Linear for the output layer.
Then, we trained the model using a batch size of 50 and epochs of 5000. We combined and changed all this functions, layers, batch size and epochs looking for the best model. However, the model Loss is 759630336.0 which means the model behaved very poorly with the training data, therefore we can not thrust this model with the tasting data. Also the accuracy of the model is 0.0 which measures the predictions of the model compare to the real data and in this case we can not trust the model's predictions. 
Although we can not trust this model's predictions, we can notice in this plot that the predictions got some prices right.
![predictions](./Images/predictions-deeplearning.png)
This outcome means that the feature we used to create the model are not enough to make a good prediction of home prices. Therefore, for future analysis is important to consider more correlated features looking for a more accurate model to predict home prices.

## LSTM Model

## 


