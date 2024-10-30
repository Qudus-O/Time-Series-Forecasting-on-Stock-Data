# Time Series Forecasting on the S&P 500 using RNN Model

In this Project, I will be working as a trader on the S&P 500 funds desk. We have been tasked with building a model to better forecast how this index will move based on its behaviors over the past several years. The better our forecast perform the more effectively and lucratively our desk will be able to trade these futures. A good way to practice data science and machine learning for “fun and profit”.

## About the Dataset
The dataset is from a yahoo finance via [Kaggle](https://www.kaggle.com/datasets/arashnic/time-series-forecasting-with-yahoo-stock-price) and it contains S&P 500 index prices from 2015 through 2020 with over 1800 entries.

## Data Exploration
Cleaned the data to prepare it for the model. Steps below;
+ split the data into training (60%), validation set (20%), and test sets (20%).
+ Scale data to be between 0 and 1.
+ Create time windows for each dataset.
+ Reshape the data into numpy arrays.

## Model Performance
I used R2_score as the evaluation metrics.
+ R2 Score on Training set: 0.99
+ R2 Score on Validation set: 0.94
+ R2 Score on Test set: 0.93
This shows that the model performance is good.
## Tools Used
+ Numpy 
+ Pandas
+ Matplotlib for Visualization
+ TensorFlow
+ Keras





