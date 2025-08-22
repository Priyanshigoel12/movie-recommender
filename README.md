# 🎬 Movie Recommender System

## 🔎 Project Overview

This project is a movie recommendation system built using a content-based filtering approach. It analyzes movie data from The Movie Database (TMDb) to suggest films that are similar to a user's preferences, focusing on movie genres, keywords, cast, and crew.

-----

## 🎯 Objectives

  - Build a robust recommender system using a content-based filtering algorithm.
  - Clean and preprocess raw data from multiple sources to prepare it for analysis.
  - Identify key features such as cast, crew, and genres to calculate movie similarities.
  - Create a reusable function to generate movie recommendations for a given movie title.

-----

## 🛠 Tools & Technologies

  - **Python** → Core programming language
  - **Jupyter Notebook** → Interactive development and code presentation
  - **pandas** → Data manipulation and analysis
  - **numpy** → Numerical operations on data
  - **ast** → Safely evaluating strings containing Python literal structures

-----

## 📂 Project Structure

```
Movie-Recommender-System/
├── data/
│   ├── tmdb_5000_credits.csv
│   └── tmdb_5000_movies.csv
├── notebooks/
│   └── movie_recomendations.ipynb
├── README.md

```

-----

## 📈 Key Insights

  - **Data Preprocessing:** The datasets were merged and cleaned to handle missing values and prepare for analysis.
  - **Feature Extraction:** Key features like genres, keywords, cast, and crew were extracted and transformed into a vector representation.
  - **Similarity Scoring:** Cosine similarity was a highly effective metric for determining the similarity between movies based on their content vectors.
  - **Recommendation Engine:** The final model provides relevant and accurate movie suggestions by identifying the most similar movies to a user's input.

-----

## 🚀 How to Use

1.  Clone or download this repository.
2.  Navigate to the project directory in your terminal.
3.  Install the required libraries from `requirements.txt`.
4.  Open the `movie_recomendations.ipynb` notebook in a Jupyter environment and run the cells sequentially to see the recommender system in action.

-----

## 🤝 Author
👩‍💻 Priyanshi Goel  
[GitHub] - https://github.com/Priyanshigoel12 [LinkedIn] - www.linkedin.com/in/priyanshigoel06

⭐ Don’t forget to star this repo if you find it useful!





