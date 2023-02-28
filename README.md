# TextVision
TextVision is a project that utilizes natural language processing (NLP) techniques to perform text classification on a given corpus of text. The aim of this project is to provide an efficient and accurate method for categorizing text into multiple classes or categories.

Table of Contents
* Overview
* Contributing


# Overview
TextVision is a Python-based project that uses the Keras deep learning library with TensorFlow as its backend. The project contains a script for building a hybrid deep learning model that combines both token and character embeddings. The model is trained on a corpus of text and can be used to predict the class or category of new text data.

The model_5.py script contains the code for building the hybrid deep learning model. The model consists of four input layers: line number embeddings, total line embeddings, token embeddings, and character embeddings. The token embeddings are created using a pre-trained Universal Sentence Encoder (USE) model from TensorFlow Hub. The character embeddings are generated using a Bidirectional LSTM layer. The line number embeddings and total line embeddings are created using simple dense layers.

The input layers are then concatenated and passed through a Bidirectional LSTM layer, a dropout layer, and a dense layer to create the final output. The output layer uses softmax activation to predict the probability of each class.


# Contributing
Contributions to the TextVision project are welcome. If you would like to contribute, please open an issue or submit a pull request on GitHub.
