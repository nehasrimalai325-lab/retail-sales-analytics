# retail-sales-analytics
End-to-end retail analytics project using Excel, MySQL, Python and Power BI, covering data cleaning, SQL analysis, RFM customer segmentation and an interactive dashboard.
# Tools: 
Excel · MySQL · Python (Pandas, SQLAlchemy, Matplotlib, Seaborn) · Power BI
# Ojective
Give retail management a single view of sales performance, inventory levels and customer value by connecting Excel, SQL, Python and Power BI in one pipeline.
# Workflow
- Excel: cleaned and standardised 9 tables (headers, duplicates, missing values, data types) and exported them as CSVs.
- MySQL: created the retail database, loaded the data and wrote analytical queries.
- Python: ran EDA and RFM customer segmentation, then saved the results back to MySQL.
- Power BI: built an interactive dashboard on top of the database.

<img width="1244" height="716" alt="image" src="https://github.com/user-attachments/assets/abc3e418-1242-4a95-8107-38d7dea3b0e5" />

<img width="1255" height="724" alt="image" src="https://github.com/user-attachments/assets/a99c6181-c450-4966-a10c-5303553eb918" />

<img width="1245" height="717" alt="image" src="https://github.com/user-attachments/assets/8114a4b8-4500-4b4e-b88a-975af24ec04b" />

# Conclusion

This project delivered a complete retail analytics pipeline. Excel was used to clean and standardise nine relational tables, MySQL to store and query them, Python to analyse the data and segment customers with RFM, and Power BI to present the results in an interactive dashboard.

The analysis turns raw transaction data into clear answers about store and staff performance, stock risk and customer value. About 89% of order lines were completed, which points to a healthy fulfilment process. RFM segmentation separated VIP Loyal Champions from Regular Active Buyers and Inactive Customers, so marketing can be targeted by segment instead of treating every customer the same.

# Recommendations
- **Retain** VIP customers with loyalty rewards and priority offers.
- **Re-engage** inactive customers with targeted campaigns.
- **Restock** products flagged by the low-stock alerts before they affect sales.
- **Review** the shipped dates that fall before order dates to fix the data quality issue at the source.

# Future scope:
Apply K-Means clustering to the RFM values, add sales forecasting, and automate data refresh so the dashboard stays current.
