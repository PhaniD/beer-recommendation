# beer-reco

It is always fun to try new beers and we look for recommendations when are out to try a new variety. This tiny project is an attempt to use some reviews (~1.5 Million) of various microbrews across the world collected from www.beeradvocate.com and train Machine Learning models to give recommendations based on alcohol value, aroma/taste/body etc., 
Python Data Science Stack and Machine Learning algorithms as implemented in Scikit-learn are used. Also answers the questions in this blog: http://tcbanalytics.com/blog/testing-data-skills.html#.WFWApHeZOb-

## Collection of Notebooks 
beer-reco repository is a collection of jupyter notebooks (.ipynb) that explain the flow of thought and answers few questions in the blog above by ranking beers based on attributes and to generate some recommendations.

## 1. Sorting and Ranking.ipynb
Data Import, basic sorting and ranking of data in Pandas DataFrames and visualization.
Example:
- which brewery produces strongest beers by ABV%?

## 2. General Recommendations.ipynb
Based on the overall reviews from reviewers across the world, another simple strategy is to rank the beers based on overall reviews. This requires a bit more work than simple sorting because of inhomogenieties in the data. All beers are not rated by all reviewers and ratings are distributed around a certain mean value with some strandard deviation.
After the data cleaning step to retain statistically significant values (to predict with 95% confidence interval), reviews can be sorted and ranked to provide general recommendations
Examples:
- Beer or top five beers with best overall review
- Top five beers with best aroma.. etc

## 3.Personalized Recommendations.ipynb 
Personalized recommendations using collaborative filtering. Besides general recommendations, this notebook trains a statistical model using low rank matrix factorization and collaborative filtering. User preferences are collected and the model provides personalized recommendations.

## 4. Beer Rating Prediction.ipynb
Regression models to predict overall rating of a beer based on sample means of aroma, appearance, taste and palate.
Includes cross-validation by splitting training and test data sets using KFold split and averaging the model parameters over all sets. Includes some utility functions and scikit-learn method wrapper class.

## 5. Beer Style Classification.ipynb (Coming Soon)
