## Intelligent Document Question Answering System using RAG and Large Language Model

---

##  Project Overview

---

Intelligent Document Question Answering System using RAG and Large Language Models
Overview

The Intelligent Document Question Answering System is a Retrieval-Augmented Generation (RAG) application that allows users to upload PDF documents and ask questions based on their content.

The system extracts text from uploaded PDFs, converts the text into embeddings using Sentence Transformers, stores them in a FAISS Vector Database, retrieves relevant content using semantic search, and generates context-aware answers using a local LLM (Llama 3 via Ollama).

---

## Features

---

- Upload PDF documents
- Extract text from PDF files
- Automatic text chunking
- Semantic search using FAISS
- Retrieval-Augmented Generation (RAG)
- Question Answering using Llama 3
- Local execution using Ollama
- Interactive Streamlit interface

---

##  Technologies Used

---

Python	  : core programming language
Streamlit :	Web Application Framework
PyPDF2    :	PDF Text Extraction
Sentence Transformers : Text Embeddings
FAISS     :	Vector Database
NumPy     :	 Numerical Operations
Requests  : API Communication
Ollama	  : Local LLM Runtime
Llama 3   : Large Language Model

##  Project Structure

---

project/
│
├── app.py
├── README.md
├── requirements.txt
│
├── PDFs/
│   └── sample.pdf
│
└── assets/

---

##  Workflow

---

PDF Upload
   ↓
Extract Text from PDF
    ↓
Split Text into Chunks
    ↓
Generate Embeddings
    ↓
Store Embeddings in FAISS
    ↓
User Asks Question
    ↓
Convert Question to Embedding
    ↓
Retrieve Relevant Chunks
    ↓
Create Context
    ↓
Send Context + Question to LLM
    ↓
Generate Final Answer

---


