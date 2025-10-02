# 🤖 ERP Assistant

ERP Assistant is a demo application built with .NET 9 + Blazor Server.  
It is currently presented as a showcase site (with plans for a future WPF or Electron desktop version)   
to explore how AI tools can integrate with ERP-like systems on the .NET platform.

---

## Features

At this stage, ERP Assistant provides **three AI-powered modules**:

---

### 🔹 Chatbot (AI Assistant)
- Semantic Kernel orchestration (integration with LLM)
- RAG Service (Postgres + pgvector)
- Embedding Service (ONNX embeddings + tokenizer)
- Prompt system
  
## sample
![chatbot-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/a8c24c85-b68f-4d06-bf6c-8b3feed9abb1)

---

### 🔹 AI Views (Safe ERP Generator)
AI-assisted module for generating ERP views from natural language queries
- Semantic Kernel orchestration (integration with LLM)
- SQL Sandbox Pipeline
- Prompt System

## sample
![views2-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/dd7f98c3-e749-4943-9b2b-dcb762f2a96e)


---

### 🔹 AI Modules (Forecasting)
- **CRM Forecasting** for sales prediction  
  - All sales  
  - By category  
  - By product  
- Historical data fetched from SQL via EF Core  
- Forecast powered by **ML.NET SSA time-series forecasting**  

## sample
![forecasting-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/9ae89b07-63c2-4449-b4b2-0b53bc1c5b33)


---

## Tech Stack
- .NET 9 + Blazor Server  
- Entity Framework Core   
- Microsoft SQL Server  
- Semantic Kernel
- Groq LLM API  
- PostgreSQL + `pgvector`  
- ONNX Runtime
- Bert
- HuggingFace MiniLM embeddings  
- ML.NET (SSA Forecasting)  

---

## Work in Progress

In the near future:  
- Extended chatbot memory and external tool integration  
- Safer and more powerful AI-driven ERP views  
- New AI modules tailored to ERP/CRM workflows  

