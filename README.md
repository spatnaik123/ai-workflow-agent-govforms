# AI Workflow Agent for Smart Government Forms 🇦🇪

An Agentic AI application that automates the understanding, validation, and Q&A for government forms using LangChain, LangGraph, and Streamlit.

## 🔍 Features
- 🧾 Parse and extract fields from PDF-based government forms
- 🧠 Answer questions about forms using Retrieval-Augmented Generation (RAG)
- ✅ Validate form content based on predefined rules
- 🧭 Built with Agentic AI architecture using LangGraph

## 📁 Project Structure
- `agents/`: Agent logic using LangGraph
- `tools/`: Custom tools for parsing, Q&A, and validation
- `workflows/`: Multi-step form processing flow
- `data/`: Sample forms and knowledge base
- `vectorstore/`: Stores embedded documents for retrieval
- `ui/`: Streamlit interface
- `main.py`: Application entry point

## 🚀 Quick Start

```bash
git clone https://github.com/yourusername/ai-workflow-agent-govforms.git
cd ai-workflow-agent-govforms
python -m venv .venv
.venv\Scripts\activate    # or source .venv/bin/activate on macOS/Linux
pip install -r requirements.txt
streamlit run ui/app.py
