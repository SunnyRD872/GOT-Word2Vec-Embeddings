
# GOT-Word2Vec-Embeddings
Project Overview

This project applies Natural Language Processing (NLP) by training a Word2Vec model using Gensim on the Game of Thrones book series. Word2Vec is a powerful technique for learning word representations, where words with similar meanings appear closer together in a high-dimensional space.

Since word vectors are 100-dimensional, Principal Component Analysis (PCA) is used to reduce them to 3D, enabling interactive visualization with Plotly. This helps in exploring semantic relationships between words and understanding their contextual similarities.



## Features

- Preprocessing: Used gensim.simple_preprocess and NLTK for text cleaning & stopword removal.
- Word Embeddings: Trained Word2Vec (Gensim) with window=10 and min_count=2. In Word2Vec, the window=10 parameter defines the context window size, meaning the model considers 10 words before and 10 words after a target word to learn relationships.and In Word2Vec, setting min_count=2 means that only words that appear at least twice in the entire corpus are considered for training the model.

- Dimensionality Reduction: Used PCA to convert 100D vectors to 3D.
- Visualization: Plotted embeddings in interactive 3D using Plotly.




## Dataset
https://www.kaggle.com/datasets/khulasasndh/game-of-thrones-books
## Special Thanks
This project was inspired by the tutorial from the CampusX Channel on YouTube.

Video: Word2vec Complete Tutorial | CBOW and Skip-gram | Game of Thrones Word2vec

Channel: CampusX
