# Portfolio-Optimisation Project Overview

The primary goal of this project is to illustrate proficiency in handling diverse datasets, implementing advanced analytics techniques, and delivering actionable insights. This project explores the full data analysis pipeline, including:

Data Acquisition: Collecting data from various sources, including APIs and web scraping.
Data Wrangling: Cleaning, transforming, and preparing data for analysis.
Exploratory Data Analysis (EDA): Uncovering insights through visualizations and statistical summaries.
Data Analysis: Formulating and addressing research questions using advanced analytical techniques.
Data Persistence: Utilizing SQLite for storing and managing datasets effectively.
Final Reporting: Documenting findings in a clear, concise, and visual format.
Key Features

Dynamic Data Sources: Integration of datasets from APIs and web scraping to ensure up-to-date analyses.
Custom Visualizations: Includes pivot tables, cross-tabulations, and rich visualizations for better comprehension.
Advanced Analytics: Covers segmentation, trend analysis, and statistical modeling.
Reproducibility: A clean and structured workflow documented in a Jupyter Notebook for seamless replication.
SQLite Integration: Demonstrates the use of SQLite for data persistence and query optimization.
Technologies and Tools

Programming Language: Python
Libraries:
pandas
numpy
matplotlib
seaborn
sqlite3
Additional libraries as needed for specific tasks
Data Sources: Web APIs, scraped data, and static datasets
Database: SQLite
Notebook: Jupyter Notebook

# Summary

This project is focused on optimizing my personal investment portfolio, consisting primarily of Indian stocks, by exploring the impact of various financial variables and asset classes on portfolio performance. The primary objective was to identify an optimized, diversified portfolio that offers the best return versus risk. Using Ordinary Least Squares (OLS) regression, I analyzed the influence of market indices, cryptocurrencies, commodities like gold and Brent Crude, and the INR/USD exchange rate on the portfolio value. The regression model explained 98.5% of the variability in portfolio value, highlighting the strong impact of these factors on investment outcomes.

The analysis revealed significant positive influences from the NIFTY50 index and Bitcoin, while Ethereum, gold, and Brent Crude had negative impacts. The INR/USD exchange rate significantly increased portfolio value, indicating sensitivity to currency fluctuations. Understanding both immediate and lagged effects of exchange rate changes was crucial, as they highlighted the importance of monitoring and responding to these movements for better investment management.

Through the construction of an efficient frontier, the study visualized the risk-return trade-off for various portfolio combinations. The optimal portfolio, with the highest Sharpe Ratio, predominantly allocated 70% to Indian stocks, 9% to Bitcoin, and 21% to gold. Other assets, including NIFTY50, NIFTY100, Ethereum, S&P 500, INR/USD, and Brent Crude, had negligible weights, indicating their limited contribution to the optimal risk-return trade-off.

Based on these findings, I recommend a diversified investment strategy prioritizing Indian stocks and including allocations in gold and Bitcoin. This strategy aims to maximize returns while minimizing risk, suitable for investors with varying risk tolerances and return objectives. The insights from this analysis can help investors make informed decisions and enhance their portfolio management practices, emphasizing the importance of continual reassessment and adaptation to changing market conditions.
