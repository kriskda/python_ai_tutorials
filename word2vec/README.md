# Amazon Reviews Word2Vec Embedding Example
This Jupyter Notebook project is focused on leveraging the power of Word2Vec, a popular word embedding technique, to analyze Amazon customer reviews. Utilizing the Gensim library, a powerful tool for natural language processing, this project aims to convert text data from Amazon reviews into meaningful vector representations.

## Word2Vec Explained
Word2Vec is an approach in the field of natural language processing (NLP) used to convert words into vector representations. These vectors capture semantic relationships between words, meaning that words with similar meanings are represented by vectors close to each other in the vector space. This technique is incredibly useful for a variety of applications in NLP, such as sentiment analysis, recommendation systems, and text classification.

## Dataset
The dataset used in this project consists of Amazon product reviews. These reviews are rich in natural language text and provide an excellent resource for performing word embedding with Word2Vec.

## Methodology
- Data Preparation: The dataset is first cleaned and preprocessed. This includes tokenization, removing stopwords, and other standard text preprocessing techniques to make the data suitable for Word2Vec training.
- Gensim Word2Vec: Use the Gensim library, a robust and efficient library for unsupervised topic modeling and natural language processing. Gensim's Word2Vec implementation is employed to create word embeddings.
- Training Word2Vec Model: The preprocessed text data is fed into the Word2Vec model. The model then learns vector representations for each unique word in the dataset, capturing the context and semantic similarity between different words.
- Analysis: Post training, these embeddings can be used to find similar words, analyze word relationships, or even as input features for further machine learning models.

## Usage
First download data set file from: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data
