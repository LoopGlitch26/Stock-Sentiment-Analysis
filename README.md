# Project Title: Sentiment Analysis of Stock News Headlines using Natural Language Processing

This project involves conducting sentiment analysis on news headlines for technology companies using the Python programming language. The sentiment analysis is based on the headlines of news articles from the website Finviz, which provides news articles for a range of different companies. In this project, we have selected the following technology companies: Apple (AAPL), Google (GOOG), Microsoft (MSFT), Amazon (AMZN), and Tesla (TSLA).

The project uses several Python libraries, including beautifulsoup4, nltk, pandas, numpy, matplotlib, seaborn, and wordcloud. We begin by importing these libraries and downloading the required datasets using the nltk library.

The first step in the project is to scrape the news headlines for the selected technology companies from the Finviz website. We extract the headlines for each ticker using Beautiful Soup and store the data in a Pandas DataFrame. We also convert the date column to a datetime object for easier manipulation and analysis.

We then use the SentimentIntensityAnalyzer from the nltk library to calculate the sentiment score for each headline. The sentiment score is a value between -1 and 1, where -1 indicates a negative sentiment, 0 indicates a neutral sentiment, and 1 indicates a positive sentiment. We calculate the average sentiment score for each day and normalize the scores to a standard scale using the mean and standard deviation.

Next, we use the seaborn and matplotlib libraries to visualize the normalized sentiment scores for each ticker that shows the trend in sentiment over time using line charts, heatmaps and bar charts. 

Finally, we generate a WordCloud for each ticker using the wordcloud library. The WordCloud provides a visual representation of the most frequently occurring words in the news headlines for each company.

# Key Results

![image](https://user-images.githubusercontent.com/53336715/224939456-b1af3ebb-c9a6-4018-b6d7-58b74aae77ae.png)
![image](https://user-images.githubusercontent.com/53336715/224939820-933d7bda-1a4d-436e-a03b-48faee1a07be.png)
![image](https://user-images.githubusercontent.com/53336715/224940110-24785698-13ad-43da-aec8-f310e849d398.png)

