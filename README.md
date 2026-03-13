# AI Document Intelligence Platform

An enterprise-style AI system that enables users to ask questions about internal documents using semantic search and grounded LLM responses.

The system processes PDFs, generates embeddings, stores them in a vector database, and retrieves relevant document excerpts to produce explainable AI answers with citations.

---

## Features

- Document ingestion and chunking
- Embedding generation
- Vector search using pgvector
- Retrieval-augmented generation (RAG)
- Source citations for explainability
- FastAPI backend
- React + Tailwind frontend

---

## Architecture

Document → Chunking → Embeddings → pgvector → Retrieval → LLM → UI

---

## Tech Stack

Backend
- Python
- FastAPI
- PostgreSQL
- pgvector
- OpenAI API

Frontend
- React
- TypeScript
- TailwindCSS
- Vite

Infrastructure
- Docker
- Vector database
- REST API

---

## Screenshots

### Application Interface

![Homepage](docs/screenshots/homepage.png)

### AI Question input

![Question Input](docs/screenshots/question-input.png)

### AI Generated Answer

![Answer](docs/screenshots/ai-answer.png)

### Retrieval Confidence

![Retrieval Confidence](docs/screenshots/retrieval-confidence.png)

### Source Citations

![Citations](docs/screenshots/citations.png)

### API Documentation

![API](docs/screenshots/api-docs.png)

### Project Structure

![Structure](docs/screenshots/project-structure.png)

---

## Running the Project

### Start Backend

