# Underrated-Movie-Recommendation-System
Objective - to build a recommender system for underrated movies which will cater to veteran movie enthusiasts


Instead of recommending the usual  shawshank redemption, or the godfather, We intend to recommend movies which are a masterpiece but not that well known 




Data Source: Plot keywords available
https://www.imdb.com/title/tt13327038/keywords?ref_=tt_stry_kw
Genres: 
Movie pages: https://www.imdb.com/title/tt0111161/
-Extract Genre, rating, popularity, release date, reviews(top 10)



Types of analytics to run on the data :
Recommender system

Search performs cosine similarity between plot keywords and release date. 

Condition on popularity, 

Association of reviews with positive words such as: underrated, awesome, 

Expected Outcomes:
Intend to see some movies which have high iMDB rating and lower popularity along with the ones which do not have higher iMDB rating in recommendations
