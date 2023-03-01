

# Stock Prediction using Machine Learning

This project aims to predict the stock prices of Tesla using machine learning algorithms. The dataset used is the historical stock prices of Tesla, which is imported using Pandas library from the CSV file.

## Libraries Used:

- Pandas
- Scikit-learn
- Matplotlib
- Numpy
- datetime

## Data Preprocessing:

The dataset is preprocessed to remove the missing values and normalize the data using the MinMaxScaler. Then, it is split into training and testing datasets for model training and evaluation purposes.

## Model Selection:

For this project, the Linear Regression model is used for predicting the stock prices. The model is trained on the training dataset and then tested on the testing dataset. The accuracy of the model is evaluated using the R2 score, which is a statistical measure that determines how well the predicted values fit the actual values.

## Forecasting:

The trained model is then used to forecast the future stock prices of Tesla. The forecasted values are added to the original dataset and plotted along with the original stock prices to visualize the trend.

## Results:

The forecasted values are compared with the actual stock prices to determine the accuracy of the model. The results are plotted using Matplotlib library to compare the predicted and actual values.

## Conclusion:
The Linear Regression model is found to be an accurate predictor of the Tesla stock prices, with an accuracy score of 0.877948583083247 for the test data. The project provides valuable insights into the potential of machine learning algorithms in predicting the stock prices of companies, which can be useful for investors and traders.
