# 📘 Intelligent Document Question Answering System using RAG and Large Language Models

## 📖 Project Overview

The **Intelligent Document Question Answering System** is an AI-powered application that enables users to upload PDF documents and ask questions based on their content. The system implements **Retrieval-Augmented Generation (RAG)** to provide accurate, context-aware answers by combining semantic search with a Large Language Model (LLM).

Instead of relying solely on the LLM's internal knowledge, the system retrieves relevant information from the uploaded PDF using **Sentence Transformers** and **FAISS**, then passes the retrieved context to a locally running **Llama 3** model through **Ollama**.

---

# 🎯 Objectives

* Build an AI-powered PDF Question Answering system.
* Implement Retrieval-Augmented Generation (RAG).
* Perform semantic search using vector embeddings.
* Generate accurate answers from uploaded documents.
* Demonstrate modern Generative AI architecture.

---

# 🚀 Features

* Upload PDF documents
* Automatic PDF text extraction
* Intelligent text chunking
* Sentence Transformer embeddings
* FAISS Vector Database
* Semantic similarity search
* Context-aware question answering
* Local LLM integration using Ollama
* Beautiful Streamlit web interface
* Technical concepts and RAG workflow visualization

---

# 🛠️ Technologies Used

* Python
* Streamlit
* PyPDF2
* Sentence Transformers
* FAISS
* NumPy
* Requests
* Ollama
* Llama 3

---

# 🏗️ System Architecture

```text
                PDF Upload
                     │
                     ▼
           Extract Text from PDF
                     │
                     ▼
            Split Text into Chunks
                     │
                     ▼
        Generate Sentence Embeddings
                     │
                     ▼
          Store Embeddings in FAISS
                     │
                     ▼
             User Asks Question
                     │
                     ▼
        Convert Question to Embedding
                     │
                     ▼
         Retrieve Relevant Chunks
                     │
                     ▼
      Context + Question → Llama 3
                     │
                     ▼
          Generate Final Answer
```

---

# ⚙️ Working Process

### Step 1

Upload a PDF document.

### Step 2

Extract readable text from every page.

### Step 3

Split large text into overlapping chunks.

### Step 4

Generate embeddings using Sentence Transformers.

### Step 5

Store embeddings inside FAISS.

### Step 6

Accept the user's question.

### Step 7

Perform semantic search.

### Step 8

Retrieve the most relevant chunks.

### Step 9

Send Context + Question to Llama 3.

### Step 10

Display the generated answer.

---

# 🧠 AI Concepts Used

* Retrieval-Augmented Generation (RAG)
* Large Language Models (LLM)
* Semantic Search
* Vector Embeddings
* Vector Databases
* Prompt Engineering
* Information Retrieval
* Natural Language Processing
* Transformer Models

---



### Install Dependencies

```bash
pip install streamlit
pip install PyPDF2
pip install sentence-transformers
pip install faiss-cpu
pip install requests
pip install numpy
```

or

```bash
pip install -r requirements.txt
```

---

# Install Ollama

Download and install **Ollama**.

Pull the Llama 3 model:

```bash
ollama pull llama3
```

Run the model:

```bash
ollama run llama3
```

---

# ▶️ Run the Application

```bash
streamlit run app.py
```

---

# 📚 Workflow

1. Upload PDF
2. Extract Text
3. Create Chunks
4. Generate Embeddings
5. Store in FAISS
6. Ask Question
7. Retrieve Context
8. Generate Answer

---

# 📊 Advantages

* Faster document search
* Accurate answers
* Context-aware responses
* Works completely offline using Ollama
* No internet required after model download
* Scalable RAG architecture

# 🔮 Future Enhancements

* Multiple PDF support
* Chat history
* Conversation memory
* OCR support for scanned PDFs
* Multi-language document support
* Citation and source highlighting
* Cloud deployment
* Voice-based question answering



# 👨‍💻 Author

**Rushikesh Hanumant Gade**

AI | Machine Learning | Deep Learning | Generative AI Enthusiast

---

