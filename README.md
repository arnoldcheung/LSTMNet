# LSTMNet
A model utlising LSTM for translation quality estimation. Built using PyTorch and uses NLTK and spaCy preprocessing and word embeddings.

## Archituecture
* Two separate LSTM networks processing English and German texts individually
* Feed forward neural network regressor taking the concatenated output from the LSTM as input

## Prerequisites
    pip install spacy
    pip istall nltk
    pip install torch
    pip install tqdm
* The notebook usee tqdm_notebook for loading bars, recommended to use jupyter notebook or colab to run

## Running Tests
The notebook contain seven sections, run from the beginning for full test:

* Environment Set Up
    * Imports libraries, creates necessary directories, fix random seed and checks GPU
    
* Importing Data
    * Downloads training, validation, and test data.
    * Downloads word embeddings and stopwords
    
* Preparing Data
    * Defines dataloader for training, containing text preprocessing and embedding extraction

* Neural Network
    * Defines the neural network architecture
    
* Training and Evaluation
    * The main training and evaluation loop
    
* Prepare For Submission
    * Loads the model, and write predictions to an output file
    
* Results
    * No code, some example results from training
