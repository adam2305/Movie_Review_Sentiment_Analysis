# 🎬 Movie Review Sentiment Analysis with LSTM and CBOW

This project builds an AI model to classify movie reviews as either positive or negative. Using a combination of Continuous Bag of Words (CBOW) for word embeddings and Long Short-Term Memory (LSTM) networks, the model is trained to understand the sentiment behind each review.

## Project Overview

This sentiment analysis project is divided into two parts:

- Embedding Matrix Creation with CBOW and LSTM: In the first phase, the CBOW technique is used to learn word representations, resulting in an embedding matrix that captures the semantic meanings of words. This embedding matrix is then used as input to an LSTM network.
- Binary Classification with RNN: Using the pre-trained embeddings, a many-to-one recurrent neural network (RNN) model is trained to classify each movie review as positive or negative.

## Key Components

- CBOW for Embeddings: A pre-training step that uses the CBOW approach to create word embeddings, helping the model understand context and relationships between words in movie reviews.
- LSTM-Based Sentiment Classifier: A many-to-one LSTM model trained to identify the sentiment of a review based on the learned embeddings.
- Binary Classification: Final RNN model performs binary classification, distinguishing between positive and negative reviews with the aim of high accuracy and reliability.

## Usage

After training, the model can be used to classify new movie reviews. Input a text review, and the model will return a sentiment score, indicating whether the review is positive or negative.

## Future Improvements

- Expanding to multi-class sentiment classification (e.g., highly positive, neutral, highly negative)
- Fine-tuning embeddings with larger and more diverse datasets
- Exploring additional architectures like bidirectional LSTMs or Transformers for enhanced accuracy
