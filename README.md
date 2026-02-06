# Analyzing S&P 500 Market Reactions to Financial News
## Tools: Python, Pandas, Matplotlib, VADER Sentiment Analysis, Time Series Analysis

In this project, I analyzed how financial news volume and sentiment relate to short-term market behavior by integrating daily S&P 500 market data with aggregated financial news headlines from 2010–2023.

## Key Steps:
Dataset Preparation: Cleaned and aligned daily S&P 500 price data with financial news headlines, filtering to a consistent 2010–2023 time range. Removed duplicate and empty headlines and engineered interpretable market reaction features, including same-day and next-day volatility and absolute returns.

### Exploratory Data Analysis:

Examined distributions and time trends of news sentiment, news volume, and market reaction metrics. 

Segmented trading days into high vs low news volume groups and negative, neutral, and positive sentiment regimes to enable clear comparisons.

### News Sentiment & Volume Analysis:

Applied VADER sentiment analysis to individual headlines and used compound sentiment scores to represent overall daily tone. 

Aggregated headlines to the daily level to compute average sentiment and news volume as measures of information intensity.

### Methodology:

Compared same-day and next-day market reactions across news conditions using group means, medians, and effect size differences. 

Focused on volatility and absolute returns to assess both immediate and delayed market responses to information flow.

### Key Takeaways:

High news volume days exhibited nearly double the average market volatility compared to low news days, with elevated volatility persisting into the following trading day.

Negative-sentiment days showed higher volatility than neutral days both same day and next day, while positive-sentiment days also displayed moderately elevated volatility.

News volume had a stronger relationship with market reactions than sentiment alone, suggesting that information intensity plays a larger role than tone.

Market volatility and price movement often continued into the next trading day rather than being fully absorbed immediately.
