# CapstoneProject_NetflixMoviesAndTVShowsClustering
The goal of this project is to analyze the **Netflix Dataset of movies and TV shows till 2019**, which was sourced from the third-party search engine Flixable, and group them into relevant clusters, with the help of NLP. This will aid in enhancing the user experience with the help of **recommendation system**, and this can prevent subscriber churn from the world's largest online streaming service provider, Netflix, which currently boasts over **220 million subscribers**. The dataset will also be analyzed to uncover new insights and trends in the rapidly growing world of streaming entertainment.

We have followed a step by step process for this project which is as follows:-
1. Firstly, we have dealt with **null values/missing values**  in the dataset.

2. Handled the **nested columns** in the dataset, which are director, cast, listed_in, and country. This helps in clearly visualizing our analysis.

3. **Binning** the rating attribute into appropriate categories, such as adult, children's, family-friendly, and not rated content.

4. We performed **Exploratory data analysis (EDA)** on various attributes and gained insightful findings that will be valuable in preventing subscriber churn.

5. Created **cluster** using following attributes: director, cast, country, genre, rating and description. The **values in these attributes were tokenized, preprocessed, and then vectorized using TFIDF vectorizer.**

6. We have reduced the dimension of the project dataset using **PCA** which is a **dimensionality reduction technique** used to improve performance, as the resulted sparse matrix was huge with more than 30,000 attributes

7. We have utilized various methods such as the **Elbow method, Silhouette score, Dendrogram**, and others to construct two distinct types of clusters using **K-Means Clustering** and **Agglomerative Hierarchical Clustering** algorithms, respectively. With the help of K-Means clustering analysis, we determined that the optimal number of clusters for our dataset is **4**. Using the hierarchical clustering algorithm, we were able to identify **2** clusters.

8. Finally, we have developed a **content-based recommender system** using the **cosine similarity matrix**. This system analyzes the type of show a user has watched and generates personalized **recommendations for the user**, which is expected to improve user experience and  **reduce subscriber churn for Netflix**.
