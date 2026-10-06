# 📚 Multi-Document Knowledge Assistant

An AI-powered **Retrieval-Augmented Generation (RAG)** system that allows users to ask questions from multiple PDF documents and receive answers grounded in the uploaded documents.

## 🚀 Features

* Upload and process multiple PDF documents
* Ask questions about the uploaded documents
* Semantic search for relevant information
* AI-generated answers based on retrieved document content
* Displays relevant document sources
* Shows page numbers for retrieved information
* Helps students quickly find information from multiple study materials

## 🧠 How It Works

The system follows a basic **RAG (Retrieval-Augmented Generation)** workflow:

```text
PDF Documents
      ↓
Document Loading
      ↓
Text Extraction
      ↓
Text Chunking
      ↓
Embeddings
      ↓
Vector Database
      ↓
Semantic Search
      ↓
Relevant Context
      ↓
LLM
      ↓
AI Answer + Sources
```

## 🛠️ Technologies Used

* Python
* RAG
* Large Language Models (LLMs)
* NLP
* Semantic Search
* Text Embeddings
* Vector Database
* PDF Processing
* Jupyter Notebook

## 🎯 Use Case

This project is designed especially for students who have to study from multiple PDF documents.

Instead of manually searching through every PDF, users can ask a question and the system retrieves relevant information from the documents and generates an answer based on that context.

## 📁 Project Structure

```text
Multi_Document_Knowledge_Assistant/
│
├── Multi_Document_Knowledge_Assistant_RAG.ipynb
├── README.md
└── .gitignore
```

## 🔍 Example

A user can upload multiple study PDFs and ask:

> "What is the difference between supervised and unsupervised learning?"

The system searches the uploaded documents, retrieves relevant content, and generates an answer along with the source document and page number.

## 💡 Key Learning

Through this project, I learned about:

* Retrieval-Augmented Generation (RAG)
* Document ingestion
* Text chunking
* Embeddings
* Vector search
* Context retrieval
* LLM-based question answering
* Reducing hallucinations by grounding responses in source documents

## 👩‍💻 Developed By

**Simran**

BCA Student | AI/ML Enthusiast
