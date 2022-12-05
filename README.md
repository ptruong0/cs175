# CS 175 Project: Genre Classification on Lyrics
### Group Name: Genre Genies

## External Libraries
* Python libraries
  * scikit-learn (logistic regression, MLP)
  * tensorflow (RNN)
  * glove-python (training glove model)
  * nltk (preprocessing)
  * pandas (convert dataset to dataframe)
  * numpy
  * pyplot (data visualizations)
  * wordcloud (data visualizations)
  * miscellaneous: json, re, pickle, collections, random, tabulate

## Publicly Available Code
* training GloVe model on custom corpus

## Code Written By Team
* cleaning dataset
  * filtering out noisy or unwanted data
* preprocessing script
* creating vectors of GloVe embedding averages as features
* generating bag of words
* constructing RNN model with LSTM layers
* custom accuracy metrics 
  * accepting multiple genres
  * accuracies by genre
  * frequencies of each prediction
* data visualizations (word clouds, confusion matrices)
