# topic-modeling

NLP - topic modeling end-to-end experiment with Lda2Vec and Tensorflow.

## 1. Introduction

This project is to build topic modeling with Lda2Vec and Tensorflow. The topic modeling will categorize the articles (piece of text messsages) into topics in a un-supervised way. Please see this this link for more details about topic modeling: https://www.datacamp.com/tutorial/what-is-topic-modeling.

## 2. Folder Structure

- The lda2vec folder stores the reference code for the Lda2Vec model with Tensorflow.
- The data folder stores the input data (a CSV file), and the processed data (a .pkl file) for the model.
- The glove folder stores the glove pretrained word vectors based on tweeter data.
- The lda2vec_clean folder stores the cleaned data after applying the glove vectors and basic statistics operations.
- In the root dir, the language_modeling_lda2vec_tensorflow.ipynb file is a end-to-end topic modeling process from data preprocessing to the final visualization.
