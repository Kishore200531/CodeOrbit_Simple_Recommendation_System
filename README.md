# CodeOrbit_Simple_Recommendation_System

# Project Title: Movie Recommendation System

# Technologies Used:
* Python
* Pandas
* Scikit-learn
* CountVectorizer
* Cosine Similarity
* CSV Dataset

The **Movie Recommendation System** is a Python-based recommendation project that suggests movies similar to a movie selected by the user. It uses a **content-based recommendation approach**, where movies are compared based on their genre information.

The project begins by loading movie data from a CSV file using **Pandas**. The dataset is converted into a DataFrame, making it easier to process and analyze the movie information.

To determine the similarity between movies, the project uses **CountVectorizer** from Scikit-learn. The movie genre information is converted into numerical vectors that can be processed mathematically.

After converting the genres into vectors, **Cosine Similarity** is applied to calculate how similar each movie is to every other movie. Movies with higher similarity scores are considered more relevant recommendations.

A dedicated `recommend()` function is implemented to make the recommendation process simple. When a movie title is provided, the system finds its corresponding index, calculates its similarity with other movies, sorts the results based on similarity, and displays the **top 5 similar movies**.

For example, the current implementation generates recommendations for **Titanic** and **Iron Man**.

# GitHub Repository Link: https://github.com/Kishore200531/CodeOrbit_Simple_Recommendation_System
