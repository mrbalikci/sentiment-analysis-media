## sentiments-Analysis for BBC, CBS, CNN, FoxNews, and New York Times. 

# Background  

Twitter has become a wildly sprawling jungle of information. Somewhere between 350 million and 500 million tweets are estimated to be sent out _per day_. With such an explosion of data, on Twitter and elsewhere, it becomes more important than ever to tame it in some way, to concisely capture the essence of the data.

* Observations for analysis is at the bottom of this page. 

# News Mood

Python script to perform a sentiment analysis of the Twitter activity of various news outlets, and to present the findings visually.

The final output provides a visualized summary of the sentiments expressed in Tweets sent out by the following news organizations: BBC, CBS, CNN, Fox, and New York Times


The first plot will be and/or feature the following:

* Be a scatter plot of sentiments of the last 100 tweets sent out by each news organization, ranging from -1.0 to 1.0, where a score of 0 expresses a neutral sentiment, -1 the most negative sentiment possible, and +1 the most positive sentiment possible.
* Each plot point will reflect the _compound_ sentiment of a tweet.
* Sort each plot point by its relative timestamp.

The second plot will be a bar plot visualizing the _overall_ sentiments of the last 100 tweets from each organization. For this plot, aggregated the compound sentiments analyzed by VADER.

The tools used for this challenge are tweepy, pandas, matplotlib, and VADER.

# The final Jupyter notebook must:

* Pull last 100 tweets from each outlet.
* Perform a sentiment analysis with the compound, positive, neutral, and negative scoring for each tweet.
* Pull into a DataFrame the tweet's source account, its text, its date, and its compound, positive, neutral, and negative sentiment scores.
* Export the data in the DataFrame into a CSV file.
* Save PNG images for each plot.

# Observations
* Sentiments Analysis of tweets of News Outlets depend on the moment of the tweets. 
* Based on the analysis which was done on 12-02-2017 at 10:48 AM; BBC, CBS has most positive moods. Fox News has the most negative mood. CNN seems most neutral and NYT is close to CNN. 