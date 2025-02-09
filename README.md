Performing clustering models with different word vector representations on BBC news dataset from https://www.kaggle.com/datasets/moazeldsokyx/bbc-news
to see which one is suitable.

# Objectives
This project aims to cluster news articles into different categories 
based on their textual content using unsupervised machine learning 
techniques, specifically K-means and Hierarchical clustering. The goal 
is to group similar articles together to understand the underlying 
themes and topics present in a collection of news articles.

# Methodology
* EDA and Data cleaning remove outliers
* Data preprocessing
* tf-idf matrix, word2vec, doc2vec
* PCA for dimensional reduction 
* Model Training
* Clustering Models Evaluation
  
# Result
Based on silhouette scores the K-means with word2vec seem to be clustered 
well with its optimal features is 3. However in reality the clustering doesn’t cover 
the news well like each clustering contains combination of categories. While the 
TF–IDF and Doc2Vec seem to be more reasonable when clustering the text for 
both clustering models. However they don’t have high silhouette scores
