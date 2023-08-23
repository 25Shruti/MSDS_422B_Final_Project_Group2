# MSDS_422B_Final_Project_Group2

## 1.1 Problem Statement - Overview
### Problem Background
- In today's digital age, streaming platforms offer a vast library of movies to users.
- However, with the sheer volume of available content, users often struggle to discover movies that match their interests.
- A movie recommendation system aims to solve this problem by leveraging user behavior and preferences to provide personalized movie suggestions, enhancing user experience and engagement.

### Objective
The goal of this project is to design and develop an efficient and accurate movie recommendation system that can intelligently suggest movies to users based on their past viewing history, ratings, and the behavior of similar users.

### Scope
As a part of this project, we shall be building recommendations using the following algorithms,

- Overall movie recommendation based on popularity and genre
- Content-based recommendation
- Collaboration-based movie recommendation

## 1.2 Recommendation Algorithm Overview

### Overall Movie recommendations

- This is a Simple Recommender, which offers generalized recommendations to every user based on movie popularity and genre.
- The basic idea behind this recommender is that movies that are more popular and more critically acclaimed will have a higher probability of being liked by the average audience.
- This model does not give personalized recommendations based on the user.

### Content Based Movie Recommendation

- A Content-Based Recommendation System suggests movies to users based on their intrinsic attributes such as genres, actors, and plot details.
- It personalizes recommendations by matching item content to user preferences
- This is achieved by building an engine that computes similarity between movies based on certain metrics and suggests movies that are most similar to a particular movie that a user liked.

### Collaborative Filtering-Based Movie Recommendation

- Collaborative Filtering is a recommendation technique that identifies user preferences by analyzing interactions and behaviors of similar users.
- Collaborative Filtering is based on the idea that users similar to user A, can be used to predict how much user A will like a particular movie, based on their likings and reviews
- This approach offers personalized suggestions and is effective for both known and unknown items


## 1.3 Conclusion & Recommendation

### Overall Recommendation based on IMDB weighted ratings

- Benefits - Can be used as a cold start recommendation baseline, for new users, with a lack of historical data
- Limitations - Unable to provide highly personalized suggestions for new users

### Content-Based Filtering

- Benefits - Improvement over the initial approach, leveraging movie attributes and user profiles to offer more personalized recommendations
- Limitations – Recommendations not customized for individual users

### Collaborative Filtering

- Benefits: Identifies user preferences by analyzing interactions and behaviors of similar users.
- Limitations: SVD & NN are resource intensive and need advanced software frameworks & computational resources


## Recommendation
- As a recommendation, while IMDB's weighted recommendation provides a basic entry point, content-based filtering enhances personalization, and collaborative filtering stands out as a more advanced and versatile approach.

## 1.4 Future Scope of Improvement
- Exploring Hybrid Modeling - Combining Context-based and Collaborative Recommendations
- This can enhance personalization, by considering user preferences beyond their interactions
