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

High news volume days exhibited substantially higher market volatility than low news volume days, with same-day volatility averaging 43.0 on high-volume days compared to 21.6 on low-volume days, representing an approximate 99% increase, and next-day volatility remaining high at 42.7 versus 21.8, an increase of about 96%.

Negative-sentiment days showed higher volatility than neutral days, with same-day volatility averaging 33.4 compared to 21.2 (about a 57% increase) and next-day volatility averaging 34.5 versus 20.8 (about a 65% increase). Positive-sentiment days also displayed moderately elevated volatility relative to neutral days, averaging 29.9 on the same day and 29.3 the next day, corresponding to increases of roughly 41% and 40%, respectively.

News volume had a stronger relationship with market reactions than sentiment alone, as high news volume was associated with nearly double the volatility levels observed on low news days (43.0 vs 21.6 same day), while sentiment-driven differences were smaller in magnitude.

Market reactions often persisted beyond the initial trading day, with next-day absolute returns remaining higher following high news volume days (0.00707 vs 0.00592, about a 19% increase) and next-day volatility staying close to same-day levels on high news days.
