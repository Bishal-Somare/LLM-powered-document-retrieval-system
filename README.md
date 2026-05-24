# LLM-Powered Document Retrieval System

A Retrieval-Augmented Generation (RAG) application built using Python, LangChain, Hugging Face Embeddings, Mistral AI, Vector Store, and Streamlit.

This system allows users to upload PDF documents and ask questions based on the document contents using semantic search and LLM-powered response generation.

---

# Features

- PDF document upload
- Automatic text chunking
- Hugging Face embeddings
- Vector database storage
- Semantic similarity search
- Retriever-based contextual retrieval
- LLM-generated responses using Mistral AI
- Interactive Streamlit interface

---

# Tech Stack

- Python
- LangChain
- Hugging Face Embeddings
- Mistral AI
- Chroma Vector Store
- Streamlit

---

# System Workflow

```text
User Uploads PDF
        ↓
Text Extraction
        ↓
Text Chunking
        ↓
Embedding Generation
        ↓
Vector Store
        ↓
User Query
        ↓
Query Embedding
        ↓
Retriever Semantic Search
        ↓
Relevant Chunks
        ↓
LLM (Mistral AI)
        ↓
Generated Response
```

---



---

# Installation

## Clone Repository

```bash
git clone https://github.com/Bishal-Somare/LLM-powered-document-retrieval-system.git

cd LLM-powered-document-retrieval-system
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Environment Variables

Create a `.env` file in the root directory.

Example:

```env
MISTRAL_API_KEY=your_api_key_here
HF_TOKEN=your_huggingface_token_here
```

---

# Run the Application

```bash
streamlit run app.py
```

---

# How the System Works

1. The uploaded PDF is processed and text is extracted
2. The text is divided into smaller chunks
3. Chunks are converted into vector embeddings
4. Embeddings are stored inside a vector database
5. User queries are converted into embeddings
6. Retriever performs semantic similarity search
7. Relevant document chunks are retrieved
8. Retrieved context is passed to the LLM
9. LLM generates a contextual response

---

# Learning Outcomes

This project helped in understanding:

- Retrieval-Augmented Generation (RAG)
- Vector Embeddings
- Semantic Search
- Retriever Pipelines
- LLM Integration
- LangChain Workflows
- Vector Databases

---

# Future Improvements

- Multi-document support
- Conversational memory
- Source citations
- Hybrid search
- Cloud deployment
- Authentication system

---


# Author

Bishal Somare
