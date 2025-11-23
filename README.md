 README – Fear & Greed Index Impact on Trading Behavior & PnL
 Project Title:

Analyzing the Impact of Market Sentiment (Fear & Greed Index) on Trading Activity and Profitability

 Project Description

This project analyzes how the Fear & Greed Index influences overall market behavior using daily trading activity and PnL data.
The goal is to identify whether market sentiment (Fear or Greed) has a measurable effect on:

Total trades

Buy vs Sell decisions

Total traded volume

Profit & Loss (PnL)

This project helps traders understand how emotions in the market correlate with trading performance and decision-making.

2. Objective

The main objectives of this analysis are:

To understand how different emotional phases (Fear, Neutral, Greed) impact trading activity.

To examine whether PnL improves or worsens during specific sentiment phases.

To find correlations between market sentiment and:

Buy/Sell trends

Trading volume

Average execution price

3. Dataset Overview

The dataset includes 7 days of trading data with the following columns:

Date

Total Trades

Buy Trades

Sell Trades

Total Volume (USD)

Average Execution Price

Daily PnL

Fear–Greed Index

The Fear–Greed Index values are categorized into:

0–30 → Fear

31–60 → Neutral

61–100 → Greed

4. Methodology

Data Cleaning

Removed duplicates

Converted date column

Verified numeric fields

Sentiment Classification

Based on Fear–Greed Index ranges, each day was labeled as Fear, Neutral, or Greed.

Exploratory Data Analysis

Compared sentiment against trades, volume, and PnL.

Identified patterns in trading behavior.

Correlation Study

Checked how PnL changes with emotion phases.

Visualization

Multiple graphs used to show trends and relationships.

5. Key Insights
Insight 1 – Buy vs Sell Behavior Changes With Emotion

Greed days: More buy trades, higher trading activity.

Fear days: More sell trades, reflecting panic or risk reduction.

Neutral days: Balanced trading decisions.

Insight 2 – PnL Strongly Correlates With Market Sentiment

Highest PnL values appear on Greed days.

Negative or low PnL appears on Fear days.

Market emotion directly impacts profitability.

Insight 3 – Trading Volume Spikes During Extreme Emotions

Both Fear and Greed phases show high volume but for different reasons:

Fear → Panic selling

Greed → Aggressive buying

Insight 4 – Average Execution Price Rises in Greed

Prices trend higher when the market is optimistic.

Prices fall during Fear periods.

📈 6. Recommended Graphs to Include
1.Line Chart – Fear & Greed Index vs PnL

Shows how sentiment affects profitability.

2.Bar Chart – Buy vs Sell Trades

Shows trading behavior changes under emotions.

3.Stacked Area Chart – Total Trades vs Sentiment

Shows spikes in trading activity.



7. Final Conclusion

This project successfully proves that market sentiment, measured using the Fear & Greed Index, has a strong influence on trading behavior and profitability.

Greed = High buy activity + Positive PnL

Fear = High sell activity + Negative PnL

Neutral = Stable, less volatile behavior

This analysis can help traders adjust their strategy based on market emotions and improve decision-making.
