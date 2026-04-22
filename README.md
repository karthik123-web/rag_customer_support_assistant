


# 🚀 RAG-Based Customer Support Assistant using LangGraph & ChromaDB



## 📌 Project Overview

This project is a **Retrieval-Augmented Generation (RAG) based Customer Support Assistant** that answers user queries using a PDF knowledge base.

Instead of giving random AI responses, the system retrieves relevant information from documents and generates accurate, context-aware answers.

It also uses **LangGraph workflow** and supports **Human-in-the-Loop (HITL)** for escalation in uncertain cases.

---

## 🎯 Problem Statement

Traditional chatbots fail to provide accurate answers because they rely only on trained knowledge.

This system solves that by:
- Using external PDF knowledge base
- Retrieving relevant chunks using embeddings
- Generating responses using LLM
- Adding workflow control using LangGraph

---

## ⚙️ Tech Stack

- Python
- Google Colab
- LangChain
- LangGraph
- ChromaDB (Vector Database)
- HuggingFace Transformers
- PyTorch
- Sentence Transformers

---

## 🧠 System Architecture

1. User Input (Query)
2. PDF Document Loading
3. Text Chunking
4. Embedding Generation
5. Vector Storage (ChromaDB)
6. Similarity Search (Retriever)
7. LLM Response Generation
8. LangGraph Workflow Control
9. HITL Escalation (if required)

---

## 🔄 Workflow

User Query → Embedding Search → Relevant Chunk Retrieval → LLM Processing → Final Answer

If confidence is low → Escalate to Human Support (HITL)

---

## 📂 Project Structure

```plaintext id="structure001"
RAG-Project/
│
├── rag_project.ipynb
├── knowledge_base.pdf
├── HLD.pdf
├── LLD.pdf
├── technical_documentation.pdf
├── requirements.txt
└── README.md
