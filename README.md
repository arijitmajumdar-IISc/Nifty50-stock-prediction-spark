# Installation

Before running the code, you need to install the required dependencies.
pyspark
xgboost
python-Levenshtein
newspaper3k nltk
googlesearch-python
pmdarima
missingno
yfinance

# Usage

## Data Preparation and Analysis

•	Import required libraries and download necessary JAR files.
•	Install and import Python libraries for data analysis, machine learning, and sentiment analysis.
•	Create a Spark session and define the stock symbol.
•	Download historical stock data for the specified symbol.
•	Convert the data to a Spark DataFrame, perform data transformations, and split the data into training and testing sets.
•	Explore and visualize the data, including calculating and displaying the correlation matrix.




## Machine Learning Models

•	Train a Linear Regression model on the stock data and evaluate its performance.
•	Train a RandomForestClassifier model on the stock data and evaluate its performance.
•	Train an XGBoost model on the stock data and evaluate its performance.



## Sentiment Analysis

•	Perform sentiment analysis on news headlines related to the specified stock symbol.
•	Analyse sentiment for both individual stocks and industry sectors.

Data Integration and Recommendation

•	Join sentiment analysis results with stock data.
•	Create a final DataFrame with relevant columns for sentiment analysis.
•	Conclude the project by selecting Linear Regression as the preferred model based on performance.

## Database Management

•	Create a managed database to store the project's data.
•	Write the relevant DataFrame to a CSV file, convert it to a Spark DataFrame, and save it as a table in the database.
•	Perform SQL queries on the data for further analysis.

## Time Series Analysis (ARIMA and SARIMAX)

•	Check stationarity of the stock data and apply necessary transformations.
•	Train ARIMA and SARIMAX models for time series prediction.
•	Evaluate and compare the performance of the time series models.



# Conclusion

The project provides a comprehensive approach to stock price prediction and sentiment analysis, incorporating machine learning models, natural language processing, and time series analysis. The chosen Linear Regression model and the integrated sentiment analysis offer insights into potential market trends and investment decisions. The project concludes with data storage in a managed database for future reference.

![image](https://github.com/arijitmajumdar-IISc/Nifty50-stock-prediction-spark/assets/151856679/d09d968e-baf4-4629-abea-587037ad6d2e)

** ARIMA and SARIMAX are not part of Spark ML – hence used it from outside spark and later integrated the result with Spark Dataframe



