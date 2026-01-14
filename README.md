🎬 Movie Recommendation System
📌 Overview
A content-based recommendation engine built with Python and Streamlit. It suggests movies by analyzing metadata like genres, cast, and crew from a Kaggle dataset.

🛠️ Tech Stack
IDE: PyCharm

Analysis: Jupyter Notebook

NLP: NLTK (PorterStemmer)

Web App: Streamlit

ML: Scikit-learn (Cosine Similarity)

🚀 How to Run
Install Requirements:

Bash

pip install pandas streamlit nltk scikit-learn
Prepare the Data: Run your Jupyter Notebook to generate movie_dict.pkl and similarity.pkl.

Launch the App:

Bash

streamlit run app.py
🧠 Logic Flow
Data Cleaning: Merge datasets and remove nulls.

Preprocessing: Create a tags column using keywords and overviews.

Vectorization: Use CountVectorizer to turn text into numbers.

Similarity: Use Cosine Similarity to find the "distance" between movies.

📂 File Structure
app.py - The Streamlit frontend.

recommender.ipynb - Data processing logic.

requirements.txt - List of libraries.

movie_dict.pkl - Processed movie data.
