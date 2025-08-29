Sentiment Analysis with BERT 🚀

This repository contains two sentiment analysis projects using the BERT (Bidirectional Encoder Representations from Transformers) model.
Both projects involve fine-tuning BERT on different datasets and publishing the fine-tuned models on the Hugging Face Hub.

📌 Projects Included
1. Binary Sentiment Classification

Dataset: IMDB Movie Reviews

Objective: Classify movie reviews as Positive or Negative.

Model Used: BERT (base-uncased)

Approach:

Preprocessed the dataset

Tokenized text using Hugging Face's BertTokenizer

Fine-tuned BERT on the IMDB dataset

Evaluated using accuracy, precision, recall, F1-score

Published the fine-tuned model on Hugging Face

Hugging Face Model: 🔗 View Model - https://huggingface.co/swapnil-12/binary_cls_results

2. Multiclass Sentiment Classification

Dataset: AG News Dataset

Objective: Classify news articles into 4 categories:

World

Sports

Business

Sci/Tech

Model Used: BERT (base-uncased)

Approach:

Preprocessed and tokenized dataset

Fine-tuned BERT on the AG News dataset

Evaluated using accuracy, macro-F1, and confusion matrix

Published the fine-tuned model on Hugging Face

Hugging Face Model: 🔗 View Model - https://huggingface.co/swapnil-12/multiclass_cls_result
