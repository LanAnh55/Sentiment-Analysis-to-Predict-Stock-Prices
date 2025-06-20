# Sentiment-Analysis-to-Predict-Stock-Prices

Can we use Sentiment Analysis to Predict Stock Prices?

**OVERVIEW**

This project explores the potential of using sentiment analysis to understand the relationship between financial news sentiment and the movements in company stock prices. This project combined web scraping, natural language processing, and financial data analysis to provide insights into market trends and investor sentiment.

**Goal of this notebook:**

- Assess the impact of financial news sentiment on stock prices.
- Generate visual reports and analytics to better understand the correlation between news and stock price movements.
  
**The analysis consists of three steps:**
- PART A: Data Collection
- PART B: Data Visualization
- PART C: Sentiment Analysis
  
**PART A**
- Utilized PRAW to scrape relevant posts from Reddit's r/stocks subreddit
- Fetched historical stock data using the yfinance library
- Focused on major finance companies, with JPM (JPMorgan Chase) as the primary case study
**PART B**
***1. Stock prices**
- Created time series visualizations of stock prices for major finance companies
- Implemented interactive charts for better data exploration
  ![image](https://github.com/user-attachments/assets/4ecf3116-1b47-49d0-991c-dcdaeedd8150)


**2. Sentiment**
- Implemented sentiment analysis on Reddit posts using TextBlob
- Calculated daily average sentiment scores
- Visualized sentiment distribution using histograms
![image](https://github.com/user-attachments/assets/15c6b12d-dd6b-4a5e-97b9-d1bec406d457)


Sentiment distribution was roughly bell-shaped with a slight positive skew, ranging from -0.4 to 0.8, with most scores between 0 and 0.2

**PART C**
- Synchronized Reddit sentiment data with corresponding stock prices
- Time series plots of sentiment vs. stock prices
![image](https://github.com/user-attachments/assets/5817965e-8c71-46c7-a6ff-af8ea6a2e89c)


**Data Insights**
Emotions drive customer behavior, sentiment analysis on customer feedback forms a tool for driving improvement in customer sentiment, customer behavior, and the business itself.

In this case:

1. Correlation Analysis
The correlation coefficient between sentiment and closing price is -0.15, indicating a weak negative correlation.

=> Suggests a complex, non-straightforward relationship between public sentiment and stock prices for large corporations

2. Stock Price Trends vs Sentiment Volatility
- The stock price (orange line) shows a clear upward trend over time, particularly accelerating from 2020 onwards.
- Sentiment scores (blue line) are highly volatile, with frequent and sharp fluctuations.
  
**Key Takeaways**
- The relationship between public sentiment and stock prices for major corporations is complex and not straightforward.
- As one of the largest banks in the world, JPMorgan Chase's stock tends to be more stable due to its large market capitalization.
- Social media sentiment alone may not be a strong predictor of stock performance for large financial institutions. A comprehensive market analysis should combine sentiment data with other financial and macroeconomic indicators.
  
---

**Version:** 1.1.0

**Contact:** Nguyễn Thị Lan Anh ([lananh2004@gmail.com](lananh2004@gmail.com))

