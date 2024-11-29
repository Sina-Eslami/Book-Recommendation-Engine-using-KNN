# Book-Recommendation-Engine-using-KNN
Book Recommendation System
This repository contains the implementation of a book recommendation system developed as part of FCC's Machine Learning curriculum. The project processes a dataset of over one million book reviews, cleans the data, and builds a recommendation model using K-Nearest Neighbors (KNN).

Features
Data Cleaning:

Filters out books with fewer than 100 reviews and users with fewer than 200 reviews.
Validates ISBNs to remove unvalidated or incorrect entries, cleaning over 15,000 invalid ratings from the raw dataset.
Recommendation Model:

Implements a KNN-based algorithm to suggest books based on user ratings and preferences.
Dataset
The dataset includes:

User ratings for books (1 million+ reviews).
Book information including ISBNs, titles, and authors.
Data Preprocessing
Filtering: Removed books with less than 100 reviews and users with less than 200 reviews to improve data quality.
