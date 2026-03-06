# Trader Behavior vs Market Sentiment Analysis

## Objective
Analyze how trader performance changes under different market sentiment conditions.

## Dataset
1. trader_data.csv – Contains trader transactions
2. sentiment.csv – Market sentiment classification

## Tools Used
Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  

## Setup

Install dependencies:

pip install pandas numpy matplotlib seaborn

## How to Run

1. Open Jupyter Notebook
2. Run analysis.ipynb
3. The notebook will:
   - Clean data
   - Merge trader data with sentiment data
   - Perform analysis
   - Generate charts

## Outputs
- Long vs Short Trades chart
- Trader PNL vs Market Sentiment
- Trade Frequency by Sentiment
- Trade Size vs Sentiment




## Methodology

The analysis begins with cleaning both datasets by removing duplicates and handling missing values. 
Date fields are converted to a consistent format to allow merging of trader activity with daily market sentiment.

The datasets are merged on the date column to analyze how trader behavior changes under different market sentiment classifications.

Key metrics analyzed include:
- Total PNL per trader
- Trader win rate
- Trade frequency by sentiment
- Trade size distribution
- Long vs short trade distribution

Visualization techniques such as bar plots and box plots were used to understand relationships between trading performance and sentiment.

## Key Insights

1. Trader profitability varies significantly across different market sentiment classifications.

2. Certain sentiment conditions show higher trade frequency, suggesting traders react strongly to extreme market moods.

3. Trade sizes tend to increase during extreme sentiment periods, indicating higher risk-taking behavior.

4. Frequent traders generally generate higher cumulative PNL compared to infrequent traders.

## Strategy Recommendations

1. Traders should reduce position sizes during extreme market sentiment to control risk.

2. Algorithmic strategies could incorporate sentiment signals to improve entry timing.

3. Monitoring trader win rates during different sentiment conditions can help optimize trading strategies.

4. Risk management rules should adapt dynamically based on market sentiment levels.
