# Twitter-Trend-Analysis

The idea behind this project is to find what is trending on Twitter. Once found, a **WorldCloud** can be created which will easily help in easy visualization of the analysis performed. 

### Packages used
1. twitteR - Provides an API to fetch tweets from Twitter.
2. wordcloud - To create a wordcloud of the analysis performed.
3. tm - A package that provides funtions to convert UTF-8 to ASCII. 
4. Other packages used - RColorBrewer, e1071

### Steps Performed
1. Connect to twitter.
2. Fetch the tweets.
3. Perform data cleaning on tweets. Extract text from tweets.
4. Create a corpus of data and convert it to a Term-Document matrix.
5. Get the wordcount for every word in all the tweets to find what is more trending. 
6. Create a WordCloud.
