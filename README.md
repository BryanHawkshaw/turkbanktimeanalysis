# Turkish Bank Atm Transactions
The goal of this project is to forecast future amounts for needed ATM Balances that would satisfy the transaction demand based on hourly recorded data for a week in different places in the city of Izmir, Turkey.

# Introduction
Don't you just hate it when you get to the ATM after a long travel and you can't withdraw because the ATM machine is out of cash. 

Yeah me too. Now you can't get that delightful looking sheperd's pie from the bakery that only accepts cash. Absolutely hate it. 

With predictive analytics we have a way of stopping that from happening using time series forecasting. As long as we have values and a datetime series we can predict future values.

In this project I will utilize baseline models, Auto Regressive Integrated Moving Average (ARIMA), Seasonal Auto Regressive Integrated Moving Average (SARIMA) and the Prophet model from facebook.

# Data Extraction
The goal of this project is to forecast future amounts for needed ATM Balances that would satisfy the transaction demand based on hourly recorded data for a week in different places in the city of Izmir, Turkey. The dataset was extracted from Kaggle as a comma separated values file format and contains 60312 rows and 13 columns. It was loaded into a database in the MySQL Workbench. The main columns for this project are the transaction time and the atm balance. The data types for these column are datetime (%Y-%m-%d %H-%M-%S) and integer respectively.

# Library Importation
The MySQL credentials were stored in an .env file .
