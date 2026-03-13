# AI Document Intelligence Platform Architecture

User
↓
React Frontend
↓
FastAPI Backend
├── Document Inventory API
├── Search API
├── Grounded Answer API
├── Comparison API
├── Clause Extraction API
└── Risk Analysis API
↓
Document Processing Pipelines
├── PDF Parsing
├── Chunking
├── Embedding Generation
└── Metadata Logging
↓
Storage Layer
├── Parsed JSON Documents
├── Chunked JSON Files
├── Metadata CSVs
└── PostgreSQL + pgvector
↓
AI Layer
├── Embedding Model
└── Grounded Answer Generation Model
