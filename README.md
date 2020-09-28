# twitter-sentiment-analysis
The model takes a certain number of tweets and a keyword both specified by user then checks for the sentiment in those tweets. <br/>

Libraries used: TextBlob (for polarity of a tweet), tweepy (getting the tweets from twitter api),
matplotlib (plotting the graph of positive,negative,neutral tweets), re (regular expression)<br/>
For each tweet, polarity is calculated and tweet is classified into one of these:<br/>
1. positive<br/>
2. negative<br/>
3. weak_positive<br/>
4. strong_positive<br/>
5. weak_negative<br/>
6. strong_negative<br/>
7. neutral <br/>

Finally we calculate the percentage of each polarity and print them on graph.<br/>

![image](https://user-images.githubusercontent.com/71806907/94445098-acd83380-01c4-11eb-946d-ee97d9d8f306.png)
![image](https://user-images.githubusercontent.com/71806907/94445218-d09b7980-01c4-11eb-99d4-e048b50509d1.png)
