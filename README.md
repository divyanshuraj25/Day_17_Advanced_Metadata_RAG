# Day 17 - Advanced Retrieval with Metadata

This project implements a metadata-aware Retrieval-Augmented Generation
(RAG) retrieval system using Sentence Transformers and FAISS.

## Features

- Metadata-based document storage
- Text chunking with metadata preservation
- Sentence Transformer embeddings
- FAISS vector similarity search
- Category filtering
- Source filtering
- Date-based filtering
- Document type filtering
- Normal vs metadata-filtered retrieval comparison
- Five-query retrieval evaluation
- Precision comparison

## Metadata Fields

- source
- category
- date
- document_type

## Retrieval Function

filtered_retrieve(query, filters)

## Technologies

- Python
- Sentence Transformers
- FAISS
- NumPy
- Pandas
- Google Colab

## Key Learning

Metadata filtering helps restrict vector retrieval to documents
that satisfy specific conditions such as category, source and date.
