
# Yahoo Finance Stock Analysis - Exploratory Data Analysis, Forecasting, Yahoo! Finance API, Web Scraping

![yahoo-finance](https://github.com/user-attachments/assets/41818973-1280-4945-bdc3-465558f75a45)



## Table of Contents
1. Introduction
2. Data Loading
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis
5. Conclusion and Future Work



### Introduction
For this project, we will be looking at the yahoo finance API which provides real market data for stocks, news and financial data. The main goal is to understand how to use the API and build some data visualizations exploring financial data. Using the Yahoo Finance API we can get real market data and explore what insights can be provided and looked into with this data on company financials and stock analysis on companies. For my focus, I will be looking at technology stocks as this provides a wide variety of unique company profiles and different variety of data to analyze.


### Data Loading 
- To get the data, we first have to import the yahoo finance api into python using the required library name which is this case is yfinance and yahoo_fin_.stock_info to get the stock info we need of real market data.
- After loading all the libraries and installing them, we can load the data calling the api in python calling for the stock ticker name into a variable and we can get the basic financial information of that stock
- For this analysis, I will be looking at Microsoft' stock so we call 'MSFT' since that is microsoft's stock ticker symbol in the stock exchange
- Using Yahoo's API we can get the basic information of any stock and financials of that company looking at things like Cost of Revenue, Total Revenue, Gross Profit, EBITDA etc. 





### Data Cleaning and Preprocessing 
- Some data cleaning that had to be done to the data was column names that had to be renamed, dropping some columns that were uncessary when getting the data from the API.
- Preprocessing included getting the required data into an dataframe, and slicing for the data that I needed.
- An example of data slicing was getting the correct stock ticker symbol that I wanted into my dataframe. 


### Exploratory Data Analysis 
**Microsoft EBITDA**

![image](https://github.com/user-attachments/assets/405730e8-87a1-49e7-84ea-8fb1b7779afd)

- Looking at Microsoft's EBITDA the company is becoming more efficient in its core operations, as it is generating more earnings from its regular business activities before accounting for non-operating costs like interest, taxes, and depreciation.
- Microsoft has heavily invested into R&D and delivering on cloud services, server products and other business processes
- This shows Microsoft's profitability is going up which indicated by the stocks growth over time. 


**Microsoft Revenue Analysis**

![image](https://github.com/user-attachments/assets/6fb82c80-9b9c-4608-92a5-2e4a82b541dc)

- Revenue growth from Microsoft has been high for the company as it has seen growth by billions each year with Azure being a main growth factor in its revenue in the future
- While still maintaining a low cost of revenue that would be beneficial for many companies as it will be expected for cost of revenue to growth with revenue growth
- Microsoft is still in a strong position in the cloud computing market with Azure, Microsoft 365 and Windows in generating revenue. 



**Price-To-Earnings ratio of top tech stocks**
![image](https://github.com/user-attachments/assets/5c67e433-13b7-4eba-9465-301558e4dd55)

- 


**Market Cap of Top Tech Stocks**

![image](https://github.com/user-attachments/assets/30c5b6aa-5d60-45fd-9546-7ea15c47de96)





**A look at Nvidia's Growth**

![image](https://github.com/user-attachments/assets/4d615d68-b206-4f99-8a91-d5fbbb684134)


**Nvidia's 10-day Moving Average Price**

![image](https://github.com/user-attachments/assets/e51bc080-d304-41b6-bd9a-adf229cdfc3a)






### Conclusion & Future Expansion

