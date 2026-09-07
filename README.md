# Stephen Odhiambo

**Machine Learning Engineer | AI Systems | MLOps**

I build intelligent systems at the intersection of machine learning, software engineering, and AI applications. Focused on production-ready implementations: agentic workflows, retrieval-augmented generation (RAG), ML pipelines, and full-stack AI products.

---

## What I Build

- **Agentic AI Systems**: Multi-agent orchestration using LangGraph, LangChain, and CrewAI for complex reasoning workflows
- **Retrieval-Augmented Generation (RAG)**: Domain-specific knowledge systems with vector databases, semantic search, and hybrid retrieval
- **ML Pipelines**: End-to-end implementations covering data ingestion, feature engineering, model training, evaluation, and deployment
- **Full-Stack AI**: Backend APIs (FastAPI), frontend interfaces (React, Streamlit), and integrated systems
- **MLOps**: Experiment tracking (MLflow), hyperparameter optimization (Optuna), containerization (Docker), CI/CD automation

---

## Featured Projects

### 🎯 **PromptHire: AI Interview Simulation Platform**
**Full-stack interview evaluation system with LLM-powered interviews and structured feedback**

- **Problem**: Candidates need realistic, role-aware interview practice with detailed feedback
- **Technical Approach**: 
  - PDF CV extraction (PyMuPDF) + job description parsing
  - LangGraph stateful workflow with interrupts for human-in-the-loop evaluation
  - Three interview rounds (behavioral, technical, system design) with LLM-generated questions
  - Structured evaluation using Pydantic models
  - Per-round feedback with scores and improvement recommendations
- **Architecture**: React 19 + TypeScript frontend (Vite), FastAPI backend, LangGraph orchestration, multi-LLM support (Groq, Gemini, OpenAI)
- **Key Features**: Thread-based state management, checkpoint persistence, role-aware questioning, structured outputs
- **Repository**: [AI_interview_simulation_platform](https://github.com/steve601/AI_interview_simulation_platform)

### 🤖 **Agentic Goal Planner**
**Intelligent assistant that converts natural language goals into actionable weekly plans**

- **Problem**: Goal-setting requires breaking down abstract goals into specific, time-bound actions
- **Technical Approach**:
  - LangGraph multi-agent workflow with specialized nodes (goal extraction, timeline generation, planning, motivation)
  - Conversational state management with message history
  - GroqCloud LLM integration for fast inference
- **Stack**: LangGraph, LangChain, Streamlit, GroqCloud
- **Evaluation**: Interactive feedback loop, user-guided refinement
- **Repository**: [agenticGoalPlanner](https://github.com/steve601/agenticGoalPlanner)

### 📊 **Fraudulent Transaction Detection**
**ML pipeline for real-time fraud prediction with experiment tracking and hyperparameter optimization**

- **Problem**: Detect fraudulent transactions from transaction metadata with high precision/recall balance
- **Technical Approach**:
  - Feature engineering from transaction context (location, velocity, device trust)
  - Logistic Regression with Optuna hyperparameter tuning
  - Experiment tracking and artifact management via MLflow
  - Nested run structure for trial organization
- **Architecture**: Python data pipeline → MLflow experiment tracking → Optuna optimization → Flask inference API
- **Metrics Tracked**: Precision, recall, F1-score, accuracy across trials
- **Deployment**: Flask web application, GitHub Actions CI pipeline
- **Repository**: [FraudlentTransactionPrediction](https://github.com/steve601/FraudlentTransactionPrediction)

### 🏥 **AI Clinical Triage System**
**LLM-powered medical assistant for symptom extraction and clinical case classification**

- **Problem**: Rapidly classify patient cases based on free-text symptoms using medical guidelines
- **Technical Approach**:
  - Natural language extraction of clinical indicators (wheeze, cough, fever, chest indrawing)
  - Structured classification into conditions (bronchiolitis, pneumonia, asthma)
  - LangGraph modular architecture with extendable nodes and rules
  - Streaming responses via Streamlit UI
- **Stack**: LangGraph, LangChain, OpenAI models, Streamlit
- **Medical Logic**: Guidelines-driven classification with explainable reasoning
- **Repository**: [AIhealth-Triage_System](https://github.com/steve601/AIhealth-Triage_System)

### 🎓 **ChatKU: Campus RAG Assistant**
**Production RAG system for university document retrieval and conversational Q&A**

- **Problem**: University staff and students need fast, accurate access to institutional information (admissions, timetables, policies)
- **Technical Approach**:
  - Document ingestion: PyPDF for parsing university documentation
  - Chunking strategy optimized for institutional documents
  - Hybrid retrieval combining keyword and vector search
  - LangChain retrieval chain with memory for multi-turn conversations
- **Stack**: LangChain, ChromaDB/vector store, Gradio (UI), ChatGroq LLM
- **Deployment**: Deployed on Hugging Face Spaces (public access)
- **Domain-Specific**: Customized knowledge base for Kenyatta University
- **Repository**: [chatKURAG_app](https://github.com/steve601/chatKURAG_app)

### 🔍 **GitHab: Codebase Understanding Agent**
**AI system for semantic understanding of Python repositories using AST parsing and RAG**

- **Problem**: Developers need high-context conversations with their codebases (architecture, dependencies, patterns)
- **Technical Approach**:
  - AST parsing to extract functions, classes, and dependency graphs
  - Dual-stream indexing: raw code chunks + LLM-generated summaries
  - Pinecone vector database with namespace isolation
  - LangGraph multi-agent workflow (understand → retrieve → analyze → answer)
  - Query optimization node that rewrites user intent
- **Stack**: Flask, LangChain, LangGraph, Pinecone, HuggingFace embeddings, Nvidia Nemotron (via OpenRouter)
- **Architecture**: Modular design separating ingestion, AI logic, and vector storage
- **Features**: Repository context persistence, stateful multi-turn conversations, code-aware analysis
- **Repository**: [codebase-Understanding-agent](https://github.com/steve601/codebase-Understanding-agent)

### 📈 **AI Data Analyst**
**Autonomous agent that ingests, cleans, analyzes, and generates reports from datasets**

- **Problem**: Data analysis requires multiple specialized steps; automation accelerates exploratory analysis
- **Technical Approach**:
  - Modular agent architecture: ingestion → cleaning → analysis → visualization → reporting
  - Each agent handles specialized task (outlier detection, missing value handling, statistical analysis)
  - Groq LLM for fast report generation
  - Automated visualization (histograms, heatmaps, pairplots)
- **Stack**: Streamlit, Pandas, Seaborn, Matplotlib, Groq LLM
- **Workflow**: CSV/Excel upload → automated pipeline → interactive visualizations + AI report
- **Repository**: [AI_DataAnalyst](https://github.com/steve601/AI_DataAnalyst)

---

## Technical Capabilities

### Languages & Core
**Python** · SQL · TypeScript · Bash

### Machine Learning & Data Science
**Scikit-learn** · **XGBoost** · **TensorFlow** · **Keras** · **PyTorch** · Pandas · NumPy · Seaborn · Matplotlib

### AI / LLM Applications
**LangChain** · **LangGraph** · **CrewAI** · Hugging Face (Transformers, fine-tuning) · **RAG systems** · Vector databases (Pinecone, ChromaDB) · **Multi-agent orchestration** · Structured outputs (Pydantic)

### MLOps & Infrastructure
**MLflow** · **Optuna** (hyperparameter tuning) · Docker · Git/GitHub · GitHub Actions (CI/CD) · AWS

### Backend & APIs
**FastAPI** · Flask · REST API design · Uvicorn · CORS & middleware

### Frontend
**React** · TypeScript · Streamlit · Vite · Tailwind CSS · Gradio

### Data Engineering
**PySpark** · Pandas · Data pipelines · Feature engineering · Web scraping (BeautifulSoup, Selenium)

---

## Engineering Approach

I focus on building systems that work in production, not prototypes:

- **Reproducible Pipelines**: Experiment tracking via MLflow, version-controlled configurations, deterministic data flows
- **Model Evaluation**: Multi-metric assessment (precision/recall/F1), validation strategies, avoiding data leakage
- **Structured Architectures**: Modular agents, clear state management, testable components
- **Deployment-Ready**: Docker containerization, API design for inference, CI/CD automation
- **Observability**: Logging, metric tracking, graceful error handling
- **Agentic Design**: LangGraph for reliable, debuggable multi-agent workflows over ad-hoc chaining

---

## Currently Exploring

- **Advanced RAG**: Hybrid search, multimodal RAG (images + text), retrieval quality optimization
- **Agentic Reasoning**: LangGraph patterns, planning agents, tool-use orchestration
- **LLM Fine-tuning**: Domain adaptation, efficiency optimization
- **Production AI Systems**: Monitoring, evaluation frameworks, cost optimization

---

## Quick Navigation

| Category | Featured Project |
|----------|------------------|
| **Agentic AI** | [PromptHire Interview Platform](https://github.com/steve601/AI_interview_simulation_platform) · [Goal Planner](https://github.com/steve601/agenticGoalPlanner) |
| **RAG Systems** | [ChatKU Campus Assistant](https://github.com/steve601/chatKURAG_app) · [Codebase Agent](https://github.com/steve601/codebase-Understanding-agent) |
| **ML Pipelines** | [Fraud Detection](https://github.com/steve601/FraudlentTransactionPrediction) |
| **Medical AI** | [Clinical Triage System](https://github.com/steve601/AIhealth-Triage_System) |
| **Data Agents** | [AI Data Analyst](https://github.com/steve601/AI_DataAnalyst) |

---

## Get in Touch

📧 **Email**: odhiambostephen057@gmail.com  
🔗 **LinkedIn**: [stephen-odhiambo-a98890308](https://linkedin.com/in/stephen-odhiambo-a98890308)  
🐙 **GitHub**: [steve601](https://github.com/steve601)

---

*Building AI systems that solve real problems. Always learning, shipping, and iterating.*
