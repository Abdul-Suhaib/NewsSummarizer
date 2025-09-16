📰 NewsSummarizer

An AI-powered news summarization tool that combines semantic search, extractive summarization, and abstractive summarization to deliver concise, topic-specific summaries from large news corpora.

🚀 Features

Summarization

Abstractive summaries with FLAN-T5

Extractive summaries with Sumy

ETL Pipeline

Ingests and preprocesses raw articles

Stores processed data in AWS S3 (Parquet format)

Runs on AWS EC2 for scalable computing

Semantic Search

Embeddings generated with Cohere

Relevance measured via cosine similarity

Interactive Chat Interface

Built with Streamlit

Mimics a ChatGPT-like experience for query-based summarization

📊 Dataset

This project leverages the CNN/DailyMail dataset, a benchmark in text summarization research.

Source: News articles from CNN and the Daily Mail

Size: ~300K news articles with human-written highlights (summaries)

Usage in this project:

Articles are processed through the ETL pipeline and stored in S3

Paired summaries are used to evaluate abstractive summarization models like FLAN-T5

Preprocessed content supports semantic search and extractive summarization

🔗 CNN/DailyMail dataset on Hugging Face

🛠️ Tech Stack

Models: FLAN-T5, Sumy

Search: Cohere embeddings + cosine similarity

Interface: Streamlit

Cloud: AWS S3, AWS EC2

Data: CNN/DailyMail dataset
