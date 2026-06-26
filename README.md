# 🤖 AI-Powered Customer Support Automation System using LangGraph

> **An Intelligent Multi-Agent Customer Support System powered by LangGraph, LangChain, Retrieval-Augmented Generation (RAG), SQLite Memory, and Human-in-the-Loop (HITL) Approval.**

---

# 📖 Overview

The **AI-Powered Customer Support Automation System** is an intelligent multi-agent workflow that automates customer support operations using **LangGraph**.

The system classifies customer queries, routes them to the appropriate support department, retrieves relevant information from a company knowledge base using **Retrieval-Augmented Generation (RAG)**, stores conversation history using **SQLite Memory**, performs **Human-in-the-Loop (HITL)** approval for critical requests, and validates responses using a **Supervisor Agent** before generating the final response.

The project demonstrates how modern AI-powered customer support systems can automate customer service while ensuring accuracy, memory retention, and human supervision for sensitive requests.

---

# 🔗 GitHub Repository

Repository Link:

**https://github.com/SalvaSoumya/CustomerSupportAutomation_agenticai**

---

# 🎯 Project Objectives

- Automatically classify customer queries.
- Route customer requests using LangGraph.
- Retrieve company information using RAG.
- Store customer conversations in SQLite.
- Recall previous customer issues.
- Support Human-in-the-Loop approval.
- Validate responses using a Supervisor Agent.
- Generate accurate final responses.

---

# ✨ Features

- ✅ LangGraph Workflow Orchestration
- ✅ Multi-Agent Customer Support
- ✅ Intent Classification
- ✅ Department Routing
- ✅ Retrieval-Augmented Generation (RAG)
- ✅ FAISS Vector Store
- ✅ HuggingFace Embeddings
- ✅ SQLite Conversation Memory
- ✅ Memory Recall
- ✅ Human Approval Workflow
- ✅ Supervisor Agent
- ✅ Modular Architecture
- ✅ Console-Based Application

---

# 🏢 Supported Support Departments

| Department | Responsibilities |
|------------|------------------|
| **Sales** | Pricing, Product Information, Subscription Plans |
| **Technical Support** | Application Errors, Login Issues, Installation, Configuration |
| **Billing** | Refunds, Payments, Invoices, Billing Queries |
| **Account** | Password Reset, Profile Management, Account Operations |

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| LangGraph | Workflow Orchestration |
| LangChain | RAG Framework |
| FAISS | Vector Database |
| HuggingFace Embeddings | Semantic Search |
| SQLite | Persistent Memory |
| RecursiveCharacterTextSplitter | Document Chunking |
| VS Code | Development Environment |

---

# 🏗️ System Workflow

```
Customer Query
       │
       ▼
Memory Check
       │
       ▼
Intent Classification
       │
       ▼
Department Routing
       │
 ┌─────┼─────┬─────┐
 ▼     ▼     ▼     ▼
Sales Technical Billing Account
       │
       ▼
Approval Check
       │
 ┌─────┴──────────┐
 ▼                ▼
Human Approval  Supervisor Agent
       │           │
       └─────┬─────┘
             ▼
      Save Conversation
        (SQLite Memory)
             ▼
       Final Response
```

---

# 📂 Project Structure

```
CustomerSupportAutomation/
│
├── app.py
├── graph.py
├── state.py
├── nodes.py
├── agents.py
├── approval.py
├── supervisor.py
├── rag.py
├── memory.py
├── utils.py
├── requirements.txt
├── README.md
├── Project_Report.pdf
│
├── database/
│   ├── memory.db
│   └── schema.sql
│
├── knowledge_base/
│   ├── Company_Policy.txt
│   ├── Pricing_Guide.txt
│   ├── Technical_Manual.txt
│   └── FAQ.txt
│
├── workflow/
│   └── workflow_diagram.pdf
│
└── screenshots/
    └── Execution_Screenshots.pdf
```

---

# 🔍 Retrieval-Augmented Generation (RAG)

The project integrates **Retrieval-Augmented Generation (RAG)** to provide accurate responses using company documentation instead of hardcoded answers.

### RAG Pipeline

1. Load Documents
2. Split into Chunks
3. Generate Embeddings
4. Store in FAISS
5. Perform Semantic Search
6. Retrieve Relevant Context
7. Generate Response

### Knowledge Base

- Company Policy
- Pricing Guide
- Technical Manual
- Frequently Asked Questions (FAQ)

---

# 💾 SQLite Memory

Customer conversations are stored using **SQLite**.

Stored Information:

- Customer ID
- Customer Name
- Customer Query

The memory module supports:

- Saving conversations
- Retrieving previous support issues
- Maintaining customer interaction history

---

# 👨‍💼 Human-in-the-Loop (HITL)

Critical customer requests require manual approval before proceeding.

Supported approval scenarios include:

- Refund Requests
- Subscription Cancellation
- Account Closure
- Compensation Requests
- Escalation Requests

---

# 👨‍💻 Supervisor Agent

The Supervisor Agent performs the final validation before responding to the customer.

Responsibilities:

- Review agent responses
- Verify approval status
- Improve response quality
- Generate final response

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/SalvaSoumya/CustomerSupportAutomation_agenticai.git
```

Move to the project directory

```bash
cd CustomerSupportAutomation_agenticai
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the virtual environment

### Windows

```bash
venv\Scripts\activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the Application

```bash
python app.py
```

---

# 🧪 Sample Test Queries

### Sales

```
What are the pricing plans available for your software?
```

### Technical Support

```
My application crashes whenever I upload a file.
```

### Billing

```
I need a refund for my annual subscription.
```

### Account

```
I forgot my account password.
```

### Human Approval

```
Please cancel my subscription.
```

### SQLite Memory

```
What was my previous support issue?
```

---

# 📊 Project Deliverables

- Source Code
- LangGraph Workflow
- RAG Integration
- SQLite Memory
- Human-in-the-Loop Workflow
- Supervisor Agent
- Workflow Diagram
- Project Report
- Execution Screenshots
- SQLite Database

---

# 📈 Future Enhancements

- Large Language Model (LLM) Integration
- Web-based User Interface
- Voice-enabled Customer Support
- Multi-language Support
- CRM Integration
- Cloud Deployment
- Email Automation
- Analytics Dashboard
- AI-based Intent Detection

---

# 👩‍💻 Author

**Salva Soumya**

Integrated M.Tech – Computer Science & Engineering (Data Science)

VIT Vellore

---

# 📚 References

- LangGraph Documentation
- LangChain Documentation
- HuggingFace Sentence Transformers
- FAISS Documentation
- SQLite Documentation
- Python Documentation

---

# ⭐ Acknowledgement

This project was developed as part of an academic assignment to demonstrate the implementation of **LangGraph**, **Retrieval-Augmented Generation (RAG)**, **SQLite Memory**, **Human-in-the-Loop Approval**, and **Multi-Agent Workflow Orchestration** for building an intelligent AI-powered customer support automation system.
