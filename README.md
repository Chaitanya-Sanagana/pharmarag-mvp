---
title: PharmaRAG MVP
emoji: 💊
colorFrom: blue
colorTo: indigo
sdk: streamlit
sdk_version: "1.39.0"
python_version: "3.11"
app_file: app.py
pinned: false
---

# 💊 PharmaRAG MVP

A retrieval-augmented AI application for grounded question answering over pharmaceutical and regulatory documents.

PharmaRAG MVP demonstrates how semantic retrieval and document-grounded responses can improve access to complex domain knowledge in life sciences and regulated workflows.

---

## Problem

Pharmaceutical and regulatory documents are often long, dense, and difficult to search efficiently using traditional keyword-based methods.

Teams often need a faster way to:

- Locate relevant policy or guidance content
- Ask natural-language questions over documents
- Review evidence-backed answers
- Reduce manual searching across PDFs

---

## Solution

PharmaRAG MVP enables users to upload and ingest pharmaceutical or regulatory PDFs, run semantic retrieval, and ask questions in natural language.

The system returns:

- Grounded answers
- Citation-aware evidence
- Supporting excerpts from retrieved document content

---

## Key Features

- Upload pharmaceutical and regulatory PDFs
- Chunk and index document content
- Semantic retrieval over prepared documents
- Natural-language question answering
- Grounded responses with citations and excerpts
- Lightweight RAG workflow for domain documents

---

## Technology Stack

- Python
- Streamlit
- PyPDF
- Sentence Transformers
- ChromaDB

---

## How It Works

1. Upload or load supported documents  
2. Ingest and index text into the vector store  
3. Ask a natural-language question  
4. Retrieve the most relevant chunks  
5. Return a grounded answer with supporting evidence  

---

## Project Structure

```text
pharmarag-mvp/
├── app.py
├── requirements.txt
├── README.md
└── ...
```

## Why This Project Matters

This project demonstrates:

- practical retrieval-augmented generation design
- semantic search over domain-specific content
- grounded answer generation patterns
- applied AI for pharmaceutical and regulatory knowledge workflows

## Important Note

This project is a prototype/demo build created to showcase retrieval workflows, semantic search, and grounded AI-assisted document question answering.


---

## 🔗 Links & Attribution

### 🌐 Live Demo
[![Live demonstration link to PharmaRAG MVP on HuggingFace Spaces with yellow and black styling](https://img.shields.io/badge/Demo-HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Chaitanya-Sanagana/pharmarag-mvp)

### 👤 Author
**Chaitanya Sanagana**
[![GitHub profile link for Chaitanya-Sanagana with dark gray background and white text](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Chaitanya-Sanagana)
[![LinkedIn profile link for Chaitanya Sai Sanagana with blue background and white text](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chaitanya-sai-sanagana-8a1827263)
