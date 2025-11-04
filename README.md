
# 🩺 AI Medical Chatbot with RAG (HuggingFace & LangChain)

## 📖 Overview
This project implements an **AI-powered Medical Chatbot** designed to provide **reliable healthcare-related responses** using **Retrieval-Augmented Generation (RAG)**.  
The chatbot combines **HuggingFace Transformers**, **LangChain**, and **Vector Databases** to retrieve relevant medical knowledge and generate **context-aware, human-like answers**.  

It represents an **End-to-End AI in Healthcare** project — from data ingestion and embedding generation to conversational retrieval and intelligent response generation.

---

## 🧠 Features
- 🩹 **Medical Query Understanding:** Handles health-related user queries with medical context awareness.  
- 🧩 **RAG Architecture:** Combines document retrieval and language generation for accurate answers.  
- 🧠 **LLM Integration:** Uses HuggingFace transformer models for response generation.  
- 📚 **Knowledge Base Integration:** Retrieves answers from medical documents or datasets stored in vector databases.  
- 💬 **Conversational Interface:** Seamless chatbot interface using Streamlit or Flask.  
- 🔒 **Safe & Ethical AI Responses:** Ensures informative yet non-diagnostic replies (for educational use only).

---

## 🧰 Technologies Used
- **Programming Language:** Python  
- **Frameworks & Libraries:**
  - LangChain – RAG pipeline creation  
  - HuggingFace Transformers – language model for response generation  
  - FAISS / ChromaDB – vector database for knowledge retrieval  
  - Streamlit / Flask – chatbot user interface  
  - OpenAI / HuggingFace API – for LLM integration  
  - PyPDF / Docx / TextLoader – for dataset ingestion  

---

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Medical-Chatbot-RAG.git
   cd Medical-Chatbot-RAG

# README: Setting Up Your Environment with Pipenv

## Prerequisite: Install Pipenv
Follow the official Pipenv installation guide to set up Pipenv on your system:  
[Install Pipenv Documentation](https://pipenv.pypa.io/en/latest/installation.html)

---

## Steps to Set Up the Environment

### Install Required Packages
Run the following commands in your terminal (assuming Pipenv is already installed):

```bash
pipenv install langchain langchain_community langchain_huggingface faiss-cpu pypdf
pipenv install huggingface_hub
pipenv install streamlit




