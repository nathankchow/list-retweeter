Problem: 

I am a fan of a certain anime character (e.g. Keqing from Genshin Impact). I would like to be subscribed to a feed of tweets involving artwork drawn of her, or alternatively be able to search up recently created art of her. One issue is that not all artists include the character's name in their tweet, meaning that searching up a character's name in Twitter search will not return all recently created art of Keqing.

Solution:

We identify other individuals that also enjoy Keqing fanart (i.e. retweet a lot of Keqing art), and follow them so their retweets end up in our own Twitter feed. 

Sample workflow:
1) You already have a twitter account and have liked or retweeted tweets containing artwork of Keqing.
2) Generate a list of tweet IDs
3) Loop over all tweets and count the number of times a specific twitter account retweeted a tweet from that list
4) Display the list of twitter accounts, in order of decreasing retweet count, as well as whether you are already following them or not.
5) Follow everyone you have not followed yet with a high retweet count
6) Enjoy more fanart of your favorite fictional characters!
