There are 8 Jupyter notebooks used for data scraping and analysis –

1.	Group_13_Amazon_BestSeller_Regression_Analysis.ipynb

In this notebook, the idea is to scrape product details from Amazon bestseller - Women - Clothing - Hoodies and Jeans page as a sample to understand what is selling the most on Amazon. We also use Product_rating as y variable for our regression and try to understand the effect of different colors/materials on the rating.

Selenium has been used for data scraping. The notebook can be run without any changes required to the codes.

2.	Group_13_Google_Trends_Analysis.ipynb

The idea is to understand what is trending on Google and what are people searching for as this would provide some insight on current trends. The starting point has been some categories available on GAP websites.
Pytrends has been used to get google trending keywords.

Requirements – pip install pytrends

3.	Group_13_GAP_Old_Navy_Banana_republic_Price_Comparisons

This notebook uses selenium to scrape product data such as name and price from the official websites in order to compare. 
Box plot is used to visualize differences in the pricing

Requirements - !pip3 install plotly

4.	Group_13_Reddit_sentiment_analysis.ipynb

Requirements - pip install praw

reddit = praw.Reddit(
    client_id='',
    client_secret='',
    user_agent='BrandGapScraper',)


Needs Reddit developed account, client id and client secret to scrape data using Reddit API.
Uses Reddit API to scrape from subreddits.




5.	Group_13_Website_Reviews_Sentiment_Analysis

In this notebook, we scrape product reviews from the official websites of GAP, Old Navy and Macy’s.

Selenium has been used for data scraping. The notebook can be run without any changes required to the codes.


6.	Group_13_Fashion_Forecasters.ipynb

This scrapes information from trend predicting websites to identify what tools and services they offer for data driven creative processes in the fashion industry. The notebook can be run without any changes required to the codes.

7.	Group_13_GAP_Financial_Data

This notebook scrapes information from the 10k reports about netsales, stocks, revenue profit from 2000-2023. The notebook can be run directly.

8.	Group_13_AE_Financials.ipynb

This notebook scrapes information from the 10k reports of American Eagle (competitor) about netsales, stocks, revenue profit from 2000-2023. The notebook can be run directly.

![image](https://github.com/akanksha-2797/New/assets/147669111/93bd0e4c-bde1-4145-b4cd-d8c1d395d078)
