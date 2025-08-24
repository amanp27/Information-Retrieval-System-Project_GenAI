# 📘 Information Retrieval System with RAG
An AI-powered Information Retrieval System where users can upload PDFs and ask questions.
The application reads the document, extracts context, and provides accurate answers. If a question is not related to the document, the system responds with:

❌ "The question is not related to the uploaded file."

### 🚨 Problem It Solves
In today’s fast-paced world, people often deal with large PDF documents such as research papers, books, contracts, or medical guidelines. Manually reading and searching through hundreds of pages to find specific answers is time-consuming, inefficient, and prone to human error.

👉 Our Information Retrieval System solves this problem by enabling users to simply upload a PDF and ask natural language questions. The system uses RAG (Retrieval Augmented Generation) with embeddings and an LLM to provide context-aware, human-like answers. If a query is outside the scope of the uploaded file, the system smartly responds that the question is not related to the document.

---

### 🚀 Features

* ✅ Upload any PDF document
* ✅ Ask contextual questions about the document
* ✅ Out-of-context question handling
* ✅ Conversational memory with ConversationBufferMemory
* ✅ Fast and efficient retrieval using FAISS Vector Store
* ✅ Simple and interactive Streamlit UI

### 🛠️ Tech Stack

* LLM: Google Gemini 1.5 Flash

* RAG Pipeline: LangChain

* Vector Store: FAISS

* Embeddings: Gemini Embeddings

* Memory: ConversationBufferMemory

---

### Use Cases
Highlight practical applications (helps recruiters imagine business value):

* 📚 Research paper summarization

* 🏥 Medical guideline lookup

* ⚖️ Contract analysis

* 🎓 E-learning support


### 📂 Project Structure
```
📦 information-retrieval-system
├── 📁 data/                # Sample PDFs
├── 📁 modules/             # Helper functions
│   ├── loader.py           # PDF loading & text extraction
│   ├── splitter.py         # Chunking and preprocessing
│   ├── embeddings.py       # Convert text to embeddings
│   ├── retriever.py        # FAISS retriever
│   └── qa_chain.py         # QA pipeline with Gemini
├── app.py                  # Streamlit main app
├── requirements.txt        # Dependencies
└── README.md               # Project documentation
```

### 🔮 Future Enhancements

* Support for multiple file uploads

* Multi-language support

* Summarization feature

* Deployment on AWS/GCP

### 👨‍💻 Author

Aman Prajapati

Language: Python
