# Time sereis analysis and forecasting
This data sets contails real TV viewership data.The data set has the following information:

Date: Year and Month the measurement corresponds to. The data set contains measurements from January 2014 to December 2017. 
Network: The TV channel the measurement corresponds to. We will simply use five categorical identifiers.
Daypart: A “daypart” is a grouping of days and hours that are of relevance in the TV industry. For example, Mondays through Fridays from 8:00 pm to 11:00 pm is a daypart. In the data set, there are 11 dayparts. 
Number of viewers: The actual value of the measurement. 

In this task, I analyze via STL decomposition and ACF as well as PACF plots. A time series in this data set is the set of measurements from January 2014 to December 2017 for each combination of network-daypart. In total, therefore, there are 55 time series in this data set. 

In all our analyses, use the period between January 2014 to December 2016 as the “training” set, and the year 2017 as the “test” data set. Used exponential smoothing (via the HoltWinters function in R) to fit your model and then produce forecasts (using the function “forecast” from the forecast package) for the 55 time series and compare those forecasts with the actuals by creating plots and calculating the mean absolute error (MAE). 

