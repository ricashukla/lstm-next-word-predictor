# LSTM Next Word Predictor

A deep learning NLP project that predicts the next word in a sequence using an LSTM model trained on Shakespeare's Hamlet text.

## Live Demo
https://lstm-next-word-predictor-02.streamlit.app/

## GitHub Repository
https://github.com/ricashukla/lstm-next-word-predictor

## Features
- Next word prediction using LSTM
- Trained on Hamlet dataset
- Streamlit web app deployment
- TensorFlow/Keras implementation

## Tech Stack
- Python
- TensorFlow
- Keras
- Streamlit
- NumPy
- Pickle

## Project Structure
```bash
lstm_rnn/
│── app.py
│── hamlet.txt
│── tokenizer.pickle
│── next_word_lstm.h5
│── requirements.txt
```

## How to Run Locally

1. Clone repository

```bash
git clone https://github.com/ricashukla/lstm-next-word-predictor.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Run Streamlit app

```bash
streamlit run lstm_rnn/app.py
```

## Model
- Embedding Layer
- LSTM Layer
- Dense Output Layer

## Dataset
Shakespeare Hamlet text corpus.

## Author
Richa Shukla
