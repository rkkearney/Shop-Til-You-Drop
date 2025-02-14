# Shop-Til-You-Drop
Social Sensing and Cyber-Physical Systems - Semester Project

This project focuses on analyzing the health of three public companies in the Consumer Discretionary sector, specifically the Textiles, Apparel, & Luxury Goods industry.  These three companies are Burberry (BRBY), LuluLemon Athletica (LULU), and Urban Outfitters (URBN). We use three different sentiment analysis tools (Vader, TextBlob, and Twinword) to analyze Twitter posts related to these companies. We also take into consideration the number of tweets about the company on a given day, the number of followers for a user who has written a particular tweet, and the number of retweets and favorites for that tweet. Using Ordinary Least Squares Regression and Random Forest predictive models, we are able to predict the company’s stock price.

*All code in this repository should be run using python3. Many of the scripts rely on the filesystem setup exhibited in the repository. We used the following libraries in building this project: numpy, pandas, matplotlib, json, requests, sklearn, statsmodels, tweepy, vaderSentiment, textblob, and yahoo_finance. 
