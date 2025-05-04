# 🤖 AI Workflow Agent for Smart Government Forms

An Agentic AI system built using LangChain, LangGraph, and Streamlit to automate triage, validation, and processing of complex government forms (PDFs).

---

## 🔍 Problem Statement

Manual processing of government forms is error-prone and time-consuming. This agent streamlines the process by:
- Parsing uploaded PDFs
- Validating form fields against rules
- Answering questions from embedded content
- Storing extracted info in vector stores for retrieval

---

## 🧠 Core Features

- 🔄 **Agentic Workflow (LangGraph)**: Multi-step decision-making for form handling.
- 🧾 **PDF Parser Tool**: Structured text and field extraction.
- ✅ **Field Validator Tool**: Checks required fields, value formats, and logical dependencies.
- 💬 **Form QnA Tool**: Allows users to ask questions based on PDF contents.
- 🔎 **Retrieval Tool**: Vectorized retrieval from a knowledge base.
- 🌐 **UI with Streamlit**: Upload forms, ask questions, and view results in real-time.

---

## 🧱 Tech Stack

| Layer         | Tools Used                        |
|---------------|----------------------------------|
| Agent Runtime | `LangGraph`, `LangChain`         |
| LLM Backend   | `OpenAI` (can be swapped later)  |
| Parsing       | `PyMuPDF`, `pdfminer`, or similar|
| UI            | `Streamlit`                      |
| Vector Store  | `FAISS` or `Chroma`              |

---

## 📁 Project Structure

ai-workflow-agent-govforms/
├── agents/ # Agent logic (LangGraph)
├── tools/ # Modular tools (PDF parsing, validation, etc.)
├── workflows/ # Agent workflow definitions
├── ui/ # Streamlit UI
├── data/
│ ├── sample_forms/ # Example government forms
│ └── knowledge_base/ # Reference materials
├── vectorstore/ # Embeddings storage
├── main.py # Entrypoint
├── requirements.txt # Python dependencies
└── .env # API keys & configs


---

## 🚀 How to Run (Coming Soon)
To be added after initial implementation.

---

## 📌 Status
🧱 Setting up scaffolding and baseline logic

---

## ✍️ Author
[spatnaik123](https://github.com/spatnaik123)
