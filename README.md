# Project Overview
This project is about predicting the prices of three cryptocurrencies (GRT, FET, and OCEAN) using the time series forecasting tool, Prophet. It involves importing the necessary libraries for data visualization and time series forecasting, loading the historical prices data for each cryptocurrency into a pandas dataframe, concatenating the dataframes together, and fitting the Prophet model to each cryptocurrency data. Then a future dataframe is created to hold the predicted prices for each cryptocurrency, and predictions are made for each cryptocurrency using the Prophet model. The predicted prices are then plotted using Matplotlib, hvplot, and Seaborn.
# Code Breakdown
The first block of code imports the required libraries which are Seaborn, Pandas, Matplotlib, Prophet and HvPlot
The second block of code loads the historical prices data for each cryptocurrency into a pandas dataframe, renames the columns, and converts the date column to datetime format.
The third block of code concatenates the dataframes together and prints the resulting concatenated dataframe.
The fourth block of code initializes the Prophet model and fits it to the data for each cryptocurrency.
The fifth block of code creates a future dataframe to hold the predicted prices for each cryptocurrency using the Prophet model, and makes predictions for each cryptocurrency.
The sixth block of code plots the predicted prices for each cryptocurrency using Matplotlib on separate plots and a single plot with subplots.
The seventh block of code plots the predicted prices for each cryptocurrency using hvplot on a single plot with subplots.
The eighth block of code creates a scatterplot of the predicted prices for each cryptocurrency using Seaborn.
# Expected Outputs
The expected outputs of this project are visualizations of the predicted prices of the three cryptocurrencies over a specified period of time using Matplotlib, hvplot, and Seaborn.
