## Introduction
With the ever-growing collection of movies, viewers often find it challenging to decide what to watch next. This project presents a Movie Recommender System that intelligently filters through a dataset of movies to suggest titles that match a user's taste. It leverages both content-based filtering and popularity-based recommendations to deliver relevant suggestions.

## Project Overview
1)The recommender system is designed to provide two types of suggestions:

2)Content-Based Filtering: Recommends movies similar in genre, keywords, cast, and other metadata.

3)Popularity-Based Recommendation: Shows top trending or most liked movies based on vote count and average rating.

4)This system is built and demonstrated in a Jupyter Notebook, making it easy to understand and extend further.

## Tools & Technologies Used
Python 3 – Core programming language.

Pandas – For data preprocessing and manipulation.

NumPy – For numerical operations.

Scikit-learn – Used for vectorization (CountVectorizer) and similarity computation (cosine_similarity).

NLTK – For natural language processing (e.g., stemming keywords).

TMDb API (optional) – To fetch movie posters dynamically using the TMDb (The Movie Database) API.

Jupyter Notebook – Interactive development and testing environment.

## Project Flow
Data Collection & Loading

Movie data is loaded from pre-downloaded CSV files (e.g., movies.csv, credits.csv, etc.).

Data Preprocessing

Merging datasets (e.g., movies with credits).

Cleaning data: removing missing values, duplicates.

Extracting and transforming features such as genres, cast, keywords, and overview.

Feature Engineering

Combining selected features into a single "tags" column.

Stemming and text normalization using NLTK.

Vectorizing text data using CountVectorizer.

Similarity Computation

Using cosine similarity on the vectorized feature matrix to compute movie-to-movie similarity scores.

Recommendation Function

A custom function that takes a movie name and returns top 5 most similar movies.

Poster Integration (Optional)

Fetches poster images for the recommended movies using TMDb API (if API key is provided).

