# Sentiment Analysis and Retrieval Augmented Generation with LLMs and Transformers

This project is an in-depth exploration of various NLP techniques and models, focusing on sentiment analysis and retrieval-augmented generation (RAG) using large language models (LLMs) and transformer architectures.

## Project Overview

The system is designed to handle both text and audio inputs, converting audio to text, and performing sentiment analysis using a fine-tuned BERT text classification model. The workflow includes:

1. **Sentiment Analysis**: Utilizing a BERT model for sentiment classification, fine-tuned to optimize precision, recall, and F1 score.
2. **Retrieval-Augmented Generation (RAG)**: Using cosine similarity with a Hugging Face Sentence Transformer to find and retrieve comments most similar to the input text.
3. **Summary Generation**: Employing a Mistral's LLM to generate summaries of the input and retrieved comments, with prompts fine-tuned through zero-shot and few-shot learning.

## Key Components

- **BERT Text Classification**: Fine-tuned for sentiment analysis.
- **Sentence Transformers**: Leveraging Hugging Face Sentence Transformers for encoding comments and calculating similarity.
- **Prompt Engineering**: Crafting effective prompts for the LLM to generate accurate summaries.
- **Integration of Audio Processing**: Converting audio inputs to text for analysis through OpenAI's Whisper.

## Downloading the Models

Due to the large size of the models, they are hosted externally. Please download them from the following link and place them in the `models` directory.

- [Best Model](https://drive.google.com/drive/folders/1VySk4CNoKCt5XY0axclpAg22EOz3C3Dl?usp=drive_link)

**Link to project webpage: https://davidperezcarrasco.github.io/projects/nlp/**
