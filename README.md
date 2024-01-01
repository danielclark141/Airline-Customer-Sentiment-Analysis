# Customer Sentiment Analysis: British Airways
Customer sentiment plays a pivotal role in the success of any modern business. However, deciphering customer sentiment requires sophisticated tools. In this in-depth exploratory analysis, I delve into airline customer review data for British Airways sourced from Kaggle.com. The goal is to interpret, clean, and transform raw data into actionable insights, ultimately aiming to enhance customer relations and retention.

## Project Overview
This comprehensive analysis covers a diverse array of customer experiences and focuses on transforming those experiences into valuable insights for improving the customer experience. This project spans across 3,500 distinct reviews with a main goal of identifying areas of focus that British Airways could work to improve customer relations.

## Tools and Methodology
For this project, I leverage Python's Pandas library for data manipulation and analysis. The sentiment analysis is conducted using Vader, a natural language processor, to gauge the positive and negative polarity of each customer review. Additionally, scipy is employed for correlation testing and confidence interval analysis. To enhance the geographical context, airport code data is transformed into locations through web scraping from NationsOnline.org. To further enhance the dataset, I imported geocode data to create additional dimensions for more comprehensive analysis in the future.

## Key Insights
Through data exploration, I learned a lot of valuable information that can be used to form a cohesive strategy for British Airways to implement changes that will create value for its patrons. I have broken down some of these insights into a list below for ease of readability.

1. The average rating is negative with a score of 4.8.
2. The average sentiment of reviews is slightly positive at 0.17.
   - This appears to be skewed towards the positive due to the complexity of natural language processing
4. Ratings and customer sentiment have moderate correlation.
5. Customer sentiment is more negative for layover flights than direct flights.
6. Customers in Economy Class have the lowest distribution of sentiment scores while customers traveling in first class have the highest distribution of sentiment scores.
7. Customers traveling for business purposes have the lowest distribution of sentiment scores while customers traveling for solo leisure purposes have the highest distribution of sentiment scores.

[Click here to view the full analysis](https://github.com/danielclark141/Airline-Customer-Sentiment-Analysis/blob/main/Airline-Customer-Sentiment-Analysis.ipynb)

[Click here to view the Kaggle dataset](https://www.kaggle.com/code/manishkumar7432698/airline-passanger-choice-eda)
