# Analyze Stock Performance with Linear Regression and Hypothesis Testing Using Python
~ Created by Alexander Hagmann

The fund management team of our company seeks to improve the performance of its US equity fund by adopting a more quantitative approach (factor investing). As a first step, they want to identify factors that drive stock performance in the fund. They also want to understand how these factors influence fund performance. The fund management team has asked our finance & analytics team to provide such statistical/quantitative analysis.

Your colleagues have already gathered two datasets. The first (stock_prices.csv) contains the daily stock prices for the fund's 15 most important stocks. The second dataset (factors.csv) contains the commonly used Fama/French 5 Factors. As our quantitative analyst, your task is to define and fit one linear regression model per stock that explains stock performance based on the Fama/French 5 Factors. You should then test the importance of independent factors in explaining stock performance. You must conduct hypothesis testing on the regression coefficients (including the intercept) at the 5% significance level. I recommend working with Python (Pandas, Numpy, Matplotlib, Seaborn, and Statsmodels) for this project. Remember, the final models must be free of common time series regression issues such as autocorrelation (serial correlation). Please prepare two results tables for the fund management team with 1) the regression coefficient values for all 15 stocks (5 slope coefficients + intercept per stock) and 2) whether these regression coefficients are significant (true) or not significant (false). The Coefficient of Determination (r-squared) shall be added too. Finally, please sort the five factors from most important to least important when explaining the performance of stocks. 

# Lab scenario
In this lab, you will be a quantitative analyst on the finance & analytics team at an asset management firm located in Toronto, Canada. The firm's fund management team is planning to adopt a more quantitative and analytical approach for its US equity fund with the goal of improving the fund's performance. As the first step, the fund managers seek to identify factors that may influence stock performance and they have asked the finance & analytics team to provide such an analysis. Your boss provides you with data on stock prices and commonly used factors and asks you to test with quantitative/statistical methods if and how these factors drive stock performance. At the end of the project, you will deliver a summary report for the fund management team pointing out if and how the factors significantly influenced the performance of various fund stocks.

# Objectives
- Create and fit basic multiple linear regression models for financial time series data
- Test the significance of independent variables in a regression model (hypothesis testing)
- Perform an Explanatory Data Analysis (EDA)
- Perform a statistical data visualization
- Pre-process and prepare financial) time series data for linear regression
- Understand and interpret the results of linear regression and hypothesis testing
- Identify and handle problems in linear regression models (e.g. autocorrelation)
- Understand why to use covariance stationarity time series in regression analysis and how to transform non-stationary (time series)


