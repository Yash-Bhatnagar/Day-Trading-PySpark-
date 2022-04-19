![enter image description here](https://assets.goldavenue.com/uploads/tag/og_image/1253/sp500.jpg)

## Day-Trading Case
You are Felix Benjamin of LWP Capital, one of Canada’s most prestigious capital and wealth management firms. Lately, you’ve been hearing a lot of worrying talk from clients about “passive investing” and “low-cost ETFs”, and you figure it’s about time to tackle this problem head-on, before more prospective customers start to doubt your ability to forecast the future and actively manage their funds. We can’t have that.

You’ve pulled data from your brokerage with historical daily closing prices from a number of exchanges. The data is in typical candlestick format:

-   The opening and closing prices of the security at the start and end, respectively, of each day
-   The highest and lowest prices that the security ever traded for on that day
-   The total volume of trades during that day

The dataset contains information for both ETFs tracking various popular indexes, as well as individual stocks. Based on your research, the index that  
most customers are talking about is the  **S&P 500**, tracked by (among others) the SPDR S&P 500 Trust ETF (ticker symbol SPY), which tracks the 500 largest US-listed stocks at any given moment, weighted by their market capitalization. The ETF exercises no judgment over the assets it holds – those amateurs!

With your superior market insight and data analysis tools, you should easily be able to find a smaller set of just 100 stocks (weighted evenly) whose average performance on a monthly basis exceeds the S&P 500 over the course of the ten-year period between 2007 and 2017. And since, of course, past performance is a perfect guarantee of future results1, that same subset should continue to outperform the market indefinitely into the future.

## Solution Code
This project uses the application of **PySpark** to retrieve the top 100 outperforming stocks as shown in attached python notebook

**Note:** Dataset has been pre-mined from WRDS (Wharton Research Data Service) and has been imported directly

> Solved By: Yash Bhatnagar
