# Web-Scraping-Moneycontrol-

Here's a web scraping code in python to get stock news headlines from moneycontrol.com. The purpose of the code is to parse data in the form of text. It reads finance news headlines and a small description of the headline. 

All the content is saved in the form of a dictionary in python. This dictionary can be converted into a csv file which can be further downloaded.
This code has a provision to access the website and create a new csv file every 4 hours.

Libraries used are requests to generate http requests, beautifulsoup4 to parse the data, and schedule for time scheduling of website access.

url link: https://www.moneycontrol.com/news/business/stocks/

Code is written in colab for easy access and the csv files generated can be accessed with google drive.

The dataset generated can be used for testing and training models for future predictions.
