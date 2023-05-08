# Word2Vec Implementation using Gensim Library on Amazon and Sports Review Datasets

In this project, we have implemented Word2Vec using the Gensim library on two different datasets, Amazon Review Dataset and Sports and Outdoors Review Dataset. The aim of this project is to understand the workings of the Word2Vec algorithm and to explore how it can be used to extract meaningful information from text data.

## Dataset
The datasets we have used are subsets of Amazon reviews from the Cell Phones & Accessories category and Sports and Outdoors category. The data is stored as a JSON file and can be read using pandas. Links to the datasets are given below:

- Amazon Review dataset:
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Cell_Phones_and_Accessories_5.json.gz

- Sports and Outdoor Review dataset:
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Sports_and_Outdoors_5.json.gz

## Implementation
We have used the Gensim library to implement Word2Vec on the two datasets. We first read the data using pandas and then preprocessed the text data using the gensim.utils.simple_preprocess() function. We then built the vocabulary using the model.build_vocab() function and trained the Word2Vec model using the model.train() function. Finally, we saved the trained model using the model.save() function.

## Results
After training the Word2Vec model, we used various functions such as model.wv.most_similar() and model.wv.similarity() to explore the semantic relationships between words in the datasets. We were able to extract meaningful information from the datasets and find similarities between words based on their contexts.

## Conclusion
In this project, we have demonstrated how Word2Vec can be implemented using the Gensim library and how it can be used to extract meaningful information from text data. We hope that this project will serve as a useful introduction to the Word2Vec algorithm and its applications in natural language processing.

