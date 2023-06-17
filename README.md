# Capstone-project-on-unsupervised-Ml-

## To ensure an optimal user experience and prevent subscriber churn, it is essential for Netflix, the world's leading online streaming service provider with over 220 million subscribers as of 2022, to effectively cluster the shows on their platform..

# Problem Statement

## The goal of this project is to analyze the Netflix catalog of movies and TV shows, which was sourced from the third-party search engine Flixable, and group them into relevant clusters. This will aid in enhancing the user experience and prevent subscriber churn for the world's largest online streaming service provider, Netflix, which currently boasts over 220 million subscribers as of 2022-Q2. The dataset, which includes movies and TV shows as of 2019, will be analyzed to uncover new insights and trends in the rapidly growing world of streaming entertainment.

## Objective

### The objective of this project is to organize the Netflix shows into distinct clusters, where the shows within a cluster are alike and the shows in different clusters are dissimilar to one another.


## Dataset

The dataset used in this project is sourced from Flixable, a third-party Netflix search engine. The data includes information on all movies and TV shows available on the streaming platform as of 2019, with a total of 7787 records and 12 attributes. Each attribute provides specific information about the movie or TV show.

1 .**show_id**: Unique ID for every Movie / Tv Show

2 .**type**: Identifier - A Movie or TV Show

3 .**title**: Title of the Movie / Tv Show

4 .**director**: Director of the Movie

5 .**cast**: Actors involved in the movie / show

6 .**country**: Country where the movie / show was produced

7 .**date_added**: Date it was added on Netflix

8 .**release_year**: Actual Releaseyear of the movie / show

9 .**rating**: TV Rating of the movie / show

10 .**duration**: Total Duration - in minutes or number of seasons

11 .**listed_in**: Genere

12 .**description**: The Summary description



## Data Cleaning And Feature Engineering

1. **Removing Duplicate Rows**

2. **Handling null values**


## Exploratory Data Analysis

ploting graphs for getting the clear information about dataset.

1.Numeric & Categoric features

2.Univariate Analysis  

3.Bivariate Analysis

4.Multivariate Analysis

### *Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:*

1.Bar plot

2.Pie Chart

3.Box Plot

## Textual Data Preprocessing

>> Clustering Attributes

>> Removing Stopwords

>> Lowercasing words

>> Removing Punctuation
 
>> Stemming
 
>> Snowball Stemmer

>> Word Vectorization

>> TF-IDF (Term Frequency - Inverse Document Frequency)
 
>> Dimenssionality Reduction

>> PCA (Principle Component Analysis)

## Model Building

>> Clustering Implemention

>> K-Means Clustering

>> Elbow Method

>> Silhoutte Score Analysis

>> Agglomerative Hierarchical Clustering

>> Dendogram

>> Content Based Recommendation System


## Conclusion

>> In this project, we worked on a text clustering problem wherein we had to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

>> The dataset contained about 7787 records, and 11 attributes.

>> We began by dealing with the dataset's missing values and doing exploratory data analysis (EDA).

>> It was found that Netflix hosts more movies than TV shows on its platform, and the total number of shows added on Netflix is growing exponentially. Also, majority of the shows were produced in the United States.

>> It was decided to cluster the data based on the attributes: director, cast, country, genre, rating and description. The values in these attributes were tokenized, preprocessed, and then vectorized using TFIDF vectorizer.

>> Through TFIDF Vectorization, we created a total of 10000 attributes.

>> We used Principal Component Analysis (PCA) to handle the curse of dimensionality. 3000 components were able to capture more than 80% of variance, and hence, the number of components were restricted to 3000.

>> We first built clusters using the K-Means Clustering algorithm, and the optimal number of clusters came out to be 6. This was obtained through the elbow method and Silhouette score analysis.

>> Then clusters were built using the Agglomerative clustering algorithm, and the optimal number of clusters came out to be 7. This was obtained after visualizing the dendrogram.

>> A content based recommender system was built using the similarity matrix obtained after using cosine similarity. This recommender system will make 10 recommendations to the user based on the type of show they watched.
