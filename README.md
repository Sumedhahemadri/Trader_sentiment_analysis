 
🧠 Trader Behavior Insights

📌 Problem Statement
Analyze how trader performance changes with Bitcoin market sentiment using two datasets:
Bitcoin Market Sentiment Dataset – Columns: Date, Classification (Fear/Greed)
Historical Trader Data from Hyperliquid – Columns include account, symbol, execution_price, size, side, time, closedPnL, leverage, etc.
Goal: Find how trader profits, losses, and leverage vary during “Fear” and “Greed” periods and uncover patterns that can help in smarter trading strategies.

⚙️ Tools Used
Python
Pandas
Numpy
Matplotlib
Seaborn
Jupyter Notebook

🧩 Steps Followed
Data Loading: Imported both CSV files using pandas.
Data Cleaning:
Converted date and time columns to datetime format.
Removed missing values.
Data Merging: Merged both datasets on Date to connect trader performance with market sentiment.
Exploratory Data Analysis (EDA):
Checked sentiment distribution (Fear vs Greed).
Compared average profit/loss (closedPnL) for each sentiment.
Analyzed leverage and trade sides (Buy/Sell).
Visualization: Used bar plots, boxplots, and heatmaps to identify trends.

📈 Key Insights
Traders earn more profit during “Greed” days.
Leverage is higher when sentiment is Greed, showing more confidence and risk-taking.
Losses are more common during Fear periods.
Buy-side trades perform better during Greed, while Sell-side works better during Fear.
