# Assignment 5 – Word Embeddings

## Objective
Implement Word2Vec, FastText, Doc2Vec, K-Means clustering, and sentence similarity on Gujarati text data.

## Dataset
- 1,000,000 Gujarati sentences
- 800,000 Training
- 100,000 Validation
- 100,000 Test

## Implementation
- Trained **Word2Vec, FastText, and Doc2Vec** embeddings.
- Applied **K-Means** clustering to word embeddings.
- Found **20 words closest to each cluster centroid**.
- Used Word2Vec, FastText, and Doc2Vec to represent sentences.
- Used **cosine similarity** to find the closest test sentence for each validation sentence.

## Outputs
- Word2Vec, FastText & Doc2Vec models
- `kmeans_clusters.csv`
- `sentence_similarity_results.csv`

## Libraries
Python, Gensim, NumPy, Pandas, Scikit-learn
