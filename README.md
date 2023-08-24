# BankCard Analytics - Credit-Debit-Card-Usage-Monitoring
The "BankCard Analytics - Credit & Debit Card Usage Monitoring" project is a comprehensive data analysis initiative aimed at extracting valuable insights from bank card usage data. The project utilizes a variety of tools and techniques, including Python, Excel, Tableau, web scraping with BeautifulSoup, pandas for data manipulation, and data visualization techniques. The project centers around understanding and visualizing trends and patterns in credit and debit card usage across multiple banks.

# Workflow:

  1. Data Collection through Web Scraping:

The project began by scraping data from the Reserve Bank of India's website, specifically targeting the last 10 months of data. Python's BeautifulSoup library was employed to extract the necessary data from the website, and the extracted data was then downloaded to the local machine.  
Skills Used: Python, BeautifulSoup, web scraping.  
website - https://www.rbi.org.in/Scripts/ATMView.aspx

![image](https://github.com/NiNja-09/BankCard-Analytics---Credit-Debit-Card-Usage-Monitoring/assets/60342946/b476b50a-622c-4071-b6de-4d6cd65b6f9a)

  2. Data Cleaning and Transformation in Excel:

Upon downloading the data, it was observed that certain issues needed to be addressed. The data in Excel files underwent a thorough cleaning process, guided by a set of rules to ensure uniformity and reliability. This included deleting irrelevant columns, unmerging cells, aggregating transactions, converting values to Indian Rupees (₹), and eliminating rows with empty values. Additionally, the data structure was modified to differentiate between different banks and their respective bank types.  

Skills Used: Excel, data cleaning, data transformation, macros.

downloaded excel file -
![image](https://github.com/NiNja-09/BankCard-Analytics---Credit-Debit-Card-Usage-Monitoring/assets/60342946/6a64e7a5-9512-4e98-906f-cadb379ec727)

Cleaned excel file -
![image](https://github.com/NiNja-09/BankCard-Analytics---Credit-Debit-Card-Usage-Monitoring/assets/60342946/61258103-828d-4605-9400-e58bcec954c1)


  3. Data Consolidation:

After cleaning and structuring the data from multiple files, the individual files were consolidated into a single file. An extra column was added to indicate the respective month and year for each data entry, enhancing the dataset's interpretability and facilitating temporal analysis.  

Skills Used: Excel, data consolidation.

  4. Data Visualization and Dashboard Creation in Tableau:

The consolidated dataset was then imported into Tableau for advanced data visualization. The Tableau platform enabled the creation of interactive dashboards that showcased various dimensions of credit and debit card usage. Different visualizations were designed to represent metrics such as the number of cards issued, transaction volumes, spending, spend per card, average transaction size, and market share based on different factors.  

Skills Used: Tableau, data visualization, dashboard creation.

![image](https://github.com/NiNja-09/BankCard-Analytics---Credit-Debit-Card-Usage-Monitoring/assets/60342946/e16d487b-b066-48f5-b1ab-79acf30d566c)


Tableau Public Dashboard Link - https://public.tableau.com/app/profile/ninad.patil/viz/Tableau-CardUsageMonitoringDashboard/Dashboard1

# Insights:

Total Usage Insights:  

-Total transactions: 4,976 million  
-Total cards issued: 9,508 million  
-Total market share: ₹18,309.26 billion

Bank Type Insights:  

-Foreign banks account for 5.12% of market share.  
-Public sector banks hold a market share of 29.88%.  
-Private sector banks dominate with a market share of 65.00%.

Card Usage Trends:  

-The number of debit cards issued declined from September 2022 to June 2023, while credit card numbers increased during the same period.  
-The top three banks in terms of total spend vs. total transactions are State Bank of India, Axis Bank, and Kotak Mahindra Bank.

Month-wise Analysis:  

-Total spending for credit cards was highest in May 2023.  
-The total number of credit/debit cards issued peaked in June 2023.  
-The number of debit cards issued exceeded credit cards.

# Conclusion:
The "BankCard Analytics - Credit & Debit Card Usage Monitoring" project demonstrates the power of data analysis in understanding financial trends. By employing web scraping, data cleaning, consolidation, and visualization techniques, we successfully gained insights into credit and debit card usage across different banks and bank types. The interactive Tableau dashboard provides a user-friendly platform to explore the trends and patterns in card usage, enabling better decision-making for stakeholders in the finance industry. This project showcases skills in data handling, visualization, and analysis that are essential for effective data-driven decision-making.
