# RAG_PROJECT

A Retrieval Augmented Generation (RAG) system built with Python, LangChain, a vector database, and LLMs. Upload documents and ask questions—answers are generated using semantic search + LLMs.

---

## Features

- Upload and process documents (PDF / Text)
- Generate embeddings
- Store and search using vector database (FAISS / Chroma)
- Retrieves relevant text chunks
- Generates context-aware responses using LLM
- FastAPI API endpoints
- Optional Streamlit UI

---

## Tech Stack

- Python
- LangChain
- OpenAI / HuggingFace
- PyPDF
- Uvicorn

---

## Project Structure

```
RAG_PROJECT/
├── app.py
├── requirements.txt
└── README.md
```

---

## Installation

1. Clone the repo:
```bash
git clone https://github.com/Jenilprajapati01/RAG_PROJECT.git
cd RAG_PROJECT
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate it:
- Windows: `venv\Scripts\activate`
- Mac/Linux: `source venv/bin/activate`

4. Install dependencies:
```bash
pip install -r requirements.txt
```

---

## Setup

Create a `.env` file:
```
OPENAI_API_KEY=your_api_key_here
```

## Use Cases

- PDF Q&A
- Knowledge base assistant
- Research helper
- AI portfolio project

---

## Future Improvements

- Multiple document uploads
- Search improvements
- Conversation memory
- Cloud deployment
- Docker support

---

## Author

Jenil Prajapati

---

## License

Open source for learning and experimentation.
