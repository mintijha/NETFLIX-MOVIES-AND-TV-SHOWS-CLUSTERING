# NETFLIX MOVIES AND TV SHOWS CLUSTERING
![image](https://github.com/mintijha/NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING/assets/123978172/49311a8e-6c3c-41e6-bdaa-3a568b034c01)

## Overview
Welcome to the Netflix Content Analysis project! This project explores the vast collection of movies and TV shows available on Netflix, aiming to uncover patterns, genres, and user preferences through advanced data analysis and clustering techniques.

## Table of Contents
Overview

Features

Installation

Usage

Technologies Used

Data Preprocessing

Dimensionality Reduction

Clustering Algorithms

Model Evaluation

Results and Insights

Conclusion

Future Work

Contributing

## Features

Cleaned and processed Netflix dataset to handle missing values and standardize data.

Applied text normalization techniques for genres and other textual data.

Implemented PCA for dimensionality reduction to visualize data patterns effectively.

Utilized k-means, hierarchical clustering, and DBSCAN for content clustering.

Evaluated clustering models using silhouette score to identify optimal clusters.

##  Installation

To run the project locally, follow these steps:

pip install -r requirements.txt

## Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

## Data Preprocessing

Handled missing values and applied text normalization techniques to clean and preprocess the Netflix dataset for analysis.

## Dimensionality Reduction

Implemented PCA (Principal Component Analysis) to reduce feature dimensions and maintain data variance, aiding in visualizing and understanding data patterns.

## Clustering Algorithms

Employed k-means, hierarchical clustering, and DBSCAN algorithms to cluster Netflix movies and TV shows based on their features and genres.

## Model Evaluation

Evaluated clustering models using silhouette score to determine the quality of clusters and their suitability for understanding content categorization.

## Results and Insights
![image](https://github.com/mintijha/NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING/assets/123978172/2a48acf2-595d-4ade-8958-4d9759facec8)

Movies uploaded on Netflix are more than twice the TV Shows uploaded. This dose not implies that movies are more indulging that of TV Shows. Beacuase TV shows may have several seasons which consits of number of episodes. Duration of TV shows are much more that of movies

![image](https://github.com/mintijha/NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING/assets/123978172/f1fa3fe4-6616-4a6d-b9cd-6e70392dc42a)

TV shows are incresing continuosly. Movies were incresing continuosly but after 2019 there is fall.

![image](https://github.com/mintijha/NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING/assets/123978172/8cbe0508-60d0-47ed-80f7-60a079303dcc)

The pie chart shows the percentage share of each of the top 10 genres in the dataset. The insight we can gain from this chart is that the most popular genre in the dataset is dramas, followed by comedies and documentries. It also shows that the top 10 genres make up a significant portion of the dataset.

Discovered distinct clusters within Netflix content, revealing user preferences and genre trends. Insights can inform content recommendation systems and marketing strategies.

## Conclusion

This project demonstrates the application of machine learning techniques to analyze and cluster Netflix content effectively. It provides valuable insights into user preferences and content categorization, contributing to enhanced user experience and targeted content recommendations.

## Future Work

Future enhancements could include:

Incorporating more granular user data for personalized recommendations.

Integrating real-time data for dynamic content analysis.

Exploring additional clustering algorithms and advanced feature engineering techniques.

## Contributing

Contributions are welcome! Fork the repository and submit a pull request with your enhancements.

## How This Project Is Helpful

**Enhanced User Experience:** Improves content discovery and recommendation systems for Netflix users.

**Business Insights:** Provides actionable insights for content creators and marketers to optimize content strategy.

**Educational Resource:**  Serves as a learning tool for data scientists and machine learning enthusiasts interested in exploratory data analysis and clustering techniques.
