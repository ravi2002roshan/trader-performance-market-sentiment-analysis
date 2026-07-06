## Trader Performance vs Market Sentiment Analysis

# Overview

This project analyzes the relationship between Bitcoin Market Sentiment (Fear & Greed Index) and trader performance on the Hyperliquid platform.

The objective is to understand whether market sentiment influences trader profitability and trading behavior.

---

# Dataset

Two datasets were used:

1. Bitcoin Fear & Greed Index
2. Hyperliquid Historical Trader Data

---

# Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Project Workflow

1. Load both datasets
2. Perform data cleaning and validation
3. Convert timestamps to datetime
4. Create daily trader metrics:
   - Daily Closed PnL
   - Win Rate
   - Average Trade Size
   - Number of Trades
   - Long/Short Ratio
5. Merge trader data with Fear & Greed Index
6. Perform exploratory data analysis
7. Visualize results
8. Generate insights and strategy recommendations

---

# How to Run

Clone the repository:

```bash
git clone <repository-link>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Run all cells from top to bottom.

---

# Output

The notebook generates:

- Data cleaning summary
- Trader performance metrics
- Market sentiment analysis
- Charts
- Business insights
- Strategy recommendations

---

# Key Insights

- Trader profitability varies across different market sentiment categories.
- Trading activity changes with market sentiment.
- High-frequency traders generated higher average profits in this dataset.

---

# Strategy Recommendations

- Apply disciplined risk management during Fear markets.
- Use conservative position sizing during Extreme Fear.
- Combine high-frequency trading with proper risk management.

