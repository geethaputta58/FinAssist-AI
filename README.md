FinAssist AI — Intelligent Banking Support Assistant (RAG + Urgency Detection)

FinAssist AI is an intelligent banking support assistant that combines Retrieval-Augmented Generation (RAG), urgency detection, and multi-turn conversational memory to deliver fast, accurate, and context-aware customer assistance. It retrieves answers from banking manuals and loan policy documents while identifying high-priority requests such as emergency loan needs.

Features
🔍 RAG-Based Document Retrieval

Extracts information from banking manuals, loan policies, and FAQs

Ensures accurate, policy-aligned responses

⚠️ Urgency Detection

Classifies high-priority cases such as emergency medical loans or urgent account issues

Enables faster handling of time-sensitive requests

🧠 Conversation Memory

Maintains multi-turn context for natural, human-like interactions

Understands follow-up questions and user intent

🏦 Banking Domain Support

Loan eligibility guidance

Policy explanation

Account and service-related Q&A

Tech Stack

Python

LangChain

OpenAI GPT / Llama

FAISS or Chroma vector store

FastAPI / Streamlit



How It Works

User submits a banking query

Urgency detector flags critical requests

RAG retrieves the most relevant document chunks

LLM generates a final, context-aware answer

Memory manager keeps interaction flow smooth

Getting Started

Install dependencies:

pip install -r requirements.txt


Run API:

python app/api.py


Optional UI:

streamlit run app/ui.py

Use Cases

Emergency loan assistance

Loan documentation guidance

Banking policy Q&A

General account support
