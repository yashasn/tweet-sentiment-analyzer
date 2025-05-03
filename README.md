# tweet-sentiment-analyzer
Twitter sentiment analyzer built with Python and TextBlob

- User can select a particular buzzword or a hashtag to query twitter for tweets on it.
- Once the user chooses the word and selects the number of tweets to analyze, the exact number of tweets are extracted and each tweet is analyzed using TextBlob to determine the emotion it exhibits.
- The aggregate sentiment of users towards the selected word is found by looping over all the tweets
and summing the polarities.
