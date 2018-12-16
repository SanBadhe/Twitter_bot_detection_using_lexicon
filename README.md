# Twitter_bot_detection_using_lexicon
We are trying to build twitter bot detection model using sentiment analysis.
Currently model worked on account level bot detection using adaboost, Random Forest, DecisionTree and Logistic Regression Classifier.
But we are in the process of tweet level detection using recurrent neural network and LSTM.

## Data
We used data from botometer(Link is provided below). Downloaded 2000 tweets for each 10K bots and 10K not bots. 
https://botometer.iuni.iu.edu/bot-repository/datasets.html

## Feature engineering
a) Followers/Friends ratio

b) Tweets/day

c) Length of name

d) Length of screenname

e) Length of description

f) Number of words in name

g) Is their “bot” word in the name, description or screenname

h) Lexical diversity of description

i) In_Reply/tweet_downloaded

j) retweet_count/tweet_downloaded

k) fav_count/tweet_downloaded)

l) total_usermention/Tweet_downloaded

m)  Variance in tweet rate

n) Number of nodes in network

o) Number of edges in network
 
 Apart from this we genrated avrage of eight emotion and two sentiment for each account.
 
 ## Model building
 1) Decision Tree
 
 2) Logistics Regression
 
 3) Random Forest 
 
 4) Adaboost

