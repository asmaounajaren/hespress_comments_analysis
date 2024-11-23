# Arabic Sentiment Analysis with Deep Learning

This project implements a deep learning-based sentiment analysis system for Arabic text using a Recurrent Neural Network (RNN) with Attention mechanisms. The goal is to classify Arabic comments into three sentiment categories: **positive**, **negative**, and **neutral**.  

## Features
- Preprocessing of Arabic text (cleaning, tokenization, and padding).
- Data augmentation to handle class imbalances.
- A deep learning architecture with embedding, LSTM, and attention layers.
- Evaluation of model performance on test data.

---

## Dataset
The dataset used in this project contains Arabic comments with their corresponding sentiment labels. The data is split into:
- **Training data**: Used to train the model.
- **Validation data**: Used to tune the model during training.
- **Test data**: Used to evaluate the model's generalization.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Libraries:
  - `TensorFlow`
  - `scikit-learn`
  - `nltk`
  - `matplotlib`
  - `numpy`
  - `pandas`

Install the dependencies using:
```bash
pip install -r requirements.txt
