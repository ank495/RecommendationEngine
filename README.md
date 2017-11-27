# RecommendationEngine


1. Provide a data set to the Recommendation Engine


2.All the users have same recommendation based on the most popular choices. We’ll use the  graphlab recommender functions popularity_recommender for this.



3.Lets start by understanding the basics of a collaborative filtering algorithm. The core idea works in 2 steps:
Find similar items by using a similarity metric
For a user, recommend the items most similar to the items (s)he already likes
To give you a high level overview, this is done by making an item-item matrix in which we keep a record of the pair of items which were rated together.


4.For evaluating recommendation engines, we can use the concept of precision-recall. You must be familiar with this in terms of classification and the idea is very similar. Let me define them in terms of recommendations.



Provide data to the python file and python file will train and then give the recommendation.
