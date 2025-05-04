# RAG-PDF-Q&A
# 📄 PDF Question Answering App using RAG (Retrieval-Augmented Generation)

This is a simple but powerful Retrieval-Augmented Generation (RAG) app built with:

- 🧠 [LangChain](https://www.langchain.com/)
- 🤗 [Hugging Face Transformers](https://huggingface.co/)
- 🔍 FAISS (Facebook AI Similarity Search)
- 💻 [Gradio](https://gradio.app/) for UI
- 📄 PDF document loader and chunking

---

## 🚀 Try the Live Demo

👉 [https://huggingface.co/spaces/MadhuBehera/RAG-PDF]

---

## 🔍 What it Does

- Upload a **PDF** containing hundreds of Q&A, documents, or notes  
- The app splits and indexes the content into vector embeddings  
- Ask **natural language questions**, and it retrieves relevant chunks  
- A pre-trained Hugging Face model (Flan-T5) answers your question based on the context

---

## 🛠️ Tech Stack

| Feature         | Tool/Library                        |
|----------------|--------------------------------------|
| LLM             | `google/flan-t5-base` (Hugging Face) |
| Embeddings      | `sentence-transformers/all-MiniLM-L6-v2` |
| Vector DB       | FAISS                              |
| Document Loader | `PyPDFLoader` (LangChain)           |
| UI              | Gradio                             |

---

## 📦 Installation

```bash
git clone https://github.com/your-username/pdf-qa-rag-app.git
cd pdf-qa-rag-app

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
