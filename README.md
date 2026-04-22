# ACC102-BYD-Data-Analysis: BYD Stock Price & Sales Performance Analysis
## 1. Problem & User
This project analyzes the relationship between BYD’s A-share/HK-share stock price trends and its new energy vehicle sales performance to reveal how operational results affect capital market performance. The target users include business/accounting students, individual investors, and automotive industry analysts.

## 2. Data
- Stock price data: AKShare (Eastmoney-based financial data interface); Access date: 2026-04-09; Key fields: Date, Open, High, Low, Close, Volume (002594.SZ & 1211.HK, 2025-01-01 to 2026-04-01)
- Sales data: BYD official monthly sales announcements; Access date: 2026-04-09; Key fields: Month, Sales_Volume

## 3. Methods
1. Use **AKShare** to fetch BYD A-share and HK-share historical data
2. Use **Pandas** for data cleaning (renaming columns, date conversion, dropping NaN/duplicates) and descriptive statistics
3. Use **Matplotlib** to plot stock price trends and sales bar charts
4. Export cleaned data to CSV files and organize the full workflow in Jupyter Notebook

## 4. Key Findings
- BYD’s A-share and HK-share prices show highly consistent fluctuation trends
- Strong sales growth in 2025 provided fundamental support for BYD’s stock performance
- BYD’s sales volume peaked in December 2025 and declined seasonally in Q1 2026
- Business operational performance is positively correlated with stock price trends

## 5. How to run (Mac)
1. Install dependencies: `pip3 install pandas akshare matplotlib notebook`
2. Open terminal, go to project folder: `cd Desktop/ACC102-BYD-Data-Analysis`
3. Launch Jupyter: `jupyter notebook`
4. Open `byd_analysis.ipynb` and run all cells

## 6. Product link / Demo
- GitHub Repository: https://github.com/lesley803/ACC102-python-data-analysis
- Demo Video: https://github.com/lesley803/ACC102-python-data-analysis/blob/main/ACC102-BYD-Data-Analysis/4月20日(1).mp4

## 7. Limitations & next steps
- Limitations: Short data time span, limited sales sample points, no macroeconomic/financial indicators
- Next steps: Extend data to 3–5 years, add competitor (e.g., Tesla) comparison, include financial indicators, build an interactive analysis tool## Dataset
1. Stock Price: AKShare (2025-01-01 to 2026-04-01)
   - A-share: 002594.SZ
   - HK-share: 1211.HK
2. Sales Data: BYD Official Monthly Announcements
3. Access Date: 2026-04-09
