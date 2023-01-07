# 2022 FIFA World Cup Qatar - Twitter Analysis

Analysis of public opinion on the World Cup, its controversies, 
and the use of the popularity of the event by other groups to advertise or publicise other issues.

## Authors

Jan Fiszer - fiszer@student.agh.edu.pl <br />
Konrad Pawlik - konradpawlik@student.agh.edu.pl

## Prerequisition

- Python 3
- numpy
- pandas
- tweepy
- nltk
- demoji
- matplotlib
- wordcloud
- networkx
- nrclex
- vaderSentiment

## Source Code

1. collect_data.ipynb
2. preprocessing.ipynb
3. exploratory_data_analysis.ipynb
4. social_network_analysis.ipynb
5. hashtag_usage_through_time.ipynb
6. social_content_analysis.ipynb

Disclaimer: Both social network and content analysis were conducted in parallel,
so the associated notebooks should not be run one after the other, but at the same time.

## Data

* data
  * tweets.csv
  * users.csv

Collected data is split into two datasets - tweets.csv and users.csv, which, as the names suggest,
respectively contain data on tweets and the users associated with them.

Due to limitations, data can be downloaded from https://drive.google.com/drive/folders/1ujaePKHniGevIWcc4Pv1kLCYXKdTRGZI?usp=share_link