# Predicting Google (GOOGL) Stock Prices with Machine Learning Using a Linear Regression Model
***
Using Machine Learning and a Linear Regression model , I examined a dataset of GOOGL stock prices from August 19th, 2004 to March 27th, 2018 and used this dataset to predict stock prices for the next 30 days. Although, a Linear Regression is not the most optimal model to predict stock prices taking into account the variability of prices, this project was simply an opportunity to become familiar with Machine Learning concepts. 

*Program Written in January 2021*  
*Pushed to Github in January 2021*

***

## Source Files and Their Roles

`Predicting Google (GOOGL) Stock Prices.ipynb` is the Jupyter Notebook that contains my steps in analyzing and predicting future data in order. I first import the necessary libraries that will be used. I then use Quandl to acquire the data on Google Stock Prices and present the first five entries. Next, I simplify the data for the eye by focusing on `Adj. Close` which is the adjusted closing price that factors in inflation and other such elements. I then plotted this as a line graph to better visualize how the prices have changed over the years. I created a new data value of `Prediction` that is influenced by the forecast which is amount of future days. Next, I set the values of `X` and `y` by further modifying the data. Then, I simply process the data by splitting it, using 80% for training the model and 20% to test the model. Finally, I plot the predicted future data as a yellow line appended to the end of the previous teal-colored line graph.
