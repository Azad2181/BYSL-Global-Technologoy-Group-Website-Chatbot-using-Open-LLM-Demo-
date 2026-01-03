# BYSL-Global-Technologoy-Group-Website-Chatbot-using-Open-LLM-Demo-
An AI-powered website chatbot built using open-source Large Language Models (LLMs). This project demonstrates how to crawl website content, create vector embeddings, store them in a vector database, and enable intelligent question-answering using LangChain and Retrieval-Augmented Generation (RAG).
---

## 🚀 Features

- Uses **Open-source LLMs (Hugging Face)**
- Website content ingestion and processing
- Text chunking and embedding generation
- **ChromaDB** vector store for semantic search
- **LangChain RetrievalQA** pipeline
- Context-aware chatbot for website FAQs
- Fully local / open-LLM friendly

---

## 🧠 Architecture Overview

1. Website data loading  
2. Text splitting into chunks  
3. Embedding generation  
4. Vector storage using Chroma  
5. Retriever + LLM via LangChain  
6. User query → relevant context → LLM response  

---

## 🛠️ Tech Stack

- **Python 3.9+**
- **LangChain**
- **LangChain Community**
- **ChromaDB**
- **Hugging Face Transformers**
- **Sentence Transformers**
- **BitsAndBytes**
- **BeautifulSoup4 / Unstructured**

---

## 📦 Installation

```bash
pip install -U langchain langchain-community langchain-text-splitters chromadb transformers sentence-transformers bitsandbytes beautifulsoup4 unstructured
```

---

## ▶️ How to Run

```bash
jupyter notebook BYSL_Website_Chatbot_using_Open_LLM.ipynb
```

Run all cells and start asking questions related to the website content.

---

## 📁 Project Structure

```
BYSL_Website_Chatbot_using_Open_LLM.ipynb
README.md
```

---

## 🚧 Future Improvements

- Web UI (Streamlit / FastAPI)
- Multi-website ingestion
- Chat history memory
- Deployment-ready API

---

## 👤 Author

**Abul Kalam Azad**
### Full Stack Data Science and AI Developer LinkedIn: https://www.linkedin.com/in/azad2181/

---

⭐ If you like this project, give it a star on GitHub!
