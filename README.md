# 🚀 Enterprise RAG Assistant (Generative AI Project)

## 📌 Project Overview
Enterprise RAG Assistant is a **production-ready Generative AI application** that allows organizations to chat with internal documents using AI.

The system uses **Retrieval Augmented Generation (RAG)** to retrieve relevant company knowledge and generate accurate answers using a Local LLM.

This project simulates a real-world **Enterprise AI Knowledge Assistant** used in companies.

---

## 🧠 Problem Statement
Companies store large amounts of documents like:

- HR Policies
- Company Guidelines
- Technical Documentation
- Internal Knowledge Base

Finding information manually is slow.

✅ This system enables:
- Intelligent document search
- AI-powered question answering
- Private offline AI assistant

---

## ⚙️ Tech Stack

| Component | Technology |
|-----------|------------|
| Backend API | FastAPI |
| LLM | Llama3 (Ollama) |
| Framework | LangChain |
| Vector Database | ChromaDB |
| Embeddings | HuggingFace |
| Deployment | Docker |
| Language | Python |

---

## 🏗️ Architecture

User Question  
↓  
FastAPI API  
↓  
Retriever (Chroma Vector DB)  
↓  
Relevant Document Chunks  
↓  
Llama3 LLM  
↓  
AI Generated Answer

---

## 📂 Project Structure
enterprise-rag-assistant/
│
├── app/
│ ├── ingest.py
│ ├── chat.py
│ ├── api.py
│
├── data/
│ └── company_docs/
│
├── vectordb/
│
├── requirements.txt
├── Dockerfile
└── README.md
