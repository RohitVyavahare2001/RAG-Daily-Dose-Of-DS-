# RAG-Based Resume Query System

This project demonstrates a Retrieval-Augmented Generation (RAG) system to query information from a resume PDF using AI models. It uses LangChain, Hugging Face embeddings, Qdrant vector storage, and Groq API for conversational question-answering.

## Features
- **PDF Processing**: Extract text from PDF resumes and split into chunks.
- **Vector Embeddings**: Generate embeddings using Hugging Face's `all-MiniLM-L6-v2`.
- **Vector Storage**: Store embeddings in Qdrant (in-memory).
- **Conversational AI**: Answer questions using Groq's `qwen-2.5-32b` model.
- **Multi-Turn Conversations**: Supports follow-up questions with conversation history.

## Installation
1. **Clone the repository**:
   ```bash
   git clone [your-repository-url]
   cd [repository-directory]
2.Create virtual environment (optional):
   ```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
