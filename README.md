There is an archive called quantquote_daily_sp500_83986.zip, which can be downloaded from the Quantquote website. This archive contains 500 csv files, which contain data on quotations on American stock exchanges of companies included in the S&P 500 index.
Data for each company is contained in a separate file. 

Each file contains 7 columns:
- **dat** - date of exchange trading
- **z** - indicator
- **opn** - opening price
- **mx** - maximum price
- **mn** - minimum price
- **clo** - closing price
- **vol** - volume of sales


The purpose of this work is to build a linear regression model that, based on data on the closing prices of trades for 9 companies for today, will predict the closing price for the target company for the next day.
I chose 10 companies out of 500, and from them randomly chose one that will be the response (we will predict the value for it), the remaining 9 will be regressors, respectively.
