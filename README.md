# SP500 vs AMD data analysis

This project aims to explain the relationship between S&P500 index and AMD between 2018 to 2019. This is done by acquiring historical data from Yahoo Finance and performing data transformation to clean data. Explorative analysis is conducted to identify its main characteristic, such as type of relationship and spread of data. Dataset is then split into training and testing data to determine whether simple linear regression is able to accurately predict future AMD price, given a certain S&P500 point. The conclusion is that AMD have a relatively strong linear relationship to S&P500.

Future study can be conducted on non-linear modelling such as logarithmic, polynomial and regression spline. Hypothesis testing can also be conducted on slopes to see whether it is statistically significant. Analysis on residuals can also be implemented to test for high leverage points, outliers or influential points. The scope of data can be further expanded by including a larger timeframe (10 year period) and other economic factors such as revenue of AMD, market share in semiconductor industry and current economic growth.

# References
Source for AMD data: https://au.finance.yahoo.com/quote/AMD/history?p=AMD

Source for S&P500 data: https://au.finance.yahoo.com/quote/%5EGSPC/history?p=^GSPC&.tsrc=fin-srch
