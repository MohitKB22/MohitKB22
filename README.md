<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Mohit%20Barse&fontSize=65&fontColor=ffffff&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%7C%20RAG%20Systems%20%7C%20Multimodal%20AI%20%7C%20Data-Driven%20Applications&descAlignY=60&descSize=15" alt="header" />

<p>
  <a href="https://www.linkedin.com/in/mohit-b-9a997b301/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://x.com/mohitkb22">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" />
  </a>
  <a href="https://github.com/MohitKB22">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="mailto:mohitbarse2230@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

</div>

---

## 🧠 About Me

> *"I don't just build models — I focus on building **usable AI systems**."*

I'm an **AI/ML Engineer** passionate about turning complex research into production-ready, real-world solutions. My focus lies at the intersection of **Retrieval-Augmented Generation (RAG)**, **multimodal AI**, and **scalable backend systems**.

- 🔭 Currently building advanced **RAG pipelines** & **multimodal AI applications**
- 🌱 Deepening expertise in **MLOps**, **FastAPI** deployment workflows, and model lifecycle management
- 🎯 Goal: Become an industry-ready AI Engineer owning the full pipeline — from data ingestion to intelligent output
- ✍️ I occasionally share AI/ML insights and engineering thoughts on **[X (@mohitkb22)](https://x.com/mohitkb22)**
- ⚡ Fun fact: I enjoy turning complex problems into simple, working solutions 🚀

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Frameworks
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)

### AI / ML
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)

### Tools & Infrastructure
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## 🚀 Featured Projects

### 🤖 [LLM Research Agent](https://github.com/MohitKB22/llm-research-agent)
> An autonomous agent that searches the web, retrieves papers, and synthesizes cited research reports — end to end.

```
Query → Planner → [Web Search | arXiv Retrieval | PDF Ingestion] → Vector Memory → Reasoning Loop → Report
```

| Feature | Details |
|---|---|
| 🧠 Planner | Breaks query into sub-tasks, reflects on gaps, re-queries until confident |
| 🌐 Web Search | Retrieves live sources beyond pre-indexed docs |
| 📚 arXiv Retrieval | Searches and pulls research papers via arXiv API |
| 📄 PDF Ingestion | Chunks and embeds downloaded papers into per-session FAISS store |
| 💻 Code Execution | Runs analysis snippets to verify claims and parse tabular data |
| 🛠️ Stack | `LangChain Agents` · `FAISS` · `arXiv API` · `pdfplumber` · `GPT-4o` · `FastAPI` |

---

### 📊 [Stock Analytics Hub](https://github.com/MohitKB22/stock-analytics-hub)
> Interactive dashboard for visualizing **Nifty and stock market data** with real-time insights and analytics.

| Feature | Details |
|---|---|
| 📈 Data | Real-time stock data visualization |
| 📊 Charts | Interactive trend analysis & pattern detection |
| 🛠️ Stack | `Python` · `Dash/Streamlit` · `Pandas` · `Plotly` |

---

### 🩺 [Care AI Engine](https://github.com/MohitKB22/care-ai-engine)
> AI-powered healthcare chatbot for **symptom analysis**, medical guidance, and patient support.

| Feature | Details |
|---|---|
| 💬 Interface | Conversational AI for healthcare Q&A |
| 🔎 Analysis | Symptom understanding & intelligent routing |
| 🛠️ Stack | `JavaScript` · `NLP` · AI APIs |

---

### 🔬 [Fingerprint Blood Group Prediction](https://github.com/MohitKB22/Fingerprint-Based-BloodGroup-Prediction)
> A deep learning project predicting **blood group from fingerprint images** using CNNs.

| Feature | Details |
|---|---|
| 🧬 Research | Biometric patterns correlated with blood groups |
| 🤖 Model | End-to-end CNN from image preprocessing to classification |
| 🛠️ Stack | `Python` · `TensorFlow/Keras` · `OpenCV` |

---

## 🏗️ System Architecture (RAG Reference)

```mermaid
flowchart TD
    A["📄 PDF Input\nText · Images · Tables"]
    B["🔀 Multimodal Parser\npdfplumber · PyMuPDF"]
    C1["📝 Text Index\nFAISS + Embeddings"]
    C2["🖼️ Image Index\nGPT-4V Captions"]
    C3["📊 Table Index\nStructured Extraction"]
    D["🧭 Query Router\nSemantic Classification"]
    E["⚡ Generator\nGPT-4o · LangChain"]
    F["✅ Final Answer"]

    A --> B
    B --> C1
    B --> C2
    B --> C3
    C1 --> D
    C2 --> D
    C3 --> D
    D --> E
    E --> F
```

---

## 📈 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=MohitKB22&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&icon_color=58a6ff" height="165" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MohitKB22&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" height="165" alt="Top Languages" />

<img src="https://github-readme-streak-stats.herokuapp.com/?user=MohitKB22&theme=tokyonight&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=ff6b35&currStreakLabel=c9d1d9" alt="GitHub Streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MohitKB22&theme=tokyo-night&area=true&hide_border=true" width="100%" />

</div>

---

## 🤝 Open to Collaborate On

| Area | Details |
|---|---|
| 🤖 AI/ML Projects | Real-world impact, RAG systems, LLM applications |
| 🛠️ Full-Stack AI Apps | End-to-end development from data to interface |
| 📦 Open Source | Python, AI tooling, ML utilities |
| 💡 Hackathons | Rapid prototyping and innovation sprints |

---

## 📫 Get In Touch

<div align="center">

| Platform | Link |
|---|---|
| 💼 LinkedIn | [mohit-b-9a997b301](https://www.linkedin.com/in/mohit-b-9a997b301/) |
| 🐦 X (Twitter) | [@mohitkb22](https://x.com/mohitkb22) |
| 📧 Email | [mohitbarse2230@gmail.com](mailto:mohitbarse2230@gmail.com) |
| 🐙 GitHub | [@MohitKB22](https://github.com/MohitKB22) |

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=100&section=footer" alt="footer"/>

*"The best way to predict the future is to build it."* 🚀

</div>
