# 🧠 Multi-Document Conversational RAG Chatbot

A **FastAPI-based intelligent chatbot** capable of answering questions from multiple uploaded documents using **Retrieval-Augmented Generation (RAG)**.  
It integrates **LangChain**, **FAISS**, **Google GenAI**, and **Groq LLMs**, combining retrieval-based reasoning with advanced language understanding.

This system allows users to upload multiple files (PDF, DOCX, TXT), automatically process them into searchable vector embeddings, and then interact conversationally with the content — getting context-rich, non-redundant, and diverse answers through **MMR (Maximal Marginal Relevance)** retrieval.

---

## 🚀 Key Highlights

- 📄 **Multi-file Document Support:** Upload multiple `.pdf`, `.docx`, and `.txt` files simultaneously.  
- 🧠 **Retrieval-Augmented Generation (RAG):** Combines vector retrieval with LLM-based reasoning for context-aware responses.  
- 🔍 **MMR-Based Retrieval:** Ensures diverse, non-repetitive document results by balancing relevance and diversity.  
- ⚡ **FastAPI Backend:** RESTful API endpoints for upload and conversational chat with session management.  
- 🗂️ **FAISS Vector Store:** High-performance embedding storage and similarity search.  
- 🧩 **LangChain Integration:** Manages document chunking, embedding, and contextual prompting.  
- 🔐 **Dynamic Model Loading:** Supports **Google GenAI** and **Groq** LLMs through a flexible YAML configuration.  
- 🐳 **Dockerized Deployment:** Ready for deployment across any environment (local or cloud).  

---

## 🏗️ System Architecture

