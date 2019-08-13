---
layout: post
title: "SONG RECOMMENDATION SYSTEM"
author: "Ujwal Sachdeva"
categories: projects
tags: [song-recommendation-system, sample]
image: song-rs.jpg
bgcolor: rgb(97, 88, 130)
---

"Song Recommendation System" is a data science project undertaken as a summer intern at the Indian Statistical Institute, New Delhi Centre.

The project was carefully worked upon and reviewed for a period of two months, under the guidance of Professor S.K. Neogy, Head - ISI, Delhi. Starting in May 2019, it was completed in July 2019.

The language used to create this basic overview is Python, and has been performed on Jupyter Notebooks. 

### RECOMMENDER SYSTEM 
A recommender system employs a statistical analysis algorithm that predicts users' ratings for a particular entity, based on the similarity between the entities or a similarity between the users that previously rated those entities. the concept is that similar types of users are likely to have similar ratings for a set of entities. 

### TYPES OF RECOMMENDER SYSTEM 
#### (I) CONTENT BASED RECOMMENDATION SYSTEM
In content-based filtering, the similarity between different products is calculated on the basis of the attributes of the products. For instance, in a content-based movie recommender system, the similarity between the movies is calculated on the basis of genres, the actors in the movie, the director of the movie, etc.

#### (II) COLLABORATIVE FILTERING 
Collaborative filtering leverages the power of the crowd. The intuition behind collaborative filtering is that if a user A likes products X and Y, and if another user B likes product X, there is a fair bit of chance that he will like the product Y as well.

#### (III) POPULARITY BASED RECOMMENDATION SYSTEM
In this type of recommendation system, the popularity of each data item is taken into account and the most popular items are recommended to subsequent users.
In this project, a popularity based song recommendation system has been taken into account. 

### ABSTRACT
The simple problem taken into consideration while coming up with the idea for this project was the fact that the number of songs available on the internet are practically impossible to filter out without any recommendations. If, on the basis of the song currently being played, or the populairty of recent songs, it increases the chances of a user to listen to a song he/she is more likely to prefer.

The project not only provides recommendations based on the different recommendation models, but also compares them with each other in order to predict the accuracy of each. It performs this task through a quantitative analysis between the models. The statistical analysis at the end provides a "Precision-Recall Curve" - a useful measure of success of prediction when the classes are very imbalanced. In information retrieval, precision is a measure of result relevancy, while recall is a measure of how many truly relevant results are returned.


