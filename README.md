# 🎬 Movie Recommendation System

A simple **Content-Based Movie Recommendation System** built with Python. It recommends movies based on textual similarity between their **overviews** and **genres**, using **CountVectorizer** and **Cosine Similarity**.

---

## ✨ Features

- Cleans and preprocesses movie data  
- Combines `Overview` and `Genre` into a single `Tags` field  
- Uses `CountVectorizer` to extract features from text  
- Computes pairwise similarity using **cosine similarity**  
- Recommends **Top 5** similar movies for a given movie title  

---

## 🛠️ Technologies Used

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## ⚙️ How It Works

1. Loads the movie dataset from `movies1.csv`  
2. Removes rows with missing values and duplicates  
3. Merges `Overview` and `Genre` into a `Tags` column  
4. Converts text data into feature vectors using `CountVectorizer`  
5. Calculates similarity scores using cosine similarity  
6. Recommends the top 5 similar movies for a selected title  

---

## ▶️ Usage

```python
recommend("12 Angry Men")
```

**Output:**  
Top 5 movie recommendations similar to "12 Angry Men".

---

## 📁 File Requirements

Make sure your CSV file (`movies1.csv`) contains the following columns:

- `id`  
- `Title`  
- `Overview`  
- `Genre`  

---

## 🚀 Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. **Install dependencies**

```bash
pip install numpy pandas scikit-learn matplotlib
```

3. **Run the script or Jupyter Notebook**

Open the `.ipynb` file in Jupyter or run the script using Python.

---
