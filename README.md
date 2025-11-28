**FinAssist AI — Banking Support Assistant (RAG + Urgency Detection)**

FinAssist AI is an intelligent banking support assistant that uses Retrieval-Augmented Generation (RAG), urgency detection, and conversation memory to help users get accurate, fast, and context-aware answers to banking queries. The system can retrieve information from banking manuals, loan documents, and FAQs, while detecting urgent customer needs such as emergency medical loans.

✨ Features
🔍 **RAG-Based Answer Retrieval**

Pulls information directly from banking manuals, policies, and FAQs

Ensures responses remain accurate and compliant with official guidelines

⚠️ **Urgency Detection**

Detects critical requests (e.g., emergency loans, urgent account issues)

Helps prioritize time-sensitive customer needs

🧠**Multi-Turn Conversation Memory**

Remembers previous messages

Provides smooth, natural, context-aware responses

🏦 **Banking Domain Support**

Loan eligibility assistance

Account & service-related help

Policy explanation and guidance

🛠 **Tech Stack**

Python

LangChain

OpenAI GPT / Llama

FAISS or Chroma (for vector search)

FastAPI / Streamlit (for API or UI)



▶️ **How It Works**

User asks a banking question

Urgency detector checks if the request is critical

RAG retrieves relevant text from documents

LLM generates a clear, contextual response

Memory keeps the conversation flowing naturally

🚀 **Getting Started**
Install dependencies
pip install -r requirements.txt

Run API
python app/api.py

Optional Streamlit UI
streamlit run app/ui.py

💡 Example Use Cases

Emergency loan guidance

Loan document requirements

FAQ-based customer support

General banking policy queries

Account help & support
