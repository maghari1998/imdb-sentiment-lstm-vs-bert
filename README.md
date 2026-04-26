# IMDB Sentiment Classification: LSTM vs BERT

This project compares a baseline **LSTM** model with a **BERT-based transfer learning** model for binary sentiment classification on the IMDB movie reviews dataset.

## Overview
The goal of this project is to classify movie reviews as **positive** or **negative** and compare the performance of a traditional sequence model (LSTM) against a pretrained transformer model (BERT).

## Methods
- **LSTM baseline** for sentiment classification
- **BERT fine-tuning** using transfer learning
- Text preprocessing, tokenization, batching, training, validation, and evaluation
- Performance comparison using **accuracy, precision, recall, and F1-score**

## Key Results

### Accuracy Comparison
| Model | Train Accuracy | Validation Accuracy | Test Accuracy |
|------|----------------|---------------------|---------------|
| BERT | 0.9834 | 0.9356 | 0.9320 |
| LSTM | 0.9312 | 0.8305 | 0.8231 |

### Test Set Performance
| Model | Precision | Recall | F1-score |
|------|-----------|--------|----------|
| BERT | 0.9264 | 0.9359 | 0.9311 |
| LSTM | 0.7862 | 0.8904 | 0.8351 |

## Main Finding
BERT clearly outperformed the LSTM baseline across training, validation, and test performance. This shows the advantage of pretrained transformer models for sentiment analysis, especially when compared with training an LSTM from scratch on the same dataset.

## Repository Contents
- `imdb_sentiment_lstm_vs_bert.ipynb` — main notebook
- `images/` — saved plots or screenshots


## How to View
The notebook can be opened directly on GitHub to review the code, outputs, and comparisons.

## Notes
Originally developed as a graduate course project.
