#  Rudra Yadav

### Building Stateful AI Agents, RAG Pipelines & MCP Servers

> I am a 3rd-year (5th-semester) BCA student specializing in Computer Networking & Cyber Security, with a focus on **agentic AI**, **multi-agent systems** and **LLM-powered applications**. I don't just write API wrappers: I build workflows with feedback loops, retrieval pipelines, and tool-calling agents backed by real databases and secured endpoints.

Currently seeking an **AI / ML Engineering Internship** where I can contribute to production-oriented AI systems and grow through real engineering work.

---

## 🛠️ Core Engineering Stack

| Domain | Technologies |
| :--- | :--- |
| **AI Orchestration** | ![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white) ![Google Gemini](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=flat&logo=google&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-Model%20Context%20Protocol-000000?style=flat) ![FastMCP](https://img.shields.io/badge/FastMCP-5A4FCF?style=flat) |
| **Retrieval & Vector Ops** | ![FAISS](https://img.shields.io/badge/FAISS-004A7C?style=flat&logo=meta&logoColor=white) ![Vertex AI](https://img.shields.io/badge/Vertex%20AI%20Embeddings-4285F4?style=flat&logo=googlecloud&logoColor=white) ![PyMuPDF](https://img.shields.io/badge/PyMuPDF-PDF%20Processing-D9534F?style=flat) |
| **Backend & Data** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white) |
| **Data Sources** | ![Yahoo Finance](https://img.shields.io/badge/Yahoo_Finance-720E9E?style=flat&logo=yahoo&logoColor=white) ![SerpAPI](https://img.shields.io/badge/SerpAPI-4285F4?style=flat&logo=google&logoColor=white) |
| **Frontend & Infra** | ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) |

*(I also have a solid foundation in DBMS, Data Structures & Algorithms, Computer Networks and Cyber Security, which helps me build AI backends that are secure as well as smart.)*

---

## 🚀 Featured Projects

### 💸 [Expense Tracker with AI + MCP](https://github.com/Ruddrayadav/Expense-Tracker-with-ai-mcp-)
**Stack:** FastMCP · Gemini · LangChain · PostgreSQL (Supabase) · Streamlit
*   **The System:** A remote MCP server exposing 6 expense tools (add, list, update, delete, summarize, monthly report) over HTTP, backed by Supabase PostgreSQL.
*   **The Agent:** A Gemini tool-calling agent that discovers the MCP tools at runtime and turns messages like *"spent 250 on lunch"* into database actions, with history windowing, step limits and output truncation to control token cost.
*   **Security:** Constant-time Bearer API-key verification (the server refuses to start without a key), parameterized queries, input validation, row-level security, and a password-gated Streamlit client.

### 📈 [Autonomous AI Equity Analyst](https://github.com/Ruddrayadav/autonomous-equity-analyst)
**Live App:** https://autonomous-equity-analyst-dur8wbrzizh5s6t6ikvqre.streamlit.app | **Stack:** LangGraph · LangChain · Gemini · yfinance · SerpAPI · Pydantic
*   **The System:** A stateful multi-agent financial research pipeline that retrieves market data, performs financial and qualitative analysis, and generates structured equity reports.
*   **The Logic:** A dedicated **Reviewer Agent** validates the pipeline state with Pydantic schemas. Missing or invalid metrics trigger a self-correcting retrieval loop before the report is generated.

### 🗄️ Text-to-SQL Clarification Engine
**Stack:** LangGraph · Gemini · PostgreSQL · SQLAlchemy · Streamlit
*   **The System:** A stateful Text-to-SQL workflow with an **Ambiguity Agent** that detects missing information and asks targeted clarifying questions instead of silently guessing.
*   **The Safety Net:** A self-correcting retry loop for failed queries, and generated SQL runs through a strictly **read-only PostgreSQL role** on Supabase.

### ⚖️ Legal Document Simplifier
**Stack:** LangChain · Vertex AI Embeddings · FAISS · PyMuPDF · Streamlit
*   **The System:** Summarizes legal documents, extracts key clauses, highlights risks and penalties, and offers interactive document Q&A.
*   **The Logic:** PDF processing and semantic retrieval with FAISS, plus risk/fairness visualizations and highlighted PDF output.

### 📄 AI-Powered Resume Analyzer
**Stack:** Python · LangChain · Streamlit · PDF Parsing
*   Separate candidate and HR workflows: resume summaries and feedback, plus job-description matching that surfaces match scores, strengths and skill gaps.

---

## 🎓 Education & Learning

*   **BCA (Computer Networking & Cyber Security)**, Galgotias University, 2023 – 2027 (currently 3rd year)
*   Oracle Certified Foundations Associate · Agentic AI (Oracle) · Introduction to Generative AI (Simplilearn)
*   Gen AI Exchange Hackathon 2025 (Google Cloud) · 5-Day AI Agents Intensive with Google (Kaggle) · AI Voice Agents Challenge (Murf AI)

---

## 📬 Let's Build Together
**Looking for an intern who can ship real AI systems? Let's talk.**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rudra-yadav-9a787b284/)
[![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/rudray_05)
