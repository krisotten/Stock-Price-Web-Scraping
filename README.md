# Stock Price Web Scraping Project

**In this project, I use pandas and Beautiful Soup to scrape stock price data from Yahoo Finance.**

First, I wrote a function to scrape the page URLs for the top 25 stocks on the "Most Active Stocks Today" page on Yahoo Finance. I put all of these URLs into a list to be used in a second function that retrieves information about each stock. 
<br><br> 
This second function takes in the list of stock URLs then for each URL, scrapes the company name, most recent stock price, most recent stock price change, and the date/time the data was recorded. The function then appends the data to a CSV file. 
<br><br>
I wrote a third function that checks the price of the top 25 stocks for a user entered amount of time at time intervals given by the user. Each time the prices are checked, a new row is added to the CSV file recording the company name, current price, and current price change for each of the top 25 stocks. This allows us to analyze the change in price of the most active stocks over time. 
<br><br>
Finally, I displayed the data of the top 9 most active stocks in a subplot using Matplotlib.
