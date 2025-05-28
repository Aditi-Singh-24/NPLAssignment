# 📄 Document Q&A Bot (FLAN-T5 + FAISS)

Ask questions about any text document using embeddings and a large language model.

---

## ✨ Features

- Upload a .txt file
- Breaks document into chunks
- Embeds chunks + query with Sentence Transformers
- Uses FAISS for semantic search
- Generates answers using FLAN-T5

---

## 🧠 How It Works

1. Upload a plain text file
2. Chunk the text (300 characters)
3. Create embeddings using all-MiniLM-L6-v2
4. Search for the most relevant chunk with FAISS
5. Generate answer using FLAN-T5 model

---

## 🛠️ Installation

Install dependencies:

```bash
pip install sentence-transformers faiss-cpu transformers

or 

pip install -r requirements.txt