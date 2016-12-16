# beer-reco

It is always fun to try new beers and we look for recommendations when are out to try a new variety. This tiny project is an attempt to use some reviews (~1.5 Million) of various microbrews across the world collected from www.beeradvocate.com and generate some good recommendations based on alcohol value, aroma/taste/body etc., using Python and Machine Learning

## Collection of Notebooks 
beer-reco repository has a  bunch of python notebooks (.ipynb) that explain the flow of thought and answer few questions by ranking beers based on a feature and also generate some recommendations.

## 1. beer-reco-abv.ipynb
Ranks beers based on alcohol % by volume and lists the top 10

## 2. beer-recommendation-reviews.ipynb
One approach is to use simple sorting and ranking of statistical means of overall reviews for all beers to recommend the top few.

The other approach is to build a regression model similar to content-based recommender system and generate a parameter matrix for an average user. Given a new beer with an overall rating, we can guess the aroma/taste/body/palate of the beer or vice-versa.

## 3. feature-selection.ipynb
This notebook outlines the methods to identify the important feature among the few selected that is important in determining the overall rating for a beer. This is a simple yet powerful method to identify important features and discard features that doesn't have a significant contribution to the overall trend in the data.

## 4. beerstyle-classification.ipynb
Here we classify the beerstyles based on the features and develop a recommendation system for a user depending on his choice of features..for example, aroma and palate
