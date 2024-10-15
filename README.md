# Text-Summarization-with-Extractive-and-Transformer-Models
Sriram Theerdh Manikyala - NLP Project 1
# Text Summarization using Transformers

## Project Overview

This study aims to automatically summarize text using both conventional NLP methods and cutting-edge transformer models. The goal is to condense large research articles into succinct, educational summaries by removing relevant information and context.

Data preprocessing, which includes text normalization, tokenization, and stopword removal, is the first step in the procedure. After that, an extraction technique is used to create an initial summary by scoring sentences according to token frequency. Lastly, the BART model, a transformer-based method that generates summaries that are both coherent and closely resemble human writing styles, is used to accomplish abstractive summarization.

### Key Features:
- **Extractive Summarization**: Using token frequency to score and select sentences.
- **Abstractive Summarization**: Using facebook/bart cnn model for generating summaries.
- **Data Preprocessing**: Includes text cleaning, tokenization, stopword removal, and sentence segmentation.

### To find the dataset externally:
visit this link : [https://www.kaggle.com/datasets/benhamner/nips-papers?select=papers.csv]

## Instructions to Run the Code

### 1. Install Dependencies
You need to install the required libraries to run the project. Use the following commands to install the dependencies:

```bash
pip install pandas nltk spacy transformers torch
