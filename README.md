# WBSFLIX Recommender Systems Project

## Overview

Welcome to the WBSFLIX Recommender Systems project! This project was completed as part of the Data Science Bootcamp and aims to develop recommender systems for a small DVD store called WBSFLIX, located near Berlin. The goal of the project is to provide personalized and serendipitous movie recommendations to users based on their preferences and behavior.

## Project Description

The objective of this project is to create recommender systems that suggest relevant movies to users of WBSFLIX. The project consists of three major types of recommender systems:

1. Popularity Rankings: Recommending movies based on a hybrid method of average rating and number of ratings. This non-personalized system suggests popular movies to users.

2. Item-Based Collaborative Filtering: Recommending movies similar to ones that the user has recently watched or rated highly. This semi-personalized system uses user-item ratings to find correlations and suggest similar movies.

3. User-Based Collaborative Filtering: Providing personalized recommendations by finding similar users and suggesting movies that those users enjoyed. This fully personalized system utilizes the Surprise library to implement collaborative filtering algorithms.

## Project Phases

The project is divided into the following phases:

1. Popularity Rankings: Creating a basic recommender based on popularity and average ratings of movies.
2. Item-Based Collaborative Filtering: Developing a system that suggests movies similar to ones the user has engaged with.
3. User-Based Collaborative Filtering with Surprise: Implementing a personalized recommender system using the Surprise library.
4. Expanding the Recommender: Enhancing the system by avoiding duplicate recommendations and considering movie genres.

## Tools and Libraries

The project utilizes the following tools and libraries:

- Python
- Google Colab Notebooks
- NumPy
- Pandas
- Scikit-Learn (for mean absolute error and train-test split)
- Seaborn
- Matplotlib (for data visualization)
- Surprise (for collaborative filtering recommender systems)
- Other necessary libraries for data manipulation and analysis

These libraries were crucial in performing data manipulation, preprocessing, similarity calculations, visualization, and implementing various recommender systems within Google Colab environment.

## Usage Instructions

Please note that this README provides an overview of the project and its different phases. Each phase involves coding and implementation. To explore the project in detail, refer to the respective Google Colab Notebook files within the repository.

## Conclusion

The WBSFLIX Recommender Systems project demonstrates how to build different types of recommender systems that provide tailored movie recommendations to users. Through popularity rankings, item-based collaborative filtering, and user-based collaborative filtering, the project showcases various approaches to enhancing user experience and engagement.

Feel free to explore the Google Colab notebooks, experiment with different data, and modify the code to suit your needs. This project serves as a foundation for understanding and implementing recommender systems in real-world scenarios.
