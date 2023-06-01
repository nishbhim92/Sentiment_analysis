# Sentiment_analysis
This R script performs sentiment analysis on a collection of tweets using several popular sentiment analysis libraries and dictionaries in R.
## Installation
[tm](https://cran.r-project.org/web/packages/tm/index.html)
[syuzhet](https://cran.r-project.org/web/packages/syuzhet/index.html)
[sentimentr ](https://cran.r-project.org/web/packages/sentimentr/index.html)
## File Descriptions
sentiment_analysis.R: This is the main file where the sentiment analysis is performed.
## Data
The dataset is a CSV file ('ABCXYZ.csv') with a column 'text' containing the tweets to be analyzed.
## How to Run
You can run the sentiment_analysis.R script in R or RStudio.
## Code Overview
The script performs the following steps:

* Set the working directory and load the data from a CSV file.
* Preprocess the tweets by converting to lowercase, removing stop words, punctuation, URLs, non-ASCII characters, and certain specified words, and stripping whitespace.
* Perform sentiment analysis using four different sentiment dictionaries: syuzhet, afinn, bing, and nrc.
* Calculate the average sentiment positivity rating for each dictionary and print the scores.
* Calculate the average presence of eight different emotions (anger, anticipation, disgust, fear, joy, sadness, surprise, trust, positive, and negative) in the tweets.
* Perform sentiment analysis using the sentimentr package and calculate the average sentiment score.
* Save all sentiment and emotion scores in a dataframe and copy to clipboard for pasting into Excel.
## Result
The result of the script is a set of sentiment scores for the tweets, providing multiple perspectives on the overall sentiment of the tweet collection.
