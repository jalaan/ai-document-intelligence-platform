# AI Content & Contract Intelligence Platform

An enterprise-style AI system designed for media and entertainment organizations to search, analyze, and extract insights from contracts, licensing agreements, and internal documents using semantic search and grounded LLM responses.

This platform simulates how streaming, music, and production companies can modernize document-heavy workflows across content, legal, and business teams.

---

## Project Overview

Media companies operate on complex ecosystems of contracts, licensing agreements, and content-related documentation. Critical business decisions often depend on quickly understanding:

- Licensing terms and usage rights  
- Revenue-sharing agreements  
- Artist and vendor contracts  
- Content distribution restrictions  
- Compliance and policy requirements  

However, this information is typically buried across large volumes of unstructured documents.

This platform transforms those documents into a **searchable, AI-powered knowledge system**, enabling teams to retrieve accurate, explainable answers in seconds.

---

## Core Capabilities

- Document ingestion for contracts, policies, and licensing agreements  
- Intelligent chunking optimized for long-form legal and media documents  
- Embedding generation and vector storage using pgvector  
- Semantic search across document collections  
- Retrieval-augmented generation (RAG) for grounded responses  
- Source citations including document name, page, and section  
- Retrieval confidence scoring for transparency  
- API-first design for integration into internal tools  

---

## Media Industry Use Cases

This system is designed to mirror real workflows in media and entertainment:

- **Content Licensing Analysis**  
  Quickly identify usage rights, territories, and restrictions across licensing agreements  

- **Artist & Vendor Contract Review**  
  Extract payment terms, obligations, and renewal clauses  

- **Royalty and Revenue Understanding**  
  Surface revenue-sharing structures and financial obligations  

- **Production & Legal Support**  
  Enable faster review of contracts and reduce manual legal analysis  

- **Content Operations & Strategy**  
  Provide quick access to content-related rules that impact distribution and monetization  

---

## Architecture

End-to-end pipeline:

Document → Chunking → Embeddings → Vector Database → Retrieval → LLM → UI

This reflects modern AI systems used by media companies to operationalize internal knowledge and reduce dependency on manual document review.

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
- Tailwind CSS  
- Vite  

Infrastructure  
- Docker  
- REST API architecture  
- Vector database design  

---

## Screenshots

### Application Interface
![Homepage](docs/screenshots/homepage.png)

### AI Question Input
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

## How It Works

1. Documents such as contracts and policies are ingested and parsed  
2. Content is split into semantically meaningful chunks  
3. Embeddings are generated and stored in a vector database  
4. User queries are embedded and matched against stored vectors  
5. Relevant document sections are retrieved  
6. The LLM generates a response grounded in retrieved context  
7. Citations and similarity scores are returned for transparency  

---

## Key Design Principles

- Explainability through source-backed answers  
- Trust via retrieval confidence scoring  
- Scalability for large document collections  
- Modularity through API-driven architecture  
- Alignment with real-world media workflows  

---

## Business Impact

This platform demonstrates how AI can transform media operations:

- Reduces time spent reviewing contracts and agreements  
- Improves speed and accuracy of content-related decision-making  
- Enables cross-functional teams (legal, finance, content) to access information independently  
- Creates a foundation for AI-driven content intelligence systems  

---

## Why This Matters for Media Companies

Media organizations rely heavily on structured understanding of contracts and content rights.

This project shows how AI can:

- Turn static documents into dynamic, queryable assets  
- Support faster deal analysis and negotiations  
- Improve operational efficiency across content lifecycle workflows  
- Enable scalable knowledge access across global teams  

---

## Running the Project

### Start Backend

```bash
cd backend
uvicorn app.main:app --reload
