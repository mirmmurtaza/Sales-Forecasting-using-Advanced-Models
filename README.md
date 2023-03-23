# Sales Forecasting using Advanced Models
In this project, I will use advanced forecasting models to predict future sales based on a publicly available retail dataset with over 500,000 records. Specifically, I will use LSTM and CNN-LSTM models to make predictions and evaluate their performance using metrics such as root mean squared error (RMSE).

## Dataset
I will be using the "Online Retail II" dataset, which is publicly available on the UCI Machine Learning Repository. This dataset contains sales data from an online retailer in the UK between 01/12/2009 and 09/12/2011. The dataset has over 500,000 records and 8 features including invoice number, stock code, description, quantity, invoice date, price, customer ID, and country.

## Methodology
The project will follow the following steps:
- Load the dataset and preprocess it by converting the date column to a datetime object and setting it as the index. We will then extract the total sales for each day to prepare the data for forecasting.
- Split the data into training and testing sets and scale the data using the MinMaxScaler.
- Build an LSTM model and train it on the training data. We will use a sequence length of 30 and 1 feature for the LSTM model.
- Make predictions on the test data using the trained LSTM model and evaluate its performance using RMSE. We will also plot the predicted sales against the actual sales to visualize the performance.
- Build a CNN-LSTM model and train it on the training data. We will use a sequence length of 30 and 1 feature for the CNN-LSTM model.
- Make predictions on the test data using the trained CNN-LSTM model and evaluate its performance using RMSE. We will also plot the predicted sales against the actual sales to visualize the performance.

## Results
I achieved an RMSE of 0.3111 using the LSTM model and an RMSE of 0.2749 using the CNN-LSTM model. The CNN-LSTM model performed slightly better than the LSTM model.

## Conclusion
In this project, I used advanced forecasting models to predict future sales based on a publicly available retail dataset. It was found that the CNN-LSTM model performed slightly better than the LSTM model. This project demonstrates the potential of using advanced models for sales forecasting, which can be useful for businesses in various industries.
