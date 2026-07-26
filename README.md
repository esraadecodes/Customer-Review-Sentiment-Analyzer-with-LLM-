# Customer-Review-Sentiment-Analyzer-with-LLM-
AI-Powered Airline Review Topic Modeling & Insights Pipeline
An advanced Natural Language Processing (NLP) pipeline designed to extract, cluster, and analyze granular customer service topics and sentiments from airline reviews using BERTopic, Sentence-Transformers, and Large Language Models (LLMs).

Project Overview
Customer feedback data is often unstructured, massive, and difficult to parse at scale. This project automates the extraction of meaningful categories from raw customer reviews. By combining state-of-the-art embedding models with zero-shot prompting and LLM-driven representations, the pipeline transforms messy text into structured, actionable business intelligence.

Key Features
Custom Embedding Generation: Leverages BAAI/bge-base-en-v1.5 sentence embeddings to capture semantic nuances in customer feedback.
Hybrid Representation Modeling: Combines KeyBERT-inspired keyword extraction with LLM-generated topic naming (compatible with OpenAI and Groq APIs).
Zero-Shot Topic Mapping: Aligns unstructured reviews directly to predefined business domains (e.g., Seating Comfort, Baggage Handling, Flight Disruptions).
Flexible Backend Support: Easily switch between OpenAI models and fast open-source inference providers (like Groq's Llama 3).

Tech Stack
Python

BERTopic & HDBSCAN
Sentence-Transformers
Pandas / NumPy
OpenAI / Groq API
