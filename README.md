# nlp_sentimentanalysis

## About the dataset

This dataset, named hate_speech_offensive, is a meticulously curated collection of annotated tweets with the specific purpose of detecting hate speech and offensive language. The dataset primarily consists of English tweets and is designed to train machine learning models or algorithms in the task of hate speech detection. It should be noted that the dataset has not been divided into multiple subsets, and only the train split is currently available for use.

The dataset includes several columns that provide valuable information for understanding each tweet's classification. The column count represents the total number of annotations provided for each tweet, whereas hate_speech_count signifies how many annotations classified a particular tweet as hate speech. On the other hand, offensive_language_count indicates the number of annotations categorizing a tweet as containing offensive language. Additionally, neither_count denotes how many annotations identified a tweet as neither hate speech nor offensive language.

For researchers and developers aiming to create effective models or algorithms capable of detecting hate speech and offensive language on Twitter, this comprehensive dataset offers a rich resource for training and evaluation purposes

It consists of annotated tweets with information about their classification as hate speech, offensive language, or neither.
Each row represents a tweet along with the corresponding annotations provided by multiple annotators.
The main columns that will be essential for your analysis are: count (total number of annotations), hate_speech_count (number of annotations classifying a tweet as hate speech), offensive_language_count (number of annotations classifying a tweet as offensive language), neither_count (number of annotations classifying a tweet as neither hate speech nor offensive language).

The data collection methodology used to create this dataset involved obtaining tweets from Twitter's public API using specific search terms related to hate speech and offensive language. These tweets were then manually labeled by multiple annotators who reviewed them for classification purposes.

