This readme file was generated on 2022-12-14
 
# GENERAL INFORMATION
Title of Project: Drag Race Philippines Sentiment Analysis
 
## Contributors:
- Gozon, Jean Pauline
- Jamias, Gillian Nicole
- Reyes, Anton Gabriel
 
Date of data collection: 2022-10-10

Geographic location of data collection: Philippines, Nationwide
 
 
# DATA AND FILE OVERVIEW
## File List:
DRPH_Tweets_Phase 0 - Contains the code that retrieves and saves the Tweets in a dataframe.

DRPH_Tweets_Phase 1 - Contains the dataset description, cleaning, and EDA.

DRPH_Tweets_Phase 2 - Containts the pre-processing, sentiment analysis, and statistical inferences and charts as well. 

MS_Cleaned - Cleaned Marina Summers dataset after Phase 1

MS7 - Raw dataset after retreiving Tweets with the Twitter API for Marina Summers worth 7 days

PPN_Cleaned - Cleaned Precious Paula Nicole dataset after Phase 1

PPN7 - Raw dataset after retreiving Tweets with the Twitter API for Precious Paula Nicole worth 7 days
 
# METHODOLOGICAL INFORMATION
Desctiption of methods used for collection of data: Using the Twitter Developer API, Tweets were retrieved using the Tweepy Library. https://docs.tweepy.org/en/stable/api.html

Methods for processing the data: The data was processed by looking at the dataset on any inconsistencies and making cleaning it in order to be useable. The group went for looking at certain characters that could potentially affect the workflow and cleaning. For the emoji and text sentiment analysis, new dataframes were created for more flexibility without affecting the main dataframes.

Instrument- or software-specific information needed to interpret the data:
	pandas
	numpy
	datetime
	seaborn
	matplotlib
	re
	collections
	spacy
	wordcloud
	nltk
	tweepy
