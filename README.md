# RAG Chatbot Using Ollama Llama 3.2

## Overview

This project is a Retrieval-Augmented Generation (RAG) Chatbot that answers user questions based on uploaded documents. The chatbot uses semantic search to retrieve relevant content and generates accurate responses using Llama 3.2 through Ollama.

## Features

- Document Upload Support
- Text Chunking
- Embedding Generation
- FAISS Vector Database
- Semantic Search
- Context-Aware AI Responses
- Streamlit User Interface
- Local LLM Integration using Ollama

## Technologies Used

- Python
- Streamlit
- Ollama
- Llama 3.2
- FAISS
- Sentence Transformers
- NumPy

## Project Workflow

1. Upload document
2. Extract text
3. Split text into chunks
4. Generate embeddings
5. Store embeddings in FAISS
6. Retrieve relevant chunks
7. Generate response using Llama 3.2

## Installation

```bash
git clone https://github.com/Madineni-Pradeep-Naidu/RAG-Chatbot---Using-Ollama-Llama-3.2-.git

cd RAG-Chatbot---Using-Ollama-Llama-3.2-

pip install -r requirements.txt

streamlit run app.py
