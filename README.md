Movie Recommendation System

This is a simple Content-Based Movie Recommendation System built using Python. It recommends movies based on textual similarity between movie overviews and genres using CountVectorizer and Cosine Similarity.


---

Features

Cleans and preprocesses movie data

Combines Overview and Genre into a single Tags field

Uses CountVectorizer to extract features from text

Computes pairwise similarity using cosine similarity

Recommends top 5 similar movies for a given movie title



---

Technologies Used

Python

NumPy

Pandas

Matplotlib

Scikit-learn



---

How It Works

1. Reads a CSV file (movies1.csv) containing movie data


2. Drops rows with missing values and removes duplicates


3. Combines Overview and Genre to create a Tags column


4. Vectorizes the Tags using CountVectorizer


5. Calculates cosine similarity scores between all movies


6. For a given movie, retrieves top 5 most similar movies




---

Usage

recommend("12 Angry Men")

The output will be the top 5 similar movie titles based on their content.


---

File Requirements

movies1.csv (or any other movies database) should include the following columns:

id

Title

Overview

Genre




---

Installation

1. Clone the repository


2. Make sure you have the following libraries installed:



pip install numpy pandas scikit-learn matplotlib

3. Run the notebook or script in your Python environment.




---

License

This project is open-source and available under the MIT License.


---
