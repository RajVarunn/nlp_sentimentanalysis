# nlp_sentimentanalysis

## Problem Statement

In today's digital age, social media platforms are very much popular amongst all age categories. Approximately, 63.9% of the words population (5.24 billion) uses social media platforms with an average user spending roughly 2 hours 21 minutes on it daily. Today, social media platforms have become the primary channel for communication and interactions. However, since 2013 there has been a seady rise on the overall negativity present on the platforms. The main driving force for this rise is due to the hate speech and offensive language remarks present all over social media. These forms of expression can perpetuate discrimination, foster hostility, and negatively impact ones mental well-being. 

Hate speech is generally defined as any communication that attacks or denigrates a person or group based on attributes like race, religion, ethnicity, gender, sexual orientation, or disability. Offensive language, less severe, is defined by words or phrases that can be used in a disrespectful, insulting, or hurtful manner without targeting a particular group. Both are considered as a negative form of message to the opposite party.

The presence of such language leads to several significant issues:
1. User Safety: Hate speech and offensive language create unsafe online spaces, discouraging healthy discussions and making users feel alienated.
2. Platform Reputation: Platforms that fail to address these concerns risk losing user trust and facing scrutiny from regulators.
3. Legal and Ethical Implications: Many countries enforce strict laws against hate speech, requiring platforms to take proactive measures to filter such content.
4. Scalability of Moderation: Given the vast amount of content generated daily, manual moderation is neither practical nor scalable.

Our goal is to build a model which can identify such negative remarks and comments and prevent it from reaching the victim before its too late. This way we can make social media a safe environment for everyone to use and foster healthy relationships between the users.

## About the dataset

The dataset we are using, named hate_speech_offensive, is a meticulously curated collection of annotated tweets with the specific purpose of detecting hate speech and offensive language. The dataset primarily consists of English tweets and is designed to train machine learning models or algorithms in the task of hate speech detection. It should be noted that the dataset has not been divided into multiple subsets, and only the train split is currently available for use.

The dataset includes several columns that provide valuable information for understanding each tweet's classification. The column count represents the total number of annotations provided for each tweet, whereas hate_speech_count signifies how many annotations classified a particular tweet as hate speech. On the other hand, offensive_language_count indicates the number of annotations categorizing a tweet as containing offensive language. Additionally, neither_count denotes how many annotations identified a tweet as neither hate speech nor offensive language.

For researchers and developers aiming to create effective models or algorithms capable of detecting hate speech and offensive language on Twitter, this comprehensive dataset offers a rich resource for training and evaluation purposes

It consists of annotated tweets with information about their classification as hate speech, offensive language, or neither.
Each row represents a tweet along with the corresponding annotations provided by multiple annotators.
The main columns that will be essential for your analysis are: count (total number of annotations), hate_speech_count (number of annotations classifying a tweet as hate speech), offensive_language_count (number of annotations classifying a tweet as offensive language), neither_count (number of annotations classifying a tweet as neither hate speech nor offensive language).

The data collection methodology used to create this dataset involved obtaining tweets from Twitter's public API using specific search terms related to hate speech and offensive language. These tweets were then manually labeled by multiple annotators who reviewed them for classification purposes.

## Project Flow

![telegram-cloud-photo-size-5-6194916586024977483-y](https://github.com/user-attachments/assets/f4da7ca8-fb57-42d9-aa39-b681c69bbbe4)


