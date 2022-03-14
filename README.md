# Toxic-Comment-Classification

This project is designed to classify toxic comments from Wikipedia into 6 types: 'toxic', 'severe toxic', 'obscene', 'threat', 'insult', 'identity hate'. We used common classifiers Logistic regression, Isolation Forest and Multinomial Naive Bayes. We also used neural network CNN and LSTM to train the classification model.

Data are achived from the [Kaggle competition](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data)

## Getting started

Download python 3 on the computer and download the code and packages listed below to your local machine to setup the model

### Prerequisites

- Python 
- Jupyter Notebook 
- Numpy Pandas 
- Matplotlib 
- Sklearn
- SciPy
- tensorflow 1.7.0rc1
- Keras 2.1.5
- gensim 3.4.0
- nltk 3.2.4
- wordcloud 1.4.1

### Installing

First to install Python 3 onto your computer 

Then to install all the packages needed to run the programs

`pip install numpy pandas matplotlib scikit-learn scipy`
`jupyter notebook` 


## Running tests

- For exploratory data analysis, run `eda_common_classifiers.ipynb`
- For common classifiers Logistic regression, Isolation Forest and Multinomial Naive Bayes, run `eda_common_classifiers.ipynb`
- For neural network CNN, run `cnn.ipynb`
- For neural network LSTM, run `LSTM.ipynb`

## Authors

* **Qingyuan Pan** [Github](https://github.com/panqingyuan)
* **Zishun Jin** [Github](https://github.com/354352231)
* **Yingyin Xiao** [Github](https://github.com/carmelbythesea)

## References

- Jigsaw/Conversation AI. (Dec, 2017). Toxic Comment Classification Challenge. Retrieved February, 2022 from https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data
- Read, Jesse & Pfahringer, Bernhard & Holmes, Geoffrey & Frank, Eibe. (2009). Classifier Chains for Multi-label Classification. Machine Learning. 85. 254-269. 10.1007/978-3-642-04174-7_17. 
- Chaudhary, M. (2020). TF-IDF Vectorizer scikit-learn. Retrieved March 2022, from https://medium.com/@cmukesh8688/tf-idf-vectorizer-scikit-learn-dbc0244a911a
- word2vec. (2013). Retrieved March 2022, from https://code.google.com/archive/p/word2vec
- Pennington, J. (2014). GloVe: Global Vectors for Word Representation. Retrieved March 2022, from https://nlp.stanford.edu/projects/glove/
- Mikolov, T., Corrado, G., Chen, K., & Dean, J. (2013). Efficient Estimation of Word Representations in Vector Space. Proceedings of the International Conference on Learning Representations (ICLR 2013), 1–12.
- Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Distributed Representations of Words and Phrases and their Compositionality. NIPS, 1–9.
