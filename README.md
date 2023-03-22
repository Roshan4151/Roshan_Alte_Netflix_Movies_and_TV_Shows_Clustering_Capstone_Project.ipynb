# Roshan_Alte_Netflix_Movies_and_TV_Shows_Clustering_Capstone_Project
This is the Capstone project which is a part of my Data Science training at AlmaBetter.

**Introduction:**

Netflix, headquartered in California, is a popular subscription streaming service and production firm. According to Statista, Netflix had approximately 220.67 million paid subscribers worldwide as of the second quarter of 2022. It is crucial that they effectively cluster the shows that are hosted on their platform in order to enhance the user experience for its subscribers. We will be able to understand the shows that are similar to and different from one another by creating clusters, which may be leveraged to offer the consumers personalized show suggestions depending on their preferences. The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

Conclusions: 

1.In this project, we worked on a text clustering problem wherein we had to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

2.The dataset contained about 7787 records, and 11 attributes.

3.It was found that Netflix hosts more movies than TV shows on its platform, and the total number of shows added on Netflix is growing exponentially. Also, majority of the shows were produced in the United States, and the majority of the shows on Netflix were created for adults and young adults age group.

4.It was decided to cluster the data based on the attributes: director, cast, country, genre, and description. The values in these attributes were pre-processed, tokenized, and then vectorized using TFIDF vectorizer. Through TFIDF Vectorization, we created a total of 20000 attributes.

5.Principal Component Analysis (PCA) was used to handle the curse of dimensionality. 4000 components were able to capture more than 80% of variance, and hence, the number of components were restricted to 4000.

6.We first built clusters using the k-means clustering algorithm, and the optimal number of clusters came out to be 6. This was obtained through the elbow method and Silhouette score analysis.

7.Hierarchical clustering model was built using the Agglomerative clustering algorithm, and the optimal number of clusters came out to be 12. This was obtained after visualizing the dendogram.

8.A content based recommender system was built using the similarity matrix obtained after using cosine similarity. This recommender system will make 10 recommendations to the user based on the type of show they watched.
