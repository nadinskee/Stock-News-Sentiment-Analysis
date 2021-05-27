# Stock News Sentiment Analysis and Visualization
This code analyzes sentiment of news articles of stocks on FinViz. The following tools were used:
- BeautifulSoup for parsing Article Data
- NLTK for Sentiment Analysis. The Vader tool was used to assign polarity scores to the words found in the headlines.
- MatPlotLib for Data Visualization for findings.

# How to Run
To run, simply type "python3 Stock News Sentiment Analysis.py" on Terminal. The code currently analyzes Amazon, FB and AMD but you may edit file accordingly to analyze other stocks.
I'd like to note that this program only analyzes headlines and only for the dates that have news available on Finviz.

Sample Output:
![Analysis of Amazon, FB and AMD Stocks](https://i.ibb.co/JC9WDdD/Figure-2.png)

# Points for Improvement
Would be nice to create a dashboard which would include price history and forecast as well as a wordcloud of the headlines to further reflect the market sentiment. 
