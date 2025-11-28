# 🎬 Movie Recommender System (TMDB Dataset) | Machine Learning Project

This project implements an end-to-end **Content-Based Movie Recommendation System** using the **TMDB dataset**.
The system leverages **Natural Language Processing (NLP)** techniques and **Cosine Similarity** to recommend movies based on user preferences.

## 🚀 Project Overview

The goal of this project is to build a recommendation engine that analyzes movies’ metadata — such as **genres, cast, crew, keywords, and overview** — and computes similarity scores to recommend the most relevant movies.

This project demonstrates fundamental machine learning concepts including:

* **Feature Engineering**
* **Text Vectorization**
* **Dimensionality Reduction**
* **Similarity-Based Retrieval**

## 🧠 Key Machine Learning Concepts Used

* **Text Preprocessing** (tokenization, stemming, stopword removal)
* **TF-IDF / Count Vectorization** for converting text features into numerical vectors
* **Cosine Similarity** to compute similarity scores between movies
* **Vector Space Modeling** to represent movies in high-dimensional feature space
* **Content-Based Filtering** ML technique

## 📂 Dataset

The system uses the **TMDB 5000 Movies & Credits Dataset**, which contains rich movie metadata suitable for NLP-based feature extraction.

## 🔧 Tech Stack

* **Python**
* **Pandas, NumPy**
* **Scikit-learn**
* **NLTK / spaCy** (optional for preprocessing)
* **Pickle** for model export

## 🎯 Features

* Recommends top-N similar movies
* Works purely on movie metadata using ML techniques
* Clean preprocessing pipeline
* Exportable similarity model
* Deployed as a simple interactive system (Streamlit / Flask optional)

