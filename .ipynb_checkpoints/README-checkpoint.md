# Module4Challenge

# Portfolio Analysis
This portfolio analysis project uses Python and Pandas to evaluate and compare the performance of various portfolios including algo, hedge fund, and custom portfolios against the S&P TSX 60 Index. The project includes different types of analyses like performance analysis, risk analysis, and rolling statistics.

## Functions
In this assignment, I created some functions to analyse the provided portfolios and my own equal weighted (EW) portfolio. Here is a short explanation to my functions.

- `clean_data`: This function reads a CSV file into a DataFrame, checks for null values, drops any rows with null values, and returns the cleaned DataFrame. (required input: file name of the csv file)
- `get_beta`: This function calculates and plots the rolling beta of a given portfolio against the S&P TSX 60 for a specified window of days. The beta measures the portfolio's sensitivity to market movements. (required input: name of the dataframe, column name of the return data and the time frame of rolling window)
- `get_sharpe_ratio`: This function calculates and plots the Sharpe Ratios of all the portfolios. The Sharpe Ratio is a measure of risk-adjusted return, which compares the portfolio's excess returns to its standard deviation. (required input:name of the dataframe)
- `reading_data`: This function reads a CSV file into a DataFrame, sets the Date column as index, and returns the DataFrame with closing price. (required input: file name of the csv file)



