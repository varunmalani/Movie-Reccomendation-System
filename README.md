# Movie-Reccomendation-System

Varun Malani - RA1911032010010, Karthik Nelanti - RA1911032010012

# Problem Statement

Over the years, there has been a rise in the population switching to OTT platforms for watching movies. Hence many companies are using and updating their machine learning model for recommending movies to their customers. The current methods are complex and are not up to the mark and hence not dependable.

# Objective

The given two datasets which are available from Kaggle provide us with information about the movie and cast over the past few years. The original content-based recommender system is the continuation and development of collaborative filtering, which doesn’t need the user’s evaluation for items. Instead, the similarity is calculated based on the information of items that are chosen by users and then make the recommendation accordingly. We can implement machine learning model algorithms that use cosine similarity in the backend to recommend movies to customers.

# Data Used 

The two CSV files naming movies and credits have been taken from the website Kaggle. We have taken approximately 5000 movies from the movies files. 
<br>
<br> 
Kaggle Link - https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata 

# Pipeline of the project
1. Data Acquisition 
2. Data Processing
3. Data Modeling
4. Execution
5. Deployment

# Architecture / Model

<img width="963" alt="image" src="https://user-images.githubusercontent.com/51241123/163738726-0544d064-3684-4ead-b721-dad1a594ebff.png">


# Predicted Output

The movie recommender predicts the top five related movies with the input given by the user. We trained our dataset from the past and applied it to models which are based on cosine similarity. The algorithm will generate the most similar five movies and print them to the user. It streamlines the data science process so that users get high-quality predictions in a fraction of the time it took using traditional methods, allowing them to more quickly implement those predictions and see the impact on their bottom line.

# References
- Cosine Similarity - https://towardsdatascience.com/understanding-cosine-similarity-and-its-application-fd42f585296a
- Stemming - https://www.nltk.org/howto/stem.html
- CountVectorizer - https://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.CountVectorizer.html

# Sample Output

<img width="253" alt="image" src="https://user-images.githubusercontent.com/51241123/163738678-3e96dbf8-5472-4908-b577-9ef6dfc6959b.png">


