# Rank_Based-Knowledge_Based-Recommendations

We have a single task. The task is that no matter the user, we need to provide a list of the recommendations based on simply the most popular items.

We will consider what is "most popular" based on the following criteria:

* A movie with the highest average rating is considered best
* With ties, movies that have more ratings are better
* A movie must have a minimum of 5 ratings to be considered among the best movies
* If movies are tied in their average rating and number of ratings, the ranking is determined by the movie that is the most recent rating

With these criteria, the goal for this notebook is to take a **user_id** and provide back the **n_top** recommendations.  Use the function below as the scaffolding that will be used for all the future recommendations as well.

to download the data : https://drive.google.com/drive/folders/1e2j6lg-kTKbML3n7_p6U9DgBvaLb5W8h?usp=sharing
