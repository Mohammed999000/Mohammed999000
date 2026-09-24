<div align="center">

# 🤖 GenAI RAG Chatbot

A production-oriented full-stack Retrieval-Augmented Generation chatbot for private document Q&A.

**Stack:** Next.js · TypeScript · FastAPI · Python · PostgreSQL · Pinecone · Groq · Llama 3 · Docker · AWS EC2

</div>

## Key Features

- 🧠 RAG over PDF, DOCX, and TXT documents
- ⚡ Llama 3 inference through Groq with streaming responses
- 🔐 Google OAuth 2.0 and JWT authentication
- 👤 User-level document and chat isolation
- 🐳 Dockerized frontend, backend, and database
- ☁️ AWS EC2 deployment with optional Cloudflare Tunnel

## Architecture

```text
User → Next.js → FastAPI → PostgreSQL
                    │
                    ├── Pinecone (vector retrieval)
                    └── Groq / Llama 3 (generation)
```

## Local Setup

```bash
git clone https://github.com/mohammed-safwaan9/mohammed-safwaan9.git
cd mohammed-safwaan9/genai-rag-chatbot
docker compose up -d --build
```

> This portfolio copy is maintained under **Mohammed Safwaan's GitHub account**.