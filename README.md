# BART-based Text Summarization and NLP Utilities

This project demonstrates the use of the `transformers` library for text summarization using the **BART model**. It also includes utilities to analyze text before and after summarization, such as word and sentence counts. Additionally, it employs the Hugging Face `pipeline` for quick summarization tasks.

---

## Features

- **Text Summarization**: Summarizes input text using the pre-trained `facebook/bart-large-cnn` model.
- **Word Count Analysis**: Counts words in the text before and after summarization.
- **Sentence Tokenization**: Tokenizes the summary into sentences using the NLTK library for proper visibility of sentences.
- **Pipeline Summarization**: Provides an alternative method for summarization using Hugging Face's `pipeline`.

---

## Prerequisites

1. **Google Colab/other**.
2. Required Python libraries:
   - `transformers`
   - `nltk`

Install the required libraries using:
```bash
pip install transformers nltk
