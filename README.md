# Udacity Project 4: Data Wrangling Project

In this project, we need to practice the data wrangling process: data gathering, data assessing, and data cleaning. A simple EDA and visualization are supplementary to this project.

The dataset that we will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." WeRateDogs has over 4 million followers and has received international media coverage.

Our goal: Wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing and cleaning is required for "Wow!"-worthy analyses and visualizations.

The following packages (libraries) need to be installed: 
- pandas
- NumPy
- requests
- tweepy
- json

Retweet count and favorite count are two of the notable column omissions. We, because you have the WeRateDogs Twitter archive and specifically the tweet IDs within it, can gather this data for all 5000+. And we're going to query Twitter's API to gather this valuable data.

