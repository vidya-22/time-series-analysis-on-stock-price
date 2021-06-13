# time-series-analysis-on-stock-price
This project uses machine learning to analyze time series data of stock
Time Series Analysis allows us to analyze data which is generated  over a period of time and has sequential interdependencies between  the observations. Time Series Analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data.The aim of this project is to predict the adjusted  close stock price of Bank of America. The adjusted closing price  shows the stock's value after posting a dividend. There are various  time series analysis models. The statistical ones include ​

• AR- Autoregression Model  ​

• MA- Moving Average Model  ​

• ARMA- Autoregression Moving Average Model​

Apart from statistical models there are various Machine Learning  Models which serve this purpose. A few of those examples are listed  below:  ​

• Decision Tree Regression Model  ​

• Random Forest Regression Model  ​

• Gradient Boosted Regression Model  ​

The most prominent technique in dealing with time series analysis  involves the use of Machine Learning. The advantage of forecasting  the stock price is it helps you to invest wisely and aids in making  better profits.​

===============================================================================================================================================================================![Screenshot (1638)](https://user-images.githubusercontent.com/56502606/121807360-6c94e480-cc71-11eb-8c39-341927b8fcc6.png)
![Screenshot (1639)](https://user-images.githubusercontent.com/56502606/121807362-6dc61180-cc71-11eb-97e5-a1c25063c81a.png)
![Screenshot (1640)](https://user-images.githubusercontent.com/56502606/121807363-6e5ea800-cc71-11eb-8395-3cab53bdf025.png)
![Screenshot (1641)](https://user-images.githubusercontent.com/56502606/121807366-6f8fd500-cc71-11eb-89f9-de84c5a68984.png)
![Screenshot (1642)](https://user-images.githubusercontent.com/56502606/121807370-79193d00-cc71-11eb-9394-9527ba27da79.png)

DECISION TREE REGRESSION MODEL​

Decision tree model approach/steps:​

Step 1: Import the required libraries. ​

Step 2: Initialize and print the Dataset.​

Step 3: Select all the rows and column 1 from dataset to “X”. ​

Step 4: Select all of the rows and column 2 from dataset to “y”. ​

Step 5: Fit decision tree regressor to the dataset. ​

Step 6: Predicting values on test set. ​

Step 7: Visualizing the result.​

============================================================================================================================================================================
RANDOM FOREST REGRESSION MODEL​

Random forest algorithm approach/steps:​

Pick random k data points from the training set​

Build the decision tree associated with those k data points​

Choose the number of trees you want to build and repeat step 1 and 2.​

For a new data point, make each one of your tree to predict the value of Y(target) for the data point, and assign the new data point the average across all of the predicted Y values. ​
  
=============================================================================================================================================================================
It is observed that the Random Forest Regressor outperformed the Decision Tree Regressor due to the overfitting nature of decision tree on training data.
