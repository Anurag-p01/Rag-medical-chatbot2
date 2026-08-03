# 🩺 AI Medical Chatbot (RAG-Based)

An AI-powered Medical Chatbot built using **Python, Streamlit, LangChain, Hugging Face Embeddings, and Llama 3 (Groq)**. The chatbot uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from documents and generate context-aware responses.

## 🚀 Features
- AI-powered medical question answering
- Retrieval-Augmented Generation (RAG) pipeline
- PDF document processing and text chunking
- Semantic search using Hugging Face Embeddings
- Interactive Streamlit web interface
- Fast response generation using Llama 3 via Groq

## 🛠️ Tech Stack
- Python
- Streamlit
- LangChain
- Hugging Face Embeddings
- Groq API
- Llama 3
- PyPDF
- Vector Similarity Search

## 📂 How It Works
1. Load medical documents (PDFs).
2. Split documents into smaller text chunks.
3. Generate vector embeddings.
4. Retrieve the most relevant content for a user's query.
5. Generate a context-aware response using Llama 3.

## ▶️ Run the Project

```bash
pip install -r requirements.txt
streamlit run app.py
