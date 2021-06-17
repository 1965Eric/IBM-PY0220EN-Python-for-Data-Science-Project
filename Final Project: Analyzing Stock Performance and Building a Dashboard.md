# Project Overview

For this project, you will assume the role of a Data Scientist / Data Analyst working for a new startup investment firm that helps customers invest their money in stocks. Your job is to extract financial data like historical share price and quarterly revenue reportings from various sources using Python libraries and webscraping on popular stocks. After collecting this data you will visualize it in a dashboard to identify patterns or trends. The stocks we will work with are Tesla, Amazon, AMD, and GameStop.

**Dashboard Analytics Displayed**

A dashboard often provides a view of key performance indicators in a clear way. Analyzing a data set and extracting key performance indicators will be practiced. Prompts will be used to support learning in accessing and displaying data in dashboards. Learning how to display key performance indicators on a dashboard will be included in this assignment. We will be using Plotly in this course for data visualization and is not a requirement to take this course.

**Watson Studio**

In the Python for Data Science, AI and Development course you utilized Skills Network Labs for hands-on labs.

For this project you will use Skills Network Labs and Watson Studio. Skills Network Labs is a sandbox environment for learning and completing labs in courses. Whereas Watson Studio, a component of IBM Cloud Pak for Data, is a suite of tools and a collaborative environment for data scientists, data analysts, AI and machine learning engineers and domain experts to develop and deploy your projects.

**Review criteria**

There are two hands-on labs on Extracting Stock Data and one assignment to complete. You will be judged by completing two quizzes and one peer review assignment. The quizzes will test you based on the output of the hands-on labs. In the peer review assignment you will share and take screen shots of the outcomes of your assignment.

## Reading: Stock Shares

A company's [stock](https://www.investopedia.com/terms/s/stock.asp) share is a piece of the company; more precisely:

*A stock (also known as equity) is a security that represents the ownership of a fraction of a [corporation](https://www.investopedia.com/terms/c/corporation.asp). This entitles the owner of the stock to a proportion of the corporation's [assets](https://www.investopedia.com/terms/c/core-assets.asp) and profits equal to how much stock they own. Units of stock are called "shares."

An investor can buy a stock and sell it later. If the stock price increases, the investor profits, If it decreases, the investor with incur a loss.  Determining the stock price is complex; it depends on the number of outstanding shares, the size of the company's future profits, and much more. People trade stocks throughout the day. The **stock ticker** is a report of the price of a certain stock, updated continuously throughout the trading session by the various **stock** market exchanges. In this lab, you will use the y-finance API to obtain the stock ticker and extract information about the stock. You will then be asked questions about your results.

[Extracting Stock Data Using a Python Library](https://github.com/1965Eric/IBM-PY0220EN-Python-for-Data-Science-Project/blob/main/Final_Assignment_Extracting_Stock_Data_Using_a_Python_Library.ipynb)

## Graded Quiz: Extracting Stock Data Using a Python Library

Question 1: From the lab exercise, in which country is AMD (Advanced Micro Devices) situated?

- A. [ ] China
- B. [X] United States
- C. [ ] Canada

Question 2: In the lab exercise, to which sector does AMD (Advanced Micro Devices) belong?

- A. [ ] Agriculture
- B. [X] Technology
- C. [ ] Electronics

Question 3: In the lab exercise what is the max of the volume of AMD?

```325058400```

[Extracting Stock Data Using Web Scraping](https://github.com/1965Eric/IBM-PY0220EN-Python-for-Data-Science-Project/blob/main/Final_Assignment_Extracting_Stock_Data_Using_Web_Scraping.ipynb)

## Graded Quiz: Extracting Stock Data Using Web Scraping

Question 1: In the lab exercise, what is the content of the title attribute from the object soup?

- A. [X] ```< title > Amazon.com, Inc. (AMZN) Stock Historical Prices & Data - Yahoo Finance < /title >```
- B. [ ] ```(AMZN) Stock Historical Prices & Data - Yahoo Finance```
- C. [ ] ```< b class="Hidden" > Yahoo Finance < /b >```

Question 2: In the lab exercise, what are the correct names of the columns of the dataframe?

- A. [X] 'Date', 'Open', 'High', 'Low', 'Close', 'Volume', 'Adj Close'
- B. [ ] 'Date', 'Open', 'High', 'Low'
- C. [ ] 'Date', 'Open', 'High', 'Low', 'Close', 'Volume', 'Adj Close', 'max','min'

Question 3: In the lab exercise What is the ```Open``` of ```Jun 01, 2019``` in the dataframe?

- A. [X] ```1,760.01```
- B. [ ] ```1,935.20```
- C. [ ] ```1,672.00```

## Reading: Tesla and GameStop Analytical Dashboard

Determining the price of a stock is complex; It depends on many things like revenue, profits, losses. company news. public perception, future business, and much more. An essential factor is the company's growth of profit/revenue. If the company reports good profits/revenue, the stock price should increase and if it reports bad profits/revenues the stock price will decrease.

Tesla and GameStop have become very popular stocks, with GameStop being one of the fastest rising and popular stocks of the year. Both have seen tremendous gains and for different reasons. In the course project, we will extract revenue and stock price data for Tesla and GameStop and build a dashboard to compare the price of the stock vs the revenue. This dashboard will not only provide information about the revenue and stock price but will allow us to see if there is a correlation between the two.

In order to complete the final project you will need to add this notebook to your Watson Studio project. Copy the link below. You will need to paste it in the next lab:

[https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/Final%20Assignment.ipynb](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-PY0220EN-SkillsNetwork/labs/project/Final%20Assignment.ipynb)

## Final Assignment in Watson Studio

[Final Assignment](https://eu-gb.dataplatform.cloud.ibm.com/analytics/notebooks/v2/72d75f56-74b1-4c28-b8d6-ade633204da8/view?access_token=eb7486624f862a8b877e5b42d6c9f753c00ced608ace8dc02db88cd38e21f74e)


