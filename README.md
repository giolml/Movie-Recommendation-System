# Author: Giovanni Roncancio, Data Scientist.
Welcome to the Movie Recommendation System, a robust platform designed to provide personalized movie recommendations. This system employs various recommendation algorithms including Collaborative Filtering (KNN), Content-Based Filtering (TF-IDF), and Jaccard Similarity, along with insights from Exploratory Data Analysis (EDA).

# Table of Contents
Overview
Features
Installation
Usage
Algorithms
Exploratory Data Analysis (EDA)
Contributing
License

# Overview
This project provides personalized movie recommendations using several methods:

Collaborative Filtering (KNN): Recommends movies based on user interactions and similarities with other users.
Content-Based Filtering (TF-IDF): Recommends movies similar to a given title based on content like genres.
Jaccard Similarity: Recommends movies based on genre similarities using the Jaccard index.
Popular and Weighted Recommendations: Offers top movies based on average ratings and vote counts.

# Technologies Used
Python
Pandas
Streamlit
Seaborn
Scikit-learn
Matplotlib

# Features
Personalized Recommendations: Users can enter their ID or choose a specific movie to get tailored recommendations.
Multiple Algorithms: Choose from KNN, TF-IDF, or Jaccard-based recommendations.
EDA Visualizations: Explore data distributions through interactive visualizations like histograms and boxplots.
User-friendly Interface: Streamlit-powered web app for ease of use.

# Usage
Once the app is running:

Select a recommendation method from the sidebar: KNN, TF-IDF, Jaccard, etc.
Input either your user ID or select a movie from the dropdown for recommendations.
Explore data using the "Análisis Exploratorio" option to view different charts and visualizations.

# Algorithms
## 1. Collaborative Filtering (KNN)
This algorithm recommends movies based on user ratings. It identifies similar users and suggests movies based on their ratings.

## 2. Content-Based Filtering (TF-IDF)
This technique recommends movies similar to a given movie based on the content of its genres using TF-IDF and cosine similarity.

## 3. Jaccard Similarity
Uses the Jaccard index to measure the similarity between movie genres and recommend similar movies.

# Exploratory Data Analysis (EDA)
The "Análisis Exploratorio" option provides insights into the data:

Distribution of Ratings: See how movie ratings are distributed among users.
Boxplot of Ratings: Understand the spread of ratings for better decision-making.
Histograms: Visualize the number of movies per genre and ratings per user.

# Project Challenge
Imagine having access to streaming platform data and using it to enhance user experiences!

As data scientists, we analyzed streaming data using Python to build a personalized movie recommendation engine that delivers precise and relevant suggestions. This system revolutionizes how users discover new content by leveraging advanced machine learning techniques.

# Team Members

|Participantes|Roles|Redes|
|:---:|:---:|:---:|
|**Mirna Prieto**|![](https://img.shields.io/badge/DATA%20SCIENTIST-blue?style=for-the-badge)| <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/mirna-prieto-990356242/">![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
|**Lucel Da Silva**|![](https://img.shields.io/badge/DATA%20SCIENTIST-blue?style=for-the-badge)| <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/jumacaq/">[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luceldasilva/)</a>
|**Juan Campos**|![](https://img.shields.io/badge/DATA%20SCIENTIST-blue?style=for-the-badge)| <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/jumacaq/">[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jumacaq/)</a> |
|**Wilfer Alexander**|![](https://img.shields.io/badge/DATA%20SCIENTIST-blue?style=for-the-badge)| <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/jumacaq/">[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wilfer-echavarria-bb19191b/)</a> |
|**Giovanni Roncancio**|![](https://img.shields.io/badge/DATA%20SCIENTIST-blue?style=for-the-badge)| <a target="_blank" rel="noopener noreferrer" href="https://www.linkedin.com/in/jumacaq/">[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/giovanni-roncancio-ds/)</a> |

> [!IMPORTANT]
> Esto fue un proyecto que participamos los miembros del canal del
> 
>[![](https://img.shields.io/youtube/channel/subscribers/UCuerQOTskuNkddcT738357g?style=for-the-badge&logo=youtube&label=Bootcamp%20Xperience)](https://www.youtube.com/@BootcampXperience)

# Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue to suggest improvements.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
