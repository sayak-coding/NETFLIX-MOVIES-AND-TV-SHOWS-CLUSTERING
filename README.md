# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING
Problem Statement:
This dataset consists of tv shows and movies on Netflix as of 2019. The dataset is
collected from Flexible which is a third-party Netflix search engine. In 2018, they released
an interesting report which shows that the number of TV shows on Netflix has nearly
tripled since 2010. The streaming service's number of movies has decreased by more
than 2,000 titles since 2010, while its number of TV shows has almost tripled. It will be
interesting to explore what all other insights can be obtained from the same dataset.
Goal:
This project aims to find similarities within groups of people to build a movie
recommendation system for users. We are going to analyze a dataset from the Netflix
database to explore the characteristics that people share in movies. We have
experienced it ourselves in the room, the endless scrolling of selecting what to watch.
Users spend more time deciding what to watch than watching their movies
Solution Approach:
After importing the data set initially, we did data preprocessing, handling NAN values and
outliers detections. Then we did some Exploratory Data Analysis. In EDA, we check how
many types of content are present on Netflix, in which year and month the maximum
number of content is released, and the count of content on the basis of genre and
ratings. We also for the highest contents provided country and their contents. Then we
check the top cast and directors on Netflix. After that, we go for topic modeling. Here we
use Latent Dirichlet Allocation (LDA). By LDA we get our data in 5 clusters. Then we did
preprocess again for clustering. After the dimensionality reduction of our vectorized data
by Principal Component Analysis (PCA) we implemented 3 clustering algorithms - K -
Means clustering, Hierarchical clustering, and DBSCAN. After that, we evaluate the
clustering algorithm by evaluation metrics like - “Rand Index”, “Adjusted Rand Index”,
“Fowlkes Mallows Score”, “Calinski Harabasz Score”, “Davies Bouldin Score”,
“Silhouette Score” and “Purity Score”. At last, we develop a recommendation system
using cosine similarity.
Conclusion:
It's clear that Netflix has grown over the years. A large part of its success was due to the
decision to expand to international markets. The popular markets prioritize what content
the company will release. In this case, we can see that a good amount of international
movies and TV shows were added over the years as part of Netflix's global expansion.
