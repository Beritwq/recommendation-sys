## RECOMMENDATION SYSTEM
### BUSINESS OVERVIEW
This project is aimed at providing personalized suggestions to movie-lovers based on their previously watched movies. 
The model is able to reduce a user’s time in searching for movies by recommending to them top five movies.

#### The objectives include:
* To understand user-movie viewership and movie-viewership and ratings.
* To predict ratings for unwatched movies.
* To recommend unwatched movies from the predicting model.

![hcu7qaSdVdgm6](https://github.com/Beritwq/recommendation-sys/assets/69270616/d878a6f1-eefb-497a-8cae-5c11954b8c33)

The data used to create the model consisted of information about movies and how users rated the movies they watched.

The picture below shows the top 5 most watched movies.

![2023-09-16 (3)](https://github.com/Beritwq/recommendation-sys/assets/69270616/9ba166ff-5514-4baa-83f8-719801a07024)


The best model was Singular Value Decomposition(SVD) as it gave the least RMSE metric of 0.87.

In comparision to the other model SVD’s prediction weremore accurate with the least error distance between theactual ratings and predicted ratings.

A recommender function was built that takes in a user’s id, the rating data and movie data.

It returns the top 5 movies suggested to the specific user based on the models prediction of the movies they have not watched.

Below is a case example of the recommender function

![2023-09-16 (4)](https://github.com/Beritwq/recommendation-sys/assets/69270616/94a6c66e-3af3-4aeb-ae23-43fd98e2abea)

The recommendation system is a simple tool that isn't based on a cold-start scenario but relies on the assumption that the user has watched and rated movies before.
