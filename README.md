# simple-rnn-imdb


# IMDB Sentiment Analysis Using Simple RNN

## Overview

This project demonstrates **sentiment analysis on the IMDB movie review dataset** using a **Simple Recurrent Neural Network (Simple RNN)** built with TensorFlow/Keras.

The project covers:
- Loading the IMDB dataset
- Text preprocessing
- Vocabulary limitation
- Decoding encoded reviews
- Sequence padding
- Word embeddings
- Building a Simple RNN model
- Binary sentiment classification
- Early stopping
- Model training and validation

## Dataset

The project uses the **IMDB Movie Review Dataset** available through `tensorflow.keras.datasets.imdb`.

The dataset contains:

- 25,000 training reviews
- 25,000 testing reviews
- Binary sentiment labels:
  - `0` → Negative
  - `1` → Positive

The vocabulary is limited to the **10,000 most frequently occurring words**.

```python
max_features = 10000
