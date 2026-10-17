# 🚀 AI RAG Document Engine (FastAPI + LangChain)

![Python](https://img.shields.io/badge/Python-3.11-blue.svg)
![FastAPI](https://img.shields.io/badge/FastAPI-0.110-00a393.svg)
![AI](https://img.shields.io/badge/LLM-Claude%20%7C%20OpenAI-orange.svg)

Production-ready **Retrieval-Augmented Generation (RAG)** backend microservice designed to parse PDF documents, generate vector embeddings in ChromaDB, and answer complex queries using Large Language Models.

## 🛠️ Tech Stack
- **Language & Framework:** Python 3.11, FastAPI, Uvicorn, Pydantic
- **AI & Orchestration:** LangChain, Anthropic Claude SDK, OpenAI API
- **Vector Store:** ChromaDB
- **Deployment:** Docker, GitHub Actions

## ⚡ Quick Start
```bash
pip install -r requirements.txt
uvicorn app:app --reload --port 8000
