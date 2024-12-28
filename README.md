# Document Question Answering with LangChain and Streamlit

This project is an interactive web application that allows users to upload a PDF document, process its content, and ask questions about it. The app combines **Retrieval-Augmented Generation (RAG)** with OpenAI's GPT-3.5 to provide accurate and context-aware answers.

---

## Features
- **PDF Upload**: Upload any PDF document for analysis.
- **Document Chunking**: Processes and splits the document into manageable chunks for better embedding and retrieval.
- **Semantic Search**: Uses **HuggingFace embeddings** to store and retrieve relevant chunks based on user queries.
- **RAG Workflow**: Combines the document's context with OpenAI's GPT-3.5 to generate answers.
- **Direct GPT Comparison**: Provides both RAG-based answers and direct GPT-3.5 responses for comparison.

---

## Installation

### Prerequisites
- Python 3.8 or higher
- OpenAI API key (stored in a `.env` file)
