# Thanglish to English Translator

## Overview
This project aims to develop a neural network-based translator that converts Thanglish sentences (a hybrid language combining Tamil and English) into English. Thanglish is commonly used in online communication, especially on social media platforms. The translator leverages Natural Language Processing (NLP) techniques and deep learning models to achieve accurate translations.

## Features
- Tokenization of Thanglish and English sentences
- Custom tokenizer implementation
- LSTM, GRU, and Transformer neural network models
- Training and evaluation of models
- Translation of Thanglish sentences to English

## Dataset
The dataset consists of pairs of Thanglish and English sentences. Thanglish sentences are written in the Tamil script but may contain English words or phrases. English sentences are their corresponding translations. The dataset is available in the following files:
- `train.txt`: Thanglish sentences
- `trainen.txt`: English translations

## Pre-processing
- Reading and preprocessing of dataset
- Tokenization: Breaking sentences into tokens
- Padding: Ensuring uniform sequence length

## Models
1. **LSTM Model**: Long Short-Term Memory neural network architecture for sequence translation.
2. **GRU Model**: Gated Recurrent Unit neural network architecture, an alternative to LSTM.
3. **Transformer Model**: State-of-the-art architecture based on self-attention mechanisms.

## Evaluation
- Training and validation of models
- Monitoring accuracy and loss metrics
- Model performance evaluation on test data

## Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the desired model script (`lstm_model.py`, `gru_model.py`, `transformer_model.py`) to train and evaluate the model.
4. After training, use the trained model for translation by providing a Thanglish sentence as input.

## Contributors
- [Dinesh Kumar M](https://github.com/imdineshkumar24)
- [Dhanush G](https://github.com/gdhanush27)
- [Vignesh R](https://github.com/KECWIKKI)

## License
This project is licensed under the [MIT License](https://mit-license.org/).
