# IMDB Movie Review Sentiment Analysis

**Live Demo:** [Streamlit App](https://rnnimdbsentimentprediction-aq9btcdr8q4meydznnen6h.streamlit.app/)

## Overview
A machine learning web application that classifies movie reviews as positive or negative using a pre-trained Recurrent Neural Network (RNN). Built with Streamlit and TensorFlow/Keras, this app demonstrates natural language processing (NLP) capabilities with real-time text analysis.

## Features
- One-hot encoding text preprocessing
- SimpleRNN model with 1.3M+ parameters
- Real-time sentiment prediction
- Confidence score visualization
- Streamlit interactive interface

## Tech Stack
- **Core Framework**: TensorFlow 2.x
- **Frontend**: Streamlit
- **NLP Processing**: Keras Text Preprocessing
- **Data Handling**: NumPy
- **Dataset**: IMDB Movie Reviews (50,000 samples)

## Installation

1. Clone repository:
```bash
git clone https://github.com/yourusername/RNN_imdb_sentiment_prediction.git
cd RNN_imdb_sentiment_prediction
```
2. Create virtual environment:
``` bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate
```
3.Install dependencies:
``` bash
pip install -r requirements.txt
```
4.Run the app:
``` bash
streamlit run app.py
```

## How It Works
- Text Input: Users enter movie review text
- Preprocessing:
Lowercase conversion and tokenization
Word-to-index mapping using IMDB vocabulary
Sequence padding to 500 tokens
- Prediction:
RNN model processes encoded sequence
Returns sentiment (Positive/Negative) with confidence score


