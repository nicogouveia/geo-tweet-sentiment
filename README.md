# geo-tweet-sentiment
Final Project for GEOG490: Geospatial Data Science Applications
 
Will be focused on mapping sentiment of different topics in within cities using geotagged tweets 🤳👍🗺⚖️🔍
______________________________________

## Analysing sentiment about different topics by city

   
### Nico Gouveia

For this project I wanted to see which cities have positive impressions of something based on twitter data. This would be useful for numerous applications but would mostly likely be used for exploratory research on developing trends. 

In this project I query tweets using Twitter's developer API, the Tweepy package, and the SNScrapper package. I use folium to plot my results. For data manipulation and analysis, I use Pandas, TextBlob, and Natural Language Toolkit. I am in the process of incorporating Pytorch and the huggingface transformers package in order to improve my sentiment analysis results. I may use NLTK's VADER tool in the future.

I split my project into three sections - querying relevant tweets and preparing them for analysis, analyzing them (performing sentiment analysis) and finally plotting them or representing this information in an appealing way.

I expect this project to have some geographical correlation with opinion of different topics related to demographic data but I'm not sure what the extent or scale of this correlation will be. My project is versatile so I can swap out locations or topics in order to find something interesting. 

In the future I hope to improve my tweet sourcing once the SCScrapper package bugs are fixed. I would also like to improve the sentiment analysis portion of my project. Once those are improved it might make sense to replace the default folium markers with something that has more versatile display options.

---
References:

Initially tried to use twitter API and Tweepy
https://towardsdatascience.com/tweepy-for-beginners-24baf21f2c25 

Tweet scraping based off this:
https://medium.com/swlh/how-to-scrape-tweets-by-location-in-python-using-snscrape-8c870fa6ec25

Sentiment analysis and preprocessing based off this:
https://www.youtube.com/watch?v=_EgqxIoUE7U

General guidance from:
https://github.com/MartinBeckUT/TwitterScraper/blob/master/snscrape/python-wrapper/snscrape-python-wrapper.ipynb 
https://medium.com/dataseries/how-to-scrape-millions-of-tweets-using-snscrape-195ee3594721
Tweepy Documentation
Folium Documentation