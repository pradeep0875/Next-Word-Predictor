# Next Word Predictor

A deep learning-based application for predicting the next word in a given text sequence, inspired by language models. This application uses a pre-trained LSTM model and is built using `Streamlit` for an interactive web interface.

## Features

- **Next Word Prediction (Auto-Completion)**: Developed an LSTM-based model to provide next-word predictions, enhancing text input efficiency with real-time suggestions.
- **Streamlit Interface**: A simple and user-friendly web interface for entering text and getting predictions.
- **Trained Model**: The model architecture includes both LSTM and GRU layers to balance performance and efficiency.

## Model Development and Performance

- **Model Development**: Fine-tuned the architecture by experimenting with both LSTM and GRU layers and testing various configurations to achieve optimal performance.
- **Evaluation & Performance**: Achieved an accuracy of 69.20% with a loss of 1.3917 on the test set, showcasing the model's capability to predict the next word with reasonable accuracy.

## Setup and Requirements

### Prerequisites

Ensure you have Python installed (version 3.7+ recommended).

### Install Dependencies

Install the required dependencies by running:

```bash
pip install -r requirements.txt
