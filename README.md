# Crypto Portfolio Assembly

Comparing holding bitcoin to constant and dynamically weighted cryptocurrency portfolios

Dynamic Weightings are Calculated Using:

Long Only
1. Highest Beta/Correlation Ratio
2. Highest Correlation/Beta Ratio
3. Highest Esposure Score (w = Beta * Correlation)

Long/Short

5. Market Neutral
6. Leveraged Short Positions

Regime Identification Using Technical Analysis on daily close price bitcoin data tell us whether to be short or long bitcoin
![BTC Regime Analysis](https://github.com/ayodeji-0/Crypto-Portfolio-Assembly/blob/main/BTC_TA.png)

Cross Correlation Matrix for the past 2 Years tells us how each individual asset moves relative to one another. Only correlations to bitcoin (first row/column) are currently used for portfolio assembly.
Future work could look at trading crypto pairs directly without a BTC or USD leg.
![Cross Correlation Matrix - 2Y](https://github.com/ayodeji-0/Crypto-Portfolio-Assembly/blob/main/CrossCorrelationMatrix.png)

Rolling Correlations, Betas, Exposure Scores, and Ratios
![Rolling Metrics](https://github.com/ayodeji-0/Crypto-Portfolio-Assembly/blob/main/RollingMetrics.png)
