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

🚀 Features

Content-based filtering

Uses TF-IDF on product descriptions and tags

Cosine similarity for recommendation ranking

Scalable to larger datasets

Modular notebook for experimentation

🛠️ Tech Stack

Language: Python 3.x

Libraries:

Pandas, NumPy (data processing)

Scikit-learn (TF-IDF, cosine similarity)

Matplotlib, Seaborn (visualization)

SciPy (sparse matrix operations)
