# LLM-Book-Recommendation

## Introduction

This project explores the development of a book recommendation system leveraging the capabilities of Llama2, a state-of-the-art large language model (LLM).

## Overview of Language Models
![](llama.jpeg)

Language models are AI systems designed to understand, generate, and manipulate human language. They are trained on extensive datasets comprising diverse text sources, enabling them to learn the intricacies of language, context, and meaning. Llama2, a state-of-the-art LLM, is part of the second generation of the Llama model family. It is known for its ability to generate coherent and contextually relevant text, making it ideal for tasks like text completion, translation, and, in this case, book recommendations.

Llama2's architecture is based on transformer models, which use self-attention mechanisms to capture the relationships between words in a sentence. This allows the model to consider the context of each word and generate more accurate and meaningful predictions. As a result, Llama2 can understand user queries and preferences and match them with suitable books, making it an excellent choice for a recommendation system.

## Dataset

The dataset provides close to seven thousand books containing identifiers, title, subtitle, authors, categories, thumbnail url, description, published year, average rating, and number of ratings. The dataset is provided as comma-delimited CSV.

Kaggle Link: [Dataset](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)

### Environment


```BASH
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
```

```BASH
ollama run
ollama pull llama2
```
