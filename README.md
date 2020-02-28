# LSTMNet
A model utlising LSTM for translation quality estimation.

## Archituecture
* Two separate LSTM networks processing English and German texts individually
* Feed forward neural network regressor taking the concatenated output from the LSTM as input

## Prerequisites
  pip install spacy
  pip istall nltk
  pip install torch
