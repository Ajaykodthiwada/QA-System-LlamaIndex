# 📄 Gemini-Powered RAG QA System

An end-to-end **Retrieval-Augmented Generation (RAG)** system that allows users to upload documents and ask questions based on their content. The system uses **Google Gemini API**, **LlamaIndex**, and **FAISS** to deliver accurate, context-aware answers.

---

## 🚀 Live Demo

🔗 https://qa-system-using-llamaindex.onrender.com/

---

## 📌 Features

* 📄 Upload PDF documents
* 🔍 Semantic search using FAISS vector database
* 🤖 Context-aware answer generation using Gemini LLM
* ⚡ Fast and efficient retrieval with embeddings
* 🔁 Retry mechanism for handling API rate limits
* 🌐 Deployed using Streamlit on Render

---

## 🏗️ System Architecture

1. Upload PDF
2. Convert text into chunks
3. Generate embeddings
4. Store embeddings in FAISS
5. Retrieve relevant chunks
6. Generate answer using Gemini

---

## 🛠️ Tech Stack

* **LLM:** Google Gemini (Gemini-2.5 Flash)
* **Framework:** LlamaIndex
* **Vector Store:** FAISS
* **Frontend:** Streamlit
* **Deployment:** Render
* **Language:** Python

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Ajaykodthiwada/QA-System-LlamaIndex.git
cd QA-System-LlamaIndex
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Set Environment Variable

Create a `.env` file or set:

```
GOOGLE_API_KEY=your_api_key_here
```

### 4️⃣ Run the Application

```bash
streamlit run StreamlitApp.py
```

---

## 📸 Screenshots




---

## 📊 Key Learnings

* Implemented end-to-end RAG pipeline
* Learned vector embeddings and semantic search
* Integrated LLM APIs with real-world applications
* Built and deployed ML application using Streamlit

---

## 🚧 Future Improvements

* Multi-document support
* Persistent vector database (Pinecone / Qdrant)
* Conversational memory
* Hybrid search (BM25 + vector search)

---

## 👨‍💻 Author

**Ajay Kodthiwada**
🔗 GitHub: https://github.com/Ajaykodthiwada

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
