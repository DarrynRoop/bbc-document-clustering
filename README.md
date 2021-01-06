# bbc-document-clustering

Project for Information Retrieval and Web Search Course\
Goal: Clustering articles from BBC and BBC Sport into categories\
Dataset: http://mlg.ucd.ie/datasets/bbc.html\

Implementation:\
-Written in an iPython Jupyter notebook\
-Parses files and imports the articles into a list\
-Uses sk-learn to build the tf-idf matrix, then convert the outputted sparse array to NumPy\
-From-scratch k-means implentation\
-Dataset includes class labels that were used for external evaluation metrics\
-PCA to reduce dimensionality (sk-learn)\
