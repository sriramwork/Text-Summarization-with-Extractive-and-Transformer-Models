# Text-Summarization-with-Extractive-and-Transformer-Models
Sriram Theerdh Manikyala - NLP Project 1
# Text Summarization using Transformers

## Project Overview

This project focuses on automatic text summarization using both traditional NLP techniques and state-of-the-art transformer models. The objective is to generate concise, meaningful summaries from long research papers while preserving key information and context.

The process begins with data preprocessing, including text normalization, tokenization, and stopword removal. Next, the sentences are scored based on token frequency, and a summary is generated using an extractive approach. Finally, a transformer-based model, **T5**, is used for abstractive summarization, creating more fluent and human-like summaries.

### Key Features:
- **Extractive Summarization**: Using token frequency to score and select sentences.
- **Abstractive Summarization**: Using Hugging Face's **T5** transformer model for generating summaries.
- **Data Preprocessing**: Includes text cleaning, tokenization, stopword removal, and sentence segmentation.

## Instructions to Run the Code

### 1. Install Dependencies
You need to install the required libraries to run the project. Use the following commands to install the dependencies:

```bash
pip install pandas nltk spacy transformers torch
