Project summary:

In this project, we will attempt to predict how ready the market is for any security's quarterly events. We plan on using various statistical and machine learning techniques, but the first step is to use regression which is well understood. The data which will be used for training the regression is that of the security and the indexes preceding the events, against the "coherence" of the reaction of the market after the event of interest. This also relates to sentiments surrounding the market, which is another avenue we may look into, i.e. sentiment analysis.


Regarding the data, we will parse a small set of indices and a large set of tickers, and the regression is justified based on how expectations were priced. 




Pickle Files (Our data)

1. Ticker_history.pkl - Dictionary file with tickers (symbols of companies) as keys and data frames of security prices for over 5 years as the corresponding values. 
2. Index_history.pkl - Dictionary file with index symbols as keys and data frames of index points for over 5 years as the corresponding values. 
3. Saved_indices.pkl - List of the 20 biggest financial indices in the world (from Yahoo Finance). It was used to scrape the aforementioned index dataframes.
4. Saved_symbols.pkl - List of the current members of NASDAQ100. It was used to scrape the aforementioned ticker dataframes.
5. Data for earnings? 


Objectives of this project 


1. Determine whether a security is overcorrected for a volatile event (in this dataset, earnings).
2. Use binary classification and regression to determine the course of the market after the event.
3. If time permits, use sentiment analysis to further determine the market’s direction after the earnings. 



Stakeholders 


1. Proprietary Trading Firms and Retail Investors will benefit by increasing their profits based on our predictions 


