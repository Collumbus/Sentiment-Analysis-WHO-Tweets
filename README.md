# Sentiment analysis on WHO's tweets using Python (Tweep API, Pandas and TextBlob)

* This is a very simple way to implement Natural Language Processing using the TextBlob lib. Here a Twitter App was created to conduct a Sentiment Analysis of the tweets of the World Health Organization ([@who](https://twitter.com/who)).


> #### DESCRIPTION:
>
>>* Install libs:
>```
>conda install -c conda-forge tweepy wordcloud textblob
>```
>In this repositorie:

>1. Extract twitter data using tweepy and handle it using Pandas.
>2. Do some basic statistics and visualizations with Numpy, Matplotlib, Seaborn and WordCloud.
>3. Do sentiment analysis of extracted (WHO's) tweets using TextBlob.


```
Tweets obtained: 1200.
The first 5 tweets:
The full briefing on #COVID19 by @DrTedros 👇
https://t.co/NqhFrJJTbu

"Only together can we get through the #COVID19 pandemic. In national unity and global solidarity"-@DrTedros

"This new partnership is another great example of solidarity that builds on the solidarity flights, solidarity tria… https://t.co/CqUhjsJq8u

"#COVID19 has exposed the uneven distribution of life-saving medical equipment across the world.

Tomorrow, the Tec… https://t.co/iX4RbfPKZS

"Even relatively short-term interruptions to treatment pose a significant threat to a person’s health and potential… https://t.co/dvVEda2jLw
```

## A Word Cloud with the most frequent words in WHO Tweets


![Brainstorm image](/img/brainstorm.png)

## Relationship of the number of Likes and Retweets


![likes_re_view image](/img/likes_re_view.png)

## Results from the sentiment analysis of Tweets

```
Positive tweets: 43.42%
Neutral tweets: 45.00%
Negative tweets: 11.58%
```
