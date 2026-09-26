# Automatic-Text-Summarization-Using-NLP


A Python-based extractive text summarization project using Natural Language Processing (NLP).

## Project Overview

This project generates concise summaries from long text by identifying important sentences based on word frequency.

The user provides the input text and specifies the desired number of sentences in the summary.

## Features

- Extractive text summarization
- Word frequency-based sentence scoring
- User-defined summary length
- Stopword removal
- Sentence tokenization
- Simple and fast implementation

## Technologies Used

- Python
- Natural Language Processing (NLP)
- NLTK
- Heap Queue (`heapq`)

## How It Works

1. Take text input from the user.
2. Tokenize the text into words.
3. Remove English stopwords.
4. Calculate the frequency of important words.
5. Tokenize the text into sentences.
6. Calculate a score for each sentence based on word frequency.
7. Select the top-ranked sentences.
8. Display the final summary.

## Installation

Install the required library:

```bash
pip install -r requirements.txt
