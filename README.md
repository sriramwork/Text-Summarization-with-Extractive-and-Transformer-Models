# Text-Summarization-with-Extractive-and-Transformer-Models
Sriram Theerdh Manikyala - NLP Project 1
# Text Summarization using Transformers

## Project Overview

The goal of this research is to automatically summarize text using both cutting-edge transformer models and conventional NLP techniques. The goal is to distill significant material and context from lengthy research articles into succinct, useful summaries.

Data preprocessing, which includes stopword removal, tokenization, and text normalization, is the first step in the process. After that, an extractive method is used to score the sentences according to token frequency and produce a summary. Lastly, abstractive summarization is achieved using **T5**, a transformer-based approach that produces summaries that are more natural and human-like.

### Key Features:
- **Extractive Summarization**: Using token frequency to score and select sentences.
- **Abstractive Summarization**: Using Hugging Face's **T5** transformer model for generating summaries.
- **Data Preprocessing**: Includes text cleaning, tokenization, stopword removal, and sentence segmentation.

## Instructions to Run the Code

### 1. Install Dependencies
You need to install the required libraries to run the project. Use the following commands to install the dependencies:

```bash
pip install pandas nltk spacy transformers torch
