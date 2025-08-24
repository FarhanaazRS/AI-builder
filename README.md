# AI-builder

![React](https://img.shields.io/badge/Frontend-React.js-61DAFB?logo=react&logoColor=white)
![FastAPI](https://img.shields.io/badge/Backend-FastAPI-009688?logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/Database-PostgreSQL-336791?logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/VectorDB-ChromaDB-purple)
![OpenAI](https://img.shields.io/badge/LLM-OpenAI-412991?logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/LLM-Gemini-4285F4?logo=google&logoColor=white)
![License](https://img.shields.io/badge/License-Educational-blue)

A **No-Code/Low-Code Intelligent Workflow Builder** that enables users to visually create and interact with workflows using drag-and-drop components. The system integrates document knowledge, Large Language Models (LLMs), and web search to deliver intelligent responses through a chat interface.

---

## 🚀 Features
- **Drag & Drop Workflow Builder** with [React Flow](https://reactflow.dev/)
- **User Query Component** – entry point for user questions
- **KnowledgeBase Component** – upload & process documents (PDFs), extract text, generate embeddings, store/retrieve context
- **LLM Engine Component** – query LLMs (OpenAI GPT, Gemini), integrate SerpAPI for web search
- **Output Component** – chat interface for displaying responses
- **Workflow Validation & Execution**
- **Optional Features**:
  - Workflow persistence
  - Chat history
  - Execution logs
  - User authentication

---

## 🛠️ Tech Stack
- **Frontend**: React.js, React Flow  
- **Backend**: FastAPI  
- **Database**: PostgreSQL  
- **Vector Store**: ChromaDB (or similar)  
- **Embeddings**: OpenAI / Gemini embeddings  
- **LLMs**: OpenAI GPT, Gemini  
- **Text Extraction**: PyMuPDF  
- **Web Search**: SerpAPI / Brave  

---

## 📂 Project Structure
AI-builder/
│── backend/ # FastAPI backend
│ ├── api/ # API endpoints
│ ├── models/ # Database models
│ ├── services/ # LLM, embeddings, search integrations
│ ├── main.py # FastAPI entry point
│ └── requirements.txt # Backend dependencies
│
│── frontend/ # React.js frontend
│ ├── components/ # UI components (React Flow, chat, config panel)
│ ├── pages/ # Main pages
│ ├── App.js # Root React component
│ └── package.json # Frontend dependencies
│
│── database/ # PostgreSQL schemas / migrations
│── docs/ # Documentation (optional)
│── README.md # Project readme
