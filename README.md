# Twitter-Data-Analytics

For this project I have access to a collection of Twitter data that is stored in Google Cloud Storage, located in gs://msca-bdp-tweets/final_project.  Once the individual JSON files are combined, there will be ~100 million Tweets (~500GB).  These tweets are collected on the topics of education, schools, universities, learning, knowledge sharing, etc., but only a fraction of them would be directly related to either primary, secondary or higher education.

The main objective is to identify whether Twitter can be considered a credible source of information, which reflects the emergence of important trends or topics in education and whether we can see any spikes in Twitter activity or any shifts in geographical distribution of Twitterers?  (Twitterer is the name given to those who use Twitter).  

• Based on my analysis we can see that more than half of the tweets from the filtered sample were retweets. Post classification of the twitterers into different
categories, we saw an overwhelming majority of tweets from other users. Among the most prolific twitterers, we found News channels
producing the greatest number of original tweets and tweets from other users have been retweeted the most. From this we can infer that
majority of the original message volume can be considered noteworthy given that it is from Twitterers having expertise on educational
topics. However, since a vast majority of the overall tweets are from other unverified users, we can’t quite completely label them as a
credible source of information owing to the noise around. A suggested approach would be to investigate the tweets a degree more by using
topic modelling which can help quantify the degree of credibility of the Twitter data.

• On conducting the geographical analysis, we notice that there is no major relationship between the emergence of new issues in education
and progression and locations of these Twitterers. While investigating tweet content from locations having a higher concentration, we also
notice that areas having highest number of tweets, need not have relevance with the concerned educational topics directly. Perhaps by
performing a more refined classification and summarization of the tweets using latent semantic indexing or implementing the elastic
search, we can produce a more convincing argument regarding Twitter’s credibility.

• While analyzing the timeline of the tweets, we decided to dig into the tweets where we noticed a spike and again stumbled across tweets
from other unverified users, dominating with topics that don’t coincide with the trending topic directly. We also notice that these spikes
coincide only with the academic calendar and a lot less during the summer and winter breaks. Only a certain section of verified users
produce tweets related to the trending topic. However, we might be able to throw more light on the timeline of the tweets on a larger date
range. When we look at tweets created by day of the week, we notice that users in their free time (weekends) tend to tweet less on
education related topics and more on other domains, yet again dipping the credibility of Twitter as a source for education.

• While studying the sample of the tweets for similarity, we notice that the number of duplicates are just fractionally more than the original
ones from a broader perspective and given that a majority of the sample are other unverified users, we see that tweets are more prone to
be copies of original messages. It is only when we categorize the twitterers, we notice that there is a higher ratio of original messages
compared to duplicates compared to the general sample and this ratio is the highest for educational institutions and lowest for other
categories of users. Again, we see that only a minor percentage can be considered truly credible. 
