1. event-statistics.txt
- This file contains the basic statistics of the data set, e.g. event topic categories, number of events in each topic category, number of tweets in each topic category.

2. event-data:
- This folder contains some samples of the event data set.
- In this fodler, the file name is also the event topic name. Each file contain a list of events. The content format: a new event start with symbol "$$$$". The line starting with "$$$$" is the summary of the event, and the lines following this line are soem sample tweets in this event cluster.

- To make the data set complete, we are going to provide tweet text, instead of tweet id.  The reason is that some of the       tweets are not available from Twitter anymore and retrieving them by id from Twitter platform will return nothing, because     they were already deleted by their authors or Twitter.  We are in the process of getting approval from Twitter for making     all the tweet texts available to public. We expect we will get the approval and publish the data set by April, 2020. If not, we will release the tweets by their ids.
3.  code will be available to the public soon.

