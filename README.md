# RAG Chatbot using Pinecone and n8n

## Overview
Built an end-to-end Retrieval-Augmented Generation (RAG) system for semantic document question answering.

## Features
- Automated document ingestion
- Recursive text chunking
- OpenAI Embeddings
- Pinecone Vector Storage
- AI Agent-based retrieval
- Conversational memory
- Context-aware responses

## Architecture

### Document Ingestion Pipeline

Google Drive Trigger
↓
Document Loader
↓
Recursive Text Splitter
↓
OpenAI Embeddings
↓
Pinecone Vector Store

### Query Pipeline

User Query
↓
AI Agent
↓
Retriever
↓
Conversational Memory
↓
OpenRouter LLM
↓
Response

## Workflow Screenshots

<img width="1738" height="721" alt="image" src="https://github.com/user-attachments/assets/69a483b0-7655-4ae7-bc8a-bfaebaadc699" />

## Tech Stack

- n8n
- Pinecone
- OpenRouter
- OpenAI Embeddings
- AI Agents

## Challenges

- Chunk size optimization
- Embedding quality
- Retrieval accuracy

## Future Improvements

- Multi-document support
- Source citations
- Hybrid search
