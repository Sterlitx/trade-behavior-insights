
# 📊 Trader Behavior Insights

This project explores how Bitcoin market sentiment (Fear & Greed Index) affects trader performance using two real-world datasets.

## 🧠 Objective
To determine if trader behavior and profitability vary with market sentiment — specifically during periods of fear versus greed.

## 📁 Datasets Used
1. **Fear & Greed Index**
   - Columns: `date`, `classification` (Extreme Fear → Extreme Greed)

2. **Historical Trader Data (Hyperliquid)**
   - Key Columns: `Timestamp IST`, `Closed PnL`, `Account`, etc.

## 🔍 Key Insights
- **Extreme Greed** had the highest average PnL.
- **Extreme Fear** showed the highest volatility (risk).
- Median PnL across sentiments = $0 → suggesting break-even behavior for most trades.

## 📊 Visuals Included
- Boxplot: PnL distribution by sentiment
- Bar chart: Number of trades per sentiment
- Bar chart: PnL volatility by sentiment

## ▶️ How to Run
1. Open the notebook `trader_behavior_insights.ipynb` in Jupyter or Google Colab.
2. Upload the two CSVs:
   - `fear_greed_index.csv`
   - `historical_data.csv`
3. Run all cells to see merged results and visualizations.

---

**Prepared by:**  
Pagidakula Akshara  
Cybersecurity Student, National Forensic Sciences University  
Email: aksharaindia@yahoo.com  
