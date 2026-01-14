# 🎬 Movie Recommendation System

A content-based movie recommendation engine built with **Python**, **NLTK**, and **Streamlit**. This project takes raw data from Kaggle and transforms it into a functional web application.

---

## 📌 Overview

This system recommends movies by calculating the similarity between movie tags (genres, cast, crew, and overview). 

* **Dataset:** [TMDB 5000 Movies](https://www.kaggle.com/tmdb/tmdb-movie-metadata)
* **Logic:** Natural Language Processing (NLP)
* **Metric:** Cosine Similarity



---

## 🛠️ Tech Stack

| Tool | Purpose |
| :--- | :--- |
| **Python** | Primary programming language |
| **Jupyter** | Data cleaning and model prototyping |
| **PyCharm** | Application development |
| **NLTK** | Text stemming and preprocessing |
| **Streamlit** | Web UI framework |

---

## ⚙️ How It Works

1. **Data Cleaning:** Merged datasets and handled missing values in Jupyter.
2. **Text Processing:** Used **NLTK PorterStemmer** to reduce words to their roots (e.g., 'dancing' to 'danc').
3. **Vectorization:** Converted text into 5000-dimensional vectors using `CountVectorizer`.
4. **Similarity:** Calculated the **Cosine Similarity** (angle between vectors) to find the closest matches.



---

## 🚀 Execution

### 1. Requirements
Install the necessary libraries:
```bash
pip install streamlit pandas nltk scikit-learn
