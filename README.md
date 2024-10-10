HH Skill Analysis
Project Description

This project focuses on analyzing key skills listed in job postings for IT specialists from the HeadHunter website for the year 2023. The project includes the following steps:

    Preprocessing of text data.
    Vectorization of text data using TF-IDF and Word2Vec methods.
    Clustering of the data using K-Means, Agglomerative Clustering, and Spectral Clustering methods.
    Evaluation of clustering quality using metrics such as Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index.
    Visualization of the results using t-SNE and word clouds.

Project Structure

    preprocessing.ipynb: This file contains the steps for text data preprocessing (stopword removal, lemmatization, etc.) using libraries such as re, pandas, spacy, and nltk.

    tfidf_clustering.ipynb: In this file, data is vectorized using the TF-IDF method and clustered using KMeans, Agglomerative Clustering, and Spectral Clustering methods. Clustering quality is assessed using Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index.

    word2vec_clustering.ipynb: Similar to the second file, but with Word2Vec vectorization, followed by clustering and quality assessment using the same methods.

