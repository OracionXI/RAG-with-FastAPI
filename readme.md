# RAG with FastAPI

A simple **Retrieval-Augmented Generation (RAG)** API built with FastAPI.  
It uses **Chroma** (local vector database) + **Ollama** (local LLM) to answer questions based on ingested documents.

## Features

- Add text documents to the knowledge base dynamically
- Query the RAG system with natural language
- Containerized with Docker
- Ready for Kubernetes deployment (Deployment + Service manifests included)
- Health check endpoint

## Tech Stack

- **Framework**: FastAPI
- **Vector DB**: Chroma (persistent)
- **Embeddings & LLM**: Ollama (default: `tinyllama`)
- **Containerization**: Docker + docker-compose
- **Orchestration**: Kubernetes manifests
