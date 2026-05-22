# Google ADK Agentic RAG

An end-to-end **Agentic RAG (Retrieval-Augmented Generation)** application built using Google’s **Agent Development Kit (ADK)** and Gemini models.

This project demonstrates how to build intelligent AI agents capable of:

* Retrieving context-aware information from documents
* Performing semantic search
* Using reasoning + tool orchestration
* Generating grounded responses with citations
* Building scalable agentic workflows using Google ADK

The repository serves as a practical implementation of modern **Agentic AI + RAG architectures** using the Google ecosystem. ([Adk][1])

---

# Features

* ✅ Agentic RAG workflow
* ✅ Google ADK integration
* ✅ Gemini-powered reasoning
* ✅ Retrieval-Augmented Generation
* ✅ Vector-based semantic retrieval
* ✅ Modular agent architecture
* ✅ Grounded AI responses
* ✅ Extensible tool ecosystem
* ✅ Production-ready project structure
* ✅ Environment-based configuration

---

# Tech Stack

| Component     | Technology                        |
| ------------- | --------------------------------- |
| LLM           | Gemini                            |
| Framework     | Google ADK                        |
| RAG           | Retrieval-Augmented Generation    |
| Embeddings    | Google Embedding Models           |
| Vector Search | Vector Store / Semantic Retrieval |
| Language      | Python                            |
| Environment   | dotenv                            |
| AI Platform   | Google AI / Vertex AI             |

---

# Project Architecture

```text
User Query
    │
    ▼
Agent (Google ADK)
    │
    ├── Query Understanding
    ├── Tool Invocation
    ├── Retrieval Pipeline
    │       │
    │       ▼
    │   Vector Database
    │       │
    │       ▼
    │   Relevant Context
    │
    ▼
Gemini LLM
    │
    ▼
Grounded Response
```

---

# Repository Structure

```text
google-adk-agentic-rag/
│
├── agents/                # Agent definitions
├── tools/                 # Custom ADK tools
├── rag/                   # RAG pipeline logic
├── prompts/               # Prompt templates
├── utils/                 # Utility functions
├── data/                  # Documents / datasets
├── notebooks/             # Experiment notebooks
├── requirements.txt
├── .env.example
├── app.py                 # Main application entry point
└── README.md
```

---

# Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/bhattbhavesh91/google-adk-agentic-rag.git
cd google-adk-agentic-rag
```

---

## 2. Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

#### Mac/Linux

```bash
source venv/bin/activate
```

#### Windows

```bash
venv\Scripts\activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Configure Environment Variables

Create a `.env` file.

Example:

```env
GOOGLE_API_KEY=your_google_api_key
PROJECT_ID=your_project_id
LOCATION=us-central1
MODEL_NAME=gemini-1.5-pro
```

---

# Running the Application

```bash
python app.py
```

---

# How It Works

## Step 1 — Document Ingestion

Documents are loaded and processed into chunks.

---

## Step 2 — Embedding Generation

Embeddings are created using Google embedding models.

---

## Step 3 — Vector Storage

The embeddings are stored inside a vector database for semantic retrieval.

---

## Step 4 — Query Understanding

The ADK agent interprets the user query and determines retrieval strategy.

---

## Step 5 — Retrieval

Relevant chunks are fetched using similarity search.

---

## Step 6 — Response Generation

Gemini generates a grounded answer using retrieved context.

---

# Example Use Cases

* Enterprise document search
* AI knowledge assistants
* Internal company copilots
* Research assistants
* PDF question-answering systems
* Customer support automation
* Multi-document querying
* Agentic workflows with retrieval

---

# Sample Query

```text
"What are the key architectural components described in the uploaded document?"
```

---

# Example Response

```text
The document describes the following components:

1. Retrieval Layer
2. Embedding Pipeline
3. Agent Orchestration
4. Vector Search
5. LLM Response Generation

These components work together to enable grounded AI responses.
```

---

# Google ADK Overview

Google ADK is an open-source framework for building production-grade AI agents with orchestration, tool usage, memory, and workflow capabilities. ([Adk][1])

Key capabilities include:

* Multi-agent systems
* Tool integration
* Workflow orchestration
* Context management
* Cloud-native deployment
* Evaluation and observability

---

# Why Agentic RAG?

Traditional RAG pipelines are often static.

Agentic RAG improves this by enabling agents to:

* Dynamically decide retrieval strategies
* Use tools intelligently
* Perform reasoning before answering
* Chain multiple retrieval operations
* Handle complex multi-step queries

This results in better grounding, reduced hallucinations, and more reliable outputs. ([DeepWiki][2])

---

# Extending the Project

You can enhance this repository by adding:

* Hybrid search
* Reranking
* Multi-agent orchestration
* Memory systems
* Graph RAG
* Web search tools
* Evaluation pipelines
* Streaming responses
* Authentication
* UI dashboards

---

# Deployment Options

The project can be deployed using:

* Docker
* Google Cloud Run
* Vertex AI
* GKE
* Local server
* FastAPI backend

---

# Recommended Improvements

* Add conversation memory
* Add citation tracking
* Introduce query rewriting
* Add observability/logging
* Add agent evaluation framework
* Integrate LangSmith/OpenTelemetry
* Add authentication layer

---

# Learning Resources

* [Google ADK Documentation](https://adk.dev/?utm_source=chatgpt.com)
* [Google ADK Samples](https://github.com/google/adk-samples?utm_source=chatgpt.com)
* [Vertex AI RAG Engine Docs](https://google.github.io/adk-docs/tools/google-cloud/vertex-ai-rag-engine/?utm_source=chatgpt.com)

---

# Contributing

Contributions are welcome.

Feel free to:

* Open issues
* Submit pull requests
* Improve documentation
* Add new agents/tools
* Enhance RAG capabilities

---

# License

This project is licensed under the MIT License.

---

# Acknowledgements

* Google ADK Team
* Gemini API
* Vertex AI
* Open-source AI community

---

# Author

Built by Bhavesh Bhatt

GitHub: [bhattbhavesh91](https://github.com/bhattbhavesh91?utm_source=chatgpt.com)

[1]: https://adk.dev/?utm_source=chatgpt.com "Agent Development Kit (ADK) - Agent Development Kit (ADK)"
[2]: https://deepwiki.com/Shubhamsaboo/awesome-llm-apps/3.1-basic-rag-implementation?utm_source=chatgpt.com "Gemini Agentic RAG | Shubhamsaboo/awesome-llm-apps | DeepWiki"
