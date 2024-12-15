# Text Generation with LSTM

## Overview
This project implements a text generation model using Long Short-Term Memory (LSTM) networks. It trains on textual data to generate text sequences that mimic the input style. The project demonstrates neural network applications in tasks such as creative writing or predictive text generation.

## Key Features
- LSTM-based architecture for text modeling.
- Processes a PDF book file as the dataset, transforming it into sequences for training.

## Key Steps
1. **Data Extraction**: Extracts text from a PDF book file.
2. **Data Preparation**: Converts text into sequences for training.
3. **Model Definition**: Builds an LSTM model with Keras.
4. **Training**: Fits the model on input sequences to predict subsequent words.
5. **Text Generation**: Generates text based on a user-provided seed sequence.

## Project Limitations
- **Simplistic Model**: The basic LSTM struggles to generate coherent and meaningful text.
- **Fixed Input Size**: The model uses a fixed sequence length for training and generation, limiting flexibility.
- **Better Alternatives**: Advanced architectures like Transformers (e.g., GPT) offer better performance and realism.
- **Data Dependency**: Output quality relies heavily on the dataset’s size and content.
- **Compute Intensive**: Training requires significant computational resources for larger datasets.
