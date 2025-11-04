## Movie Review Search & Recommendation Engine

## Project Overview
This project implements a text-based movie recommendation search engine.
When a user enters a query such as "romantic emotional love story", the system retrieves the most similar movie reviews using TF-IDF Vectorization and Cosine Similarity.

## Objectives

- To understand information retrieval techniques.
- To build a search engine-like system using text similarity.
- To practice TF-IDF and vector-space modeling in NLP.

## Technologies Used

| Component            | Tool                               |
| -------------------- | ---------------------------------- |
| Programming Language | Python                             |
| NLP                  | NLTK / TF-IDF                      |
| Model                | Cosine Similarity                  |
| Dataset              | IMDB Movie Review Dataset (Kaggle) |

## How It Works
- Load movie reviews dataset.
- Preprocess text (lowercase, stopword removal, tokenization).
- Convert reviews to TF-IDF numeric vectors.
- When a user enters a query → convert query to vector.
- Use cosine similarity to find closest movie reviews.
- Return top recommendations.
