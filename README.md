
# 🎬 Movie Recommendation System with Metadata and NLP

This project demonstrates how to build a simple content-based movie recommendation system using metadata and overview text from two datasets: `movies.csv` and `credits.csv`. The analysis includes data preprocessing, ranking by rating and popularity, visualization, and natural language processing using TF-IDF.

---

##  Datasets Used

- **movies.csv** — Contains metadata such as title, genres, popularity, and overview.
- **credits.csv** — Contains cast and crew information.

---

##  Features

- Data cleaning and merging of movie metadata and credits
- Ranking movies by:
  - Weighted average rating
  - Popularity score
  - Hybrid score (rating + popularity)
- Interactive visualizations using Plotly and Seaborn
- Text vectorization using TF-IDF on movie overviews
- Similarity matrix computation using sigmoid kernel
- Content-based recommendations using overview similarity

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Plotly
- Scikit-learn
- Jupyter Notebook

---

##  Visualizations

- Boxplots for vote count distribution
- Bar plots for:
  - Top-rated movies
  - Most popular movies
  - Hybrid (rating + popularity) rankings

---

##  Recommendation System

The recommendation system uses the movie’s overview (`description`) to compute similarity scores and recommend the most similar movies using:

```python
TfidfVectorizer + Sigmoid Kernel
````

##  Future Improvements

* Use cosine similarity for better performance
* Incorporate genre, cast, and crew into similarity model
* Deploy using Streamlit or Flask
* Add collaborative filtering model

---

## 📌 Author

**Felicia Angel**
Data Science @ Korea University
📫 [feliciaangel21@gmail.com](mailto:feliciaangel21@gmail.com)

---

## ⭐️ If you like this project...

Feel free to ⭐ the repo and fork it for your own custom movie recommendations!
