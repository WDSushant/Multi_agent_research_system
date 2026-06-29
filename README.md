🔍 Multi-Agent Research System using Gemini + LangChain + Streamlit

A production-ready AI-powered research assistant that uses multiple specialized agents to perform deep research, summarize information, critique findings, and generate comprehensive reports.

🚀 Features
🤖 Multi-Agent Architecture
🔎 Intelligent Search Agent
📚 Research Reader Agent
✍️ Report Writer Agent
🧐 Critic Agent
📄 Automatic Research Report Generation
⚡ Powered by Gemini 2.5 Flash
🖥️ Streamlit User Interface
Architecture
                User Query
                     │
                     ▼
              Pipeline Controller
                     │
      ┌──────────────┼──────────────┐
      ▼              ▼              ▼
 Search Agent   Reader Agent   Writer Agent
      │              │              │
      └──────────────┼──────────────┘
                     ▼
               Critic Agent
                     │
                     ▼
             Final Research Report
Tech Stack
Python
LangChain
Google Gemini API
Streamlit
Tavily Search API
Python-dotenv
Installation

Clone the repository

git clone https://github.com/yourusername/research-system.git
cd research-system

Create Virtual Environment

python -m venv venv

Activate Virtual Environment

Windows

venv\Scripts\activate

Linux/Mac

source venv/bin/activate

Install Dependencies

pip install -r requirements.txt
Environment Variables

Create a .env file

GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
TAVILY_API_KEY=YOUR_TAVILY_API_KEY
Run Streamlit
streamlit run app.py
Example

Input

Latest advancements in Artificial Intelligence

Output

Research Summary
Important Sources
Final AI Generated Report
Future Improvements
PDF Export
Citation Support
Memory Agent
Planner Agent
Web Browsing
Vector Database Integration
RAG Pipeline
Multi-modal Research
