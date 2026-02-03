# [ PART A - DATA PREPARATION ]
This repository contains a comprehensive data analysis project exploring the impact of market sentiment—specifically the **Bitcoin Fear & Greed Index**—on the behavior and profitability of traders on the **Hyperliquid** decentralized excha
* **Data Synthesis:** Aligning high-frequency trade data with daily sentiment classifications.
* **Behavioral Analysis:** Quantifying how 'Fear' and 'Greed' influence trader metrics such as win rates, trade frequency, and position sizing.
* **Strategic Insights:** Developing "rules of thumb" and risk management protocols to optimize trading performance based on historical sentiment patterns.
* **Segmentation:** Identifying trader archetypes (e.g., "The Contrarians" vs "The Chasers") and their performance across different market regimes
* **Python** (Pandas, NumPy) for data cleaning and feature engineering.
* **Matplotlib & Seaborn** for data visualization and evidence-backed insights.
* **Jupyter Notebook** for end-to-end reproducible research.

# [PART B - ANALYSIS ] HERE ARE THE INSIGHTS THAT I FOUND
 1. *Profitability Gap:* Average PnL is significantly higher during "Fear" ($11,085) than during "Extreme Greed" ($1,131).
 2. *Win Rate Decay:* The win rate drops from ~40% in Fear phases to less than 10% in Extreme Greed phases.
 3. *High Activity in Fear:* Traders are 4x more active (129 trades/day) during Fear than Greed, indicating a "buy the dip" aggressive behavior.

# [PART C - ACTIONABLE OUTPUT ] HERE ARE THE STARTEGIES THAT I SUGGEST
   *Strategy 1:* Implement "Greed Caps" — reduce maximum position sizes by 50% when the index exceeds 75, as the data shows a 30% drop in win probability.
   *Strategy 2:* Contrarian Signal — increase leverage only for the "Consistent Winner" segment when sentiment is below 25 (Fear).
