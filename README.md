# Portfolio-Management-Investment-Analysis-Fundamentals-in-Python

Calculate and compare the performance of stocks and stocks indicies
# a. Install must-have Packages for finance

Numpy: a third-party package allowing us to work with multidimensional arrays
Pandas: allows us to organize data in a tabular form and to attach descriptive labels to the rows and columns of the table
Matplotlib: a two-dimensional plotting library specially designed for visualizations of NumPy computations
Math: involves mathematical functions
Random: invokes random number of generators
Statsmodels: Descriptive statistics, plotting functions, regressions, etc.
Pandas_datareader: Extension to read data from web

# b. Extract data from Yahoo Finance for Microsoft from the 1st of January 1995. The ticker you need is ‘MSFT’. 

# c. A few pandas methods can speed up this analysis
.info: will first tell you we are examining a data frame object. How many entries and the time span
.head: first 5 rows of the dataset
.tail: last 5 rows of the dataset

# d. Create a data set that contains five columns representing five different companies by Adj Close

When we think of our investment we have to evaluate its downside ond its upside. You must consider this parameters: the profit you can expect and the risk of losing money.
The art of finance is all about making informed decisions that consider both dimensions risk and return and optimizing the risk-return combinations of an investment portfolio.
To make an evaluation we have to calculate the return of a single security and portfolio & assesing risk by calculating the standard deviation, variance, correlation and covariance.associated with them

# e. Calculate simple rate of return of Microsoft for the given timeframe.
Simple return is dividing today's adjusted closed price by yesterday's adjusted closed price minus 1.
The most significant observations are mainly negative, in finance we are accustomed to seeing negative returns that have a much higher magnitude of positive returns. Usually positive returns accumulate over time and stock prices increase but when things do go wrong, stock prices tend to fall very quickly. An investor who is interested in buying a stock and holding it in the long run is mainly interested in the average rate of return that the stock will have.    

# f.Let's calculate the daily annual rate of return of the stock
# g. Let's calculate the average annual rate of return of the stock
# h. Let's round the average annual rate of return of the stock to make it more presentable
# i. Calculate log return (the difference is that logreturn is better when we explore the behaviour of a single stock)
# n. Calculating a portfolio of securities rate of return 
# We need a formula help to us normalize the data to 100. The idea of this operation is comparing the stock as if they were all starting from the same value.
# Assigning the weights as an array we can compare and calculate the returns between identical portfolios. 

# Create a data set that contains four columns representing four indexes
#Note that the values of indices are much higher with respect to the adjusting closing price of companies
#That is only natural, given that indices are baskets composed of many stocks
#Let's normalize the data to 100 and plot it like a graph
#Interpretation of the graph: Around of the millenium we observe a rise of the indicies value. This was because there was a dotcom bubble and the stock markets were boosted by a significance rise of tech companies.
#In the long term we can say that overall all indicies perform very well with only FTSE below the initial growth level.
#NASDAQ scores the highest in certain periods of time, experiencing in 2020 the sharpest growth.
#The German Market demonstrate real persistence and stability. 
#We can conclude that NASDAQ surpasses the rest of the indicies easily
#Explained by the sharp growth experimented by tech companies from the pandemic years.
#Let's put the adjusted closing price of a company and compare its performance with one of the indicies.
#Let's opt for SP500 and then include Dow Jones Industrial Average
#Let's normalize our data 
Conclusion: We will be able to see that PG did better the last 27 years compared to the index.
This is how we can compare the performance of stocks and stocks indicies
