<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Mohit%20Barse&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%E2%80%94%20RAG%20Systems%20%7C%20Multimodal%20AI%20%7C%20Production%20Pipelines&descAlignY=60&descSize=14" alt="header" />

<p>
  <a href="https://www.linkedin.com/in/mohit-b-9a997b301/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://x.com/mohitkb22">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" />
  </a>
  <a href="mailto:mohitbarse2230@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

</div>

---

## About me

I'm an AI/ML engineer focused on building **retrieval-augmented generation systems** and **multimodal AI applications** that work reliably in production — not just in notebooks.

My work sits at the intersection of LLM engineering, backend systems, and applied ML. I care about the full pipeline: from data ingestion and vector indexing to API deployment and output quality.

- Currently deepening expertise in **MLOps**, **FastAPI** deployment patterns, and model evaluation
- Building toward owning end-to-end AI pipelines — data in, intelligent output out
- Occasionally sharing engineering thoughts on **[@mohitkb22](https://x.com/mohitkb22)**

---

## Tech stack

**Core languages:** Python · JavaScript

**AI / LLM:** LangChain · OpenAI API (GPT-4o, GPT-4V) · FAISS · Embeddings · Prompt engineering

**ML / Data:** TensorFlow · Keras · scikit-learn · OpenCV · Pandas · Plotly

**Backend & infra:** FastAPI · PostgreSQL · Docker · Git

---

## Projects

### [LLM Research Agent](https://github.com/MohitKB22/rag-multimodal-engine)

An autonomous research agent that takes a user query, plans a multi-step investigation, and returns a synthesized, cited answer — without manual intervention.

```
Query → Planner → [Web Search | arXiv Retrieval | PDF Ingestion]
                              ↓
                    Vector Memory (FAISS) → Reasoning Loop → Report
```

**Key design choices:**
- **Planner-executor loop:** the agent breaks a research question into sub-tasks, executes each tool call, reflects on gaps, and re-queries until confident
- **arXiv + web search tools:** retrieves live papers and sources, not just pre-indexed docs
- **PDF ingestion pipeline:** downloaded papers are chunked, embedded, and stored in a per-session FAISS vector store for grounded retrieval
- **Code execution tool:** can run analysis snippets to verify numerical claims or summarize tabular data from papers
- **Structured output:** final report includes section summaries, key findings, and inline citations back to source documents
- Built with `LangChain Agents` · `FAISS` · `arXiv API` · `pdfplumber` · `GPT-4o` · `FastAPI`

---

### [Stock Analytics Hub](https://github.com/MohitKB22/stock-analytics-hub)

Interactive dashboard for Nifty and equity market data — real-time visualization, trend analysis, and pattern detection.

Built with `Python` · `Streamlit/Dash` · `Pandas` · `Plotly`

---

### [Care AI Engine](https://github.com/MohitKB22/care-ai-engine)

Conversational AI for healthcare — symptom intake, intelligent triage routing, and patient-facing Q&A.

Built with `JavaScript` · NLP · AI APIs

---

### [Fingerprint Blood Group Prediction](https://github.com/MohitKB22/Fingerprint-Based-BloodGroup-Prediction)

End-to-end CNN pipeline predicting blood group from fingerprint images — from raw image preprocessing through classification. A research-oriented deep learning project exploring biometric correlates.

Built with `Python` · `TensorFlow/Keras` · `OpenCV`

---

## Architecture — LLM Research Agent

```mermaid
flowchart TD
    A["🔍 Research Query"]
    B["🧠 Planner\nGPT-4o · LangChain"]
    C1["🌐 Web Search\nLive sources"]
    C2["📚 arXiv Retrieval\nPaper search API"]
    C3["📄 PDF Ingestion\npdfplumber · chunking"]
    D["🗃️ Vector Memory\nFAISS per-session store"]
    E["🔁 Reasoning Loop\nReflect · re-query if needed"]
    F["💻 Code Execution\nVerify claims · parse tables"]
    G["📝 Final Report\nSummary · citations · sources"]

    A --> B
    B --> C1
    B --> C2
    B --> C3
    C3 --> D
    C1 --> E
    C2 --> E
    D --> E
    E --> F
    F --> G
    E -->|gap detected| B
```

---

## GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=MohitKB22&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohitKB22&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="160" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=MohitKB22&theme=tokyonight&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=ff6b35&currStreakLabel=c9d1d9" />

</div>

---

## Get in touch

| | |
|---|---|
| LinkedIn | [mohit-b-9a997b301](https://www.linkedin.com/in/mohit-b-9a997b301/) |
| X | [@mohitkb22](https://x.com/mohitkb22) |
| Email | [mohitbarse2230@gmail.com](mailto:mohitbarse2230@gmail.com) |

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" />
</div>
