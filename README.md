# Bitcoin Market Sentiment vs Trader Performance

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader performance.

## Dataset
- Bitcoin Fear & Greed Index
- Hyperliquid Trader Data

## Key Insights
- Traders perform worst during Extreme Fear
- Profitability and win rate increase in Greed phases
- Traders take larger positions during Greed
- Selling performs better than buying in Greed
- ML model shows trade features matter more than sentiment

## Model Used
- Random Forest Classifier
- Accuracy: ~85%

## Conclusion
  Market sentiment significantly influences trader behavior, with losses dominating during Extreme Fear and improved performance in Greed    phases. Traders also take larger and riskier positions in bullish conditions. However, predictive modeling shows that individual trade     success depends more on trade-specific factors like execution price and size rather than sentiment alone.

## Tools Used
- Python
- Pandas
- Seaborn
- Scikit-learn
