# RAG Pipeline & Chatbot (n8n)

This repository contains an **n8n workflow JSON** for building a **Retrieval-Augmented Generation (RAG) chatbot**.

## Features
- Google Drive trigger for document ingestion
- Recursive text splitting
- OpenAI embeddings
- Pinecone vector storage
- LLM-based chat agent using OpenRouter
- Real-time chat trigger

## Tech Stack
- n8n
- Pinecone
- OpenAI Embeddings
- Claude 3.5 (via OpenRouter)
- Google Drive API

## Usage
1. Import the JSON file into n8n
2. Configure credentials (Google Drive, OpenAI, Pinecone, OpenRouter)
3. Activate the workflow

