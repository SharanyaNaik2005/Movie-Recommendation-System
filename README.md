🎬 Movie Recommendation System
This project builds a content-based movie recommendation system using Python, Pandas, Scikit-learn, and Cosine Similarity. It suggests movies similar to a user’s favorite movie based on genres, keywords, tagline, cast, and director.

📌 Features
Uses TF-IDF Vectorization to convert movie features into numerical form.
Calculates cosine similarity between movies.
Recommends Top 10 or Top 30 movies similar to the user’s choice.
Handles partial or misspelled movie names using difflib.
Dataset sourced from YBI Foundation.

🛠 Tech Stack
Python
Pandas & NumPy – Data handling
Scikit-learn – TF-IDF & cosine similarity
Difflib – Fuzzy string matching

📂 Dataset
Dataset: Movies Recommendation.csv
Columns used for recommendations:
Movie_Genre
Movie_Keywords
Movie_Tagline
Movie_Cast
Movie_Director

🚀 How It Works
1. Load the dataset using Pandas.
2. Select important features (genre, keywords, tagline, cast, director).
3. Combine text data and apply TF-IDF Vectorizer.
4. Compute cosine similarity matrix between movies.
5. Take user’s favorite movie as input.
6. Find the closest match using difflib.
7. Recommend Top 10 or Top 30 similar movies.
8. 

OUTPUT:
Enter your favourite movie name: Avatar
Top 10 Movies suggested for you:
1. Avatar
2. Guardians of the Galaxy
3. Star Trek
4. The Avengers
5. Thor
6. ....
