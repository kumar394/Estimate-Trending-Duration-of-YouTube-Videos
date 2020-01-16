# Estimate-Trending-Duration-of-YouTube-Videos
Built a multivariate linear regression model to predict trending duration of a video on YouTube based on feature engineering, A/B testing and sentiment score generated from user comments (https://www.youtube.com/watch?v=oPr8Sx9L9Mg)

YouTube trending video analysis

Pre-requisites
1. Download UScomments.csv file
2. Install wordcloud, nltk and vaderSentiment libraries in python

Steps to estimate the sentiment score for each video
1. Change the path of csv file to the exact path of UScomments.csv file
2. Run the Web_Data_Text_Analytics.ipynb file in Jupyter notebook or any other IDE.  
3. Provide the name and path where you want to store your final sentiments score file.
4. Average the sentiment scores for each video in the newly generated csv file.
5. Use excel Vlookup to add the sentiment score of each video in a new column called sentiment_score in USvideos.csv file. 

Regression Analysis
1. Calculated trending duration for each video
2. Subsetted day1 data of each video
3. Created new variables – like to view ratio, dislike to view ratio, comment to view ratio
3. Exploratory Data Analysis of predictor variables
4. Logarithmic transformation of skewed variables  
5. Capping and Flooring of outliers
6. Standardized input variables
7. Generated regression model through Minitab
8. Inference from the results
