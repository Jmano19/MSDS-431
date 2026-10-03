---
title: "Yelp Restaurant Recommendation Chatbot"
---

# Yelp Restaurant Recommendation Chatbot

## Overview

A conversational restaurant recommendation system combining retrieval, embeddings, large language models, and sentiment analysis.

## Technologies

Python · FAISS · OpenAI Embeddings · LLMs · Gradio · BERT

## Architecture

User queries are processed through a conversational interface and matched against restaurant information using vector similarity search.

Relevant restaurant and review information is retrieved using FAISS and passed to the language model to generate recommendations.

A sentiment analysis model is also used to analyze restaurant reviews.

## Key Components

- Vector embeddings
- FAISS similarity search
- Retrieval-augmented generation
- Large language models
- Restaurant review sentiment analysis
- Gradio conversational interface