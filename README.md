# 📄 Gemini-Powered RAG QA System

An end-to-end **Retrieval-Augmented Generation (RAG)** system that allows users to upload PDF documents and ask questions based on their content. The system leverages **Google Gemini API**, **LlamaIndex**, and **FAISS** to deliver accurate, context-aware answers.

---

## 🚀 Live Demo

🔗 https://qa-system-using-llamaindex.onrender.com/

---

## 📌 Features

* 📄 Upload and process PDF documents
* 🔍 Semantic search using FAISS vector database
* 🤖 Context-aware answer generation using Gemini LLM
* ⚡ Fast retrieval using embeddings
* 🔁 Retry mechanism for API rate limits
* 🌐 Deployed using Streamlit on Render

---

## 🎯 How It Works

1. User uploads a PDF document
2. Document is split into chunks
3. Each chunk is converted into embeddings
4. Embeddings are stored in FAISS vector database
5. User asks a question
6. Relevant chunks are retrieved
7. Gemini LLM generates a final answer

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

GOOGLE_API_KEY=your_api_key_here

### 4️⃣ Run the Application

```bash
streamlit run StreamlitApp.py
```

---

## 📸 Application Demo

This system demonstrates real-time document-based question answering using Retrieval-Augmented Generation (RAG).

### 🔹 Upload & Query Interface

![Upload Interface](https://raw.githubusercontent.com/Ajaykodthiwada/QA-System-LlamaIndex/main/Screenshot%202026-04-01%20222152.png)

---

### 🔹 Answer Generation

![Answer Output](https://raw.githubusercontent.com/Ajaykodthiwada/QA-System-LlamaIndex/main/Screenshot%202026-04-01%20222212.png)

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

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
