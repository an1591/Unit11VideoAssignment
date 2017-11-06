"# Unit11VideoAssignment" 

Purpose: This repository contains the files related to the Unit11.4 Video Lecture Assignment for MSDS6303.
The analysis is based on INTC stock prices from 11/6/2005 thru 11/6/2017.  The data was pulled from Yahoo Finance and is available in the intc.csv datafile.

Author: Ann Nelson
Create Date: 11/6/2017

Process Flow:
Create the dataframe
Explore the time series a little
Calculate log(returns) and log(Volume)
Calculate the overall volatility measure
Calculate the volatility measure estimates for 3 lookback windows
Plot the volatility estimates along with the actual log(return) rate

Dependencies:
   tseries library
   fpp library
   
Notes:  There are several functions that do not work on time series datasets, so there are several conversions between dataframes and time-series.  
