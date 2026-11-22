# 📄 Document Question Answering with Google Generative AI & Cohere

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline to answer questions based on the content of multiple PDF documents.  
It uses:

- **Google Generative AI Embeddings** (`models/text-embedding-004`) to embed text chunks.
- **ChromaDB** as the vector database for semantic search.
- **Cohere's Command R+ model** to generate concise answers from the most relevant retrieved chunks.

---

## 🚀 Features
- Load and process multiple PDF documents from a directory or ZIP file.
- Split documents into smaller overlapping text chunks for better embedding.
- Generate embeddings using Google’s Generative AI API.
- Store and query embeddings with ChromaDB.
- Retrieve the top-N most relevant chunks for a given question.
- Generate short, context-aware answers using Cohere’s LLM.

---

### 1. Clone the repository
```bash
git clone https://github.com/mohamed-7oda/RAG-System-using-LangChain.git
cd RAG-System-using-LangChain
