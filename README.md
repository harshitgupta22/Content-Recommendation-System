# Content-Recommendation-System

This project implements a content-based recommendation system that suggests similar products based on their descriptions, tags, and metadata. The model uses TF-IDF vectorization and cosine similarity to compute product similarity and generate recommendations.

📌 Overview :

Dataset: Walmart product reviews dataset (TSV format, ~5k records).
Goal: Recommend products to users based on product descriptions, tags, brand, and categories.
Approach:
Preprocess dataset (handle missing values, select relevant columns).
Convert text features into numerical vectors using TF-IDF.
Compute cosine similarity between product vectors.
Recommend top N similar products for a given product.

🚀 Features :

Content-based filtering
Uses TF-IDF on product descriptions and tags
Cosine similarity for recommendation ranking
Scalable to larger datasets
Modular notebook for experimentation

🛠️ Tech Stack :

Language: Python 3.x
Libraries:
Pandas, NumPy (data processing)
Scikit-learn (TF-IDF, cosine similarity)
Matplotlib, Seaborn (visualization)
SciPy (sparse matrix operations)

EDA (Exploratory Data Analysis) :

<img width="1148" height="766" alt="Screenshot 2025-09-09 153112" src="https://github.com/user-attachments/assets/698181b4-4fe7-465f-b206-763501a54d36" />

<img width="732" height="746" alt="Screenshot 2025-09-09 152835" src="https://github.com/user-attachments/assets/23411699-b6d9-4ca1-bdb0-704ba1029dae" />
