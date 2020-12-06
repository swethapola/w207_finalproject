This is where Swetha, Akaash, and Katie will work on their Fall 2020 w207 project. 

In this project, we seek to investigate the relationship between expressed sentiments on twitter and mobility data.

Data Processing Steps. Each step must be done in order due to dependencies:

- Run tweet_ids.ipynb to produce tweets ready for hydrating. Outputs to 'clean_data' folder.
- Hydrate tweets using twarc (need to add in this notebook name). Outputs to 'slightly_cleaned_tweets.csv'
- Run tweet_location on previous output to get the State & County for each tweet. Outputs to 'california_tweets.csv'
- Run tweet_sentiment to grab the sentiment scores from raw data and filter down to tweets of interest. Outputs to 'sentiment_scores.csv'
- Run tweet_mobility to attach mobility data. Outputs to 'mobility_data.csv'
- Run 'tweet_featurization' to featurize of tweets. Outputs all above information into one csv.
- Run 'model_building' to build the model.

