Project Overview

In this project, we'll predict the price of the S&P500 stock market index.
(The Standard and Poor's 500, or simply the S&P 500, is a stock market index tracking the stock performance of 500 of the largest companies listed on stock exchanges in the United States.)
Similarly we can use this model for any different stock prediction just by changing tick value to required stock value.

Project Steps

-Download data using the yfinance package

-Create an initial machine learning model and estimate accuracy

-Build a backtesting engine to more accurately measure accuracy

-Improve the accuracy of the model



File Overview:

stock_prediction.ipynb: This Jupyter notebook encompasses all the necessary code for the project.
Local Setup



Installation Requirements:
For a smooth replication of this project, ensure you have the following installed on your system:

-JupyterLab

-Python 3.12 or later



-Python Packages:
-Install the following packages required for the project:

pandas: For data manipulation and analysis.

yfinance: Used for downloading historical market data.

scikit-learn: For implementing machine learning algorithms.




Data Acquisition:
Data for this project will be fetched in real-time using the yfinance package during the execution of the notebook.


*This model is not autonomous in any way, to find the stock prediction daily we need to run this model daily and download the data package from yfinance.
