# Hi, I'm Gopal 👋

**Senior Data Scientist · RAG / GraphRAG · LLM systems · M.Sc. Physics (NIT Calicut)**

I build retrieval and reasoning systems that hold up under measurement: layout-aware document RAG, knowledge-graph
multi-hop QA, and the evaluation harnesses that keep them honest. Before ML, I trained as a physicist
(CSIR-UGC NET AIR 81, IIT JAM AIR 469); my M.Sc. project was on renormalization in QED, and I still use AI as a
tool for physics.

### What I work on
- **Graph retrieval for multi-hop QA:** bidirectional meet-in-the-middle traversal over 50k-node LightRAG graphs,
  with local cross-encoder answer seeding.
- **Document RAG that respects layout:** heading hierarchies recovered from typography, tables kept intact, no LLM
  in the chunking loop.
- **LLM platforms in production:** async FastAPI + Celery + Redis inference, guardrails (prompt injection, PII,
  hallucination), distillation and quantization.
- **AI for physics:** symbolic + learned methods for QFT renormalization.

### Projects

| Repo | What it is | Headline |
|---|---|---|
| [openai-budget-guard](https://github.com/gopalsharma1615-ai/openai-budget-guard) | Per-key, per-task token and $ budgets for OpenAI keys: preflight blocking, SQLite ledger, proxy, CLI | Atomic reservations, so concurrent calls can't overshoot; openai SDK 1.x–3.x |
| layout-rag *(in progress)* | Layout-aware naive RAG: PDF → typography-aware chunks → hybrid retrieval → local rerank | Benchmarked on OHR-Bench and FinanceBench vs LangChain / Docling chunkers |
| graphwalk-rag *(in progress)* | Graph RAG: build, store (NetworkX/Neo4j), and three retrievers incl. meet-in-the-middle walk | HotpotQA multi-hop, accuracy by hop vs LightRAG modes |
| qft-renorm-ai *(in progress)* | One-loop QED renormalization in code, plus AI experiments on running couplings | Symbolic regression on PDG α_s data; LLM vs LLM+CAS on loop calculations |
| rag-mcp-server *(in progress)* | MCP server exposing document and graph retrieval as tools for any AI client | Tool-using agent vs fixed pipeline |

### Stack
Python · PyTorch · Hugging Face · sentence-transformers · LightRAG · Neo4j · Milvus · FastAPI · Celery · Redis ·
SymPy · Docker

📫 [LinkedIn](https://www.linkedin.com/in/gopal-sharma-943012145) · gopalsharma.1615@gmail.com
