Analysing 20 years of Netflix (NFLX) stock data to uncover price trends, trading volume patterns, and key market events using Python.


📌 Business Problem
Netflix is one of the most watched stocks in the tech sector. Investors, analysts, and business teams need to understand:

When did Netflix experience its biggest growth phases?
Are there seasonal patterns in trading volume?
What were the peak and trough price points — and what drove them?

This project answers these questions using historical NFLX stock data with Python-based EDA.

🎯 Objectives
#Question1How has Netflix stock price evolved over 20 years?2Which months/years show the highest trading volume?3What are the top 5 dates with the highest and lowest closing prices?4Is there a pattern between high volume and price movement?5What does the overall price trend look like — bullish or bearish phases?

📁 Project Structure
Netflix-Stock-Analysis/
│
├── Netflix project.ipynb      # Main analysis notebook
├── NFLX.csv                   # Raw stock dataset (Kaggle)
├── Objective.txt              # Project goals
└── README.md                  # Project documentation

🔍 Key Insights

Explosive growth phase (2012–2021): Netflix stock grew from ~$10 to an all-time high of ~$700, driven by global subscriber expansion and content investment.
2022 sharp correction: The stock dropped over 70% from its peak — the steepest annual decline in Netflix's history — triggered by subscriber loss and rising competition.
Highest volume years were 2011 and 2022 — both years marked major business turning points (password sharing crisis, initial streaming boom).
Month-wise pattern: January and October tend to show higher trading volumes, likely aligned with quarterly earnings releases.
Top 5 peak prices all occurred in November 2021, just before the major correction — a signal that the stock was in an overbought zone.


📈 Visualisations Included

📊 Volume vs Time (yearly, monthly, day-wise breakdown)
📈 Stock price trend — High, Open, Close over 20 years
🟢 Top 5 dates with highest closing prices
🔴 Top 5 dates with lowest closing prices
📉 Year-wise average closing price trend


🛠️ Tech Stack
ToolPurposePython 3.xCore programming languagePandasData loading, cleaning, groupingNumPyNumerical operationsMatplotlibLine charts, bar chartsSeabornEnhanced visualisationsJupyter NotebookInteractive analysis environment

▶️ How to Run
bash# 1. Clone the repository
git clone https://github.com/guptavanshi/Netflix-Stock-Analysis.git

# 2. Install dependencies
pip install pandas numpy matplotlib seaborn

# 3. Open the notebook
jupyter notebook "Netflix project.ipynb"

📂 Dataset

Source: Kaggle — Netflix Stock Data
File: NFLX.csv
Columns: Date, Open, High, Low, Close, Adj Close, Volume
Period: 2002 – 2022 (20 years of data)


🔮 Future Scope

 Add 20-day and 50-day Moving Averages for trend analysis
 Build a price forecasting model using ARIMA or LSTM
 Create an interactive dashboard using Streamlit or Power BI
 Compare NFLX performance vs competitors (Disney+, Amazon Prime)


👩‍💻 About Me
Vanshika Gupta — Final year B.Tech student passionate about Data Analytics.
Skills: Python · Pandas · SQL · Power BI · Matplotlib · Seaborn · Excel
📧 Connect with me on LinkedIn | GitHub


⭐ If you found this project useful, consider giving it a star!
