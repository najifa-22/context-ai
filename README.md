# ContextAI

ContextAI is an AI-powered system that allows users to upload multiple PDF files and ask questions in natural language. By combining semantic search, vector embeddings, and Retrieval-Augmented Generation (RAG), the system delivers context-aware answers based on the content of the uploaded documents. Built with LangChain, FAISS, Hugging Face models, and Streamlit, the project demonstrates the practical implementation of modern LLM technologies for intelligent document understanding and information retrieval.

## Features

* Upload multiple PDF documents
* Automatic text extraction
* Intelligent text chunking
* Semantic search using vector embeddings
* Conversational question answering
* Retrieval-Augmented Generation (RAG)

## Tech Stack

* Python
* Streamlit
* LangChain
* FAISS
* Hugging Face Transformers
* PyPDF2

## Project Workflow

1. Upload PDF documents
2. Extract text from PDFs
3. Split text into chunks
4. Generate embeddings
5. Store embeddings in FAISS vector database
6. Retrieve relevant document chunks
7. Generate answers using an LLM

## Installation

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Future Improvements

* Source citations for retrieved document chunks
* Persistent chat history and conversation storage
* Support for additional document formats (DOCX, TXT, CSV)
