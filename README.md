# beer-reco

It is always fun to try new beers and we look for recommendations when are out to try a new variety. This tiny project is an attempt to use some reviews (~1.5 Million) of various microbrews across the world collected from www.beeradvocate.com and generate some good recommendations based on alcohol value, aroma/taste/body etc., using Python and Machine Learning

I tried to answer the questions in this blog:
## http://tcbanalytics.com/blog/testing-data-skills.html#.WFWApHeZOb-

## Collection of Notebooks 
beer-reco repository is a collection of jupyter notebooks (.ipynb) that explain the flow of thought and answer few questions by ranking beers based on a feature and also generate some recommendations.

## 1. beer-reviews_analysis.ipynb
Basic statistics of beer reviews analysis. Answers questions 1, 2 and 3 in the blog above

## 2. beer-recommender system.ipynb
Answers question  2 in the above blog using a different approach. Build a regression model similar to content-based recommender system and generate a parameter matrix for a user. Based on his ratings for some beers, compute the preferences of that particular user and recommend few more beers to that user which I think are most relevant based on this data.

## 3. beerstyle-classification.ipynb (coming soon..) Answer to question 4.
Here we classify the beerstyles based on the features and develop a recommendation system for a user depending on his choice of features..for example, aroma and palate
