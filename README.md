# 🧠 AI Enterprise Knowledge Discovery Agent

> Transform scattered enterprise documents into a living, queryable knowledge graph powered by AI.

An intelligent agent that searches enterprise repositories, discovers hidden relationships between entities, generates actionable insights, and automatically updates organizational knowledge using **GraphRAG**, **Neo4j**, **Gemini AI**, and **Semantic Search**.

---

## 🎯 What It Does

- 📂 **Ingests** documents (PDF, DOCX, TXT, MD)
- 🔍 **Extracts** entities (people, orgs, projects, concepts) using LLMs
- 🕸️ **Builds** a knowledge graph in Neo4j revealing hidden connections
- 💡 **Discovers** non-obvious relationships and patterns
- 🎯 **Answers** natural-language questions using GraphRAG
- 📊 **Generates** insights and auto-updates organizational knowledge

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **GraphRAG** | Hybrid graph + vector retrieval |
| **Graph DB** | Neo4j |
| **LLM** | Google Gemini API |
| **Vector Store** | ChromaDB |
| **Backend** | FastAPI (Python) |
| **Frontend** | React + Vite + Tailwind CSS |
| **Database** | SQLite + Neo4j + ChromaDB |

---

## 🚀 Features

- 📄 Multi-format document ingestion
- 🧩 Intelligent chunking & preprocessing
- 🔗 Entity & relationship extraction via Gemini
- 🕸️ Interactive knowledge graph visualization
- 💬 GraphRAG-powered chat interface
- 💡 Automated insight generation
- 🔍 Semantic + hybrid search
- 📊 Analytics dashboard
- ⚙️ CPU-friendly (no GPU required)

---

## 📁 Project Structure

\`\`\`
ai-knowledge-discovery-agent/
├── backend/          # FastAPI backend
├── frontend/         # React UI
├── database/         # Neo4j + SQLite + ChromaDB
├── data/             # Uploads, samples, exports
├── docs/             # Documentation
├── docker/           # Docker configs
└── scripts/          # Setup scripts
\`\`\`

---

## ⚡ Quick Start

### Prerequisites
- Python 3.11+
- Node.js 18+
- Neo4j (Docker recommended)
- Gemini API Key

### Backend Setup
\`\`\`bash
cd backend
python -m venv venv
venv\\Scripts\\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
\`\`\`

### Frontend Setup
\`\`\`bash
cd frontend
npm install
npm run dev
\`\`\`

### Neo4j (Docker)
\`\`\`bash
docker-compose up -d neo4j
\`\`\`

---

## 🔑 Environment Variables

Create \`backend/.env\`:

\`\`\`
GEMINI_API_KEY=your_gemini_api_key_here
NEO4J_URI=bolt://localhost:7687
NEO4J_USER=neo4j
NEO4J_PASSWORD=password
CHROMA_PERSIST_DIR=./database/chroma
DATABASE_URL=sqlite:///./database/sqlite/app.db
\`\`\`

---

## 📚 Documentation

- [Architecture](docs/ARCHITECTURE.md)
- [API Reference](docs/API_REFERENCE.md)
- [Setup Guide](docs/SETUP_GUIDE.md)
- [User Guide](docs/USER_GUIDE.md)

---

## 🎯 Roadmap

- [x] Project scaffolding
- [ ] Backend core (FastAPI + Neo4j + Gemini)
- [ ] Document ingestion pipeline
- [ ] Entity & relationship extraction
- [ ] Knowledge graph builder
- [ ] GraphRAG query engine
- [ ] Insight generator
- [ ] React frontend
- [ ] Graph visualization
- [ ] Deployment

---

## 🤝 Contributing

This is a personal practice project. Contributions, issues, and feature requests are welcome!

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Vishakha**
- GitHub: [@vishakha2121](https://github.com/vishakha2121)

---

⭐ **Star this repo if you find it helpful!**