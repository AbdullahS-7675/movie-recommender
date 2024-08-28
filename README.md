# Movie Recommender System

A movie recommendation system built using the TMDB-5000 movies dataset. This project uses Natural Language Processing and machine learning techniques to suggest movies similar to a user-provided input.

## Overview

This project focuses on developing a content-based movie recommender system that outputs the top 5 movies most similar to the one entered by the user. The similarity is calculated using cosine similarity on numerical vectors representing the textual data.

## Features

- **Data Cleaning and Preprocessing:**  
  - Handled missing values and duplicates in the dataset using Pandas.
  - Performed data cleaning to ensure quality and consistency of the dataset.

- **Feature Engineering:**  
  - Extracted relevant features and transformed the dataset into a format suitable for machine learning models.

- **Natural Language Processing (NLP):**  
  - Implemented Bag of Words (BoW) text vectorization using NLTK to convert textual data into numerical vectors.
  - Calculated similarity scores using cosine similarity to recommend movies.

- **Tools and Technologies Used:**  
  - **Pandas** and **Scikit-learn** for data cleaning, preprocessing, and feature engineering.
  - **NLTK** for text vectorization.
  - **Jupyter Lab** for an efficient development environment.

## Dataset

The dataset used for this project is the [TMDB-5000 Movies Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata). It contains information about movies such as titles, genres, keywords, cast, crew, and more.

## Results

The model successfully recommends the top 5 most similar movies based on the input movie's features, demonstrating a reliable content-based filtering approach.


