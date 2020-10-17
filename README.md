# Covid_tweets_analysis

In this project, I wanted to explore how people feel at the "beginning" of the pandemic. I want to do that, in order to compare the feeling of people at the beginning of the pandemic and now after more than 6 months. I think it could be a very interesting study. Therefore, in this repo, I decided to analyze tweets about Covid between the end of February and March 2020. I will do the same thing with tweets between September and October 2020 soon.
* Text preprocessing: removed https link, removed punctuations, lowered the text, removed stopwords.
* Performed a sentiment analysis of the different tweets.
* Looked at the most common words (N_grams).
* Checked the most popular hashtags.
* Used sentiment polarity in order to find out how people feel regarding the pandemic.
* **Tools used**: pandas, numpy, nltk, scikit-learn, matplotlib, seaborn

## Results

Three things stricked me the most:
* The most impressive thing is that there are more positive tweets than negative ones. In my opinion, this is a really good thing, and that explains the general positive good vibe during the quarantine period. It will be interesting to check if in September, there are still more positive tweets. I do not think it will be the case, since people are more and more annoyed by the situation.
* Secondly, if I had to summarize the most popular topics in only two categories, I would say: stores & supermarkets (food ...), people (employers, workers). This is cool to see that many people are worrying about people that still has top go to work outside during quarantine.
* Finally, the most popular hashtags are: Donald Trump, Tesco, Amazon, Boris Johnson and Youtube. 

## About the Data

Tweets have been pulled from Twitter. It contains approximately 3700 tweets that have been classified manually. Apart from the Original tweets, the dataset contains information about the Location and the tweet date. One import thing to note is that the tweets are between February to March 2020. I decided to use this old dataset because I want to compare at the "beginning" of the pandemic and now after more than 6 months. I will do this second analysis soon.

## Data visualization

![alt text](https://github.com/gaetanlop/Covid_tweets_analysis/blob/main/bi_grams_tweets.PNG)
![alt text](https://github.com/gaetanlop/Covid_tweets_analysis/blob/main/wordcloud%20tweets.PNG)
![alt text](https://github.com/gaetanlop/Covid_tweets_analysis/blob/main/classes_tweets.PNG)

## Code and Resources Used

**Python Version:** 3.7

**Link of the dataset:** https://www.kaggle.com/datatattle/covid-19-nlp-text-classification

**Interesting notebook:** https://www.kaggle.com/satanizer/covid-19-tweets-analysis
