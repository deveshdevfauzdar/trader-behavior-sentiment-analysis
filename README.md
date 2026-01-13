# trader-behavior-sentiment-analysis
Analysis of trader performance under Bitcoin market sentiment, for an internship project.

**Trader Behavior vs Market Sentiment Analysis**
**About the Project**

This project explores how Bitcoin market sentiment (Fear & Greed Index) influences trader behavior and trading performance. The goal was to understand whether traders perform differently under Fear-driven markets compared to Greed-driven markets, and how risk-taking changes across these conditions.

The analysis was done as part of a hiring assignment focused on deriving practical insights from real trading data.

**Data Used**

Bitcoin Fear & Greed Index
Daily market sentiment data classified into categories such as Fear, Extreme Fear, Greed, etc.

Hyperliquid Historical Trader Data
Trade-level data including execution details, trade size, direction (buy/sell), and closed profit or loss.

**What Was Done**

Cleaned and preprocessed both datasets

Converted timestamps and aligned data on a daily level

Merged trader data with corresponding market sentiment

Analyzed trader performance metrics across different sentiment regimes

Visualized patterns using charts for better interpretation

**Key Insights**

Traders tend to take larger positions during Greed phases, indicating increased risk appetite.

Despite higher risk-taking during Greed, average profitability and win rates do not improve, suggesting overconfidence.

Trades executed during Fear and Extreme Fear periods show relatively better discipline, with improved win rates.

Market sentiment clearly plays a role in shaping trader behavior and outcomes, making it a useful signal for risk management.

**Conclusion**

The analysis suggests that blindly increasing exposure during positive market sentiment can negatively impact performance. Incorporating sentiment awareness—such as controlling position size during Greed and being selective during Fear—can potentially improve trading efficiency and reduce downside risk.

**Tools used**

Python

pandas, numpy

matplotlib, seaborn

Google Colab

**Author**
Devesh



