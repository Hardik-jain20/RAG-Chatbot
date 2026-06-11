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

Google Drive
↓
Document Loader
↓
Text Splitter
↓
OpenAI Embeddings
↓
Pinecone

User Query
↓
AI Agent
↓
Retriever
↓
OpenRouter LLM
↓
Response

## Workflow Screenshots

(insert screenshots)

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
