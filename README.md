The dataset is available on Kaggle, which consists of 5000 financial news headlines and they are classified as either positive,negative or neutral.
Two methods were used for calculating the word embeddings. First the Glove word embeddings were used and then using word2vec model(Gensim Library) custom word embeddings were generated(Glove word embeddings of 100 dimensions gave the best accuracy).
Keras module of Tensorlfow was used to create a sequential Bidirectional LSTM model.
To run the code the Glove 100 dimensions twitter trained word embeddings need to be downloaded.
