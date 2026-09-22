<h1 align="center">Musaab Javed</h1>

<p align="center">
  <b>AI Engineer</b> — LLM applications, RAG systems and agentic automation<br>
  <i>Production over notebooks.</i>
</p>

<p align="center">
  <a href="https://musaab-javed.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://linkedin.com/in/musabjaved"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:musabjaved47@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Lahore,%20PK-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to%20work-2EA043?style=for-the-badge" alt="Open to work">
</p>

---

I build AI systems that run in production, not in notebooks. Currently working independently with EU and US clients on retrieval pipelines, multi-agent automation and the FastAPI services that hold them together. Previously led a small AI team at Tkrupt.

---

## 🚀 Featured Work

### [arabic-ocr-post-correction](https://github.com/Crypto47/arabic-ocr-post-correction)

A 0.5B language model that repairs Arabic OCR output — the step between *"we scanned the archive"* and *"the archive is searchable."*

No paired Arabic OCR corpus exists, so the supervision is generated: a script-aware confusion model that breaks clean text the way a scanner actually breaks it — dot and skeleton confusion, word splits and merges — weighted by real failure modes. A production guardrail rejects rewrites rather than repairs.

| | CER | WER |
|---|---|---|
| Raw OCR (do nothing) | 0.0808 | 0.4112 |
| Untuned Qwen2.5-0.5B | 1.8123 | 2.2680 |
| **Fine-tuned + guardrail** | **0.0671** | **0.2042** |

**Word error 41.1% → 20.4%** — a 50.3% reduction. Trained in 80 minutes on a single laptop GPU. Runs on CPU, on-premise.

`LoRA` `PEFT` `Qwen` `Arabic NLP` `Small Language Models`

### [PineCone-RAG-Assistant](https://github.com/Crypto47/PineCone-RAG-Assistant)

Retrieval-augmented assistant over Pinecone — document ingestion, embedding and semantic search with an LLM answer layer.

`RAG` `Pinecone` `Vector Search` `Embeddings`

---

## 📊 Impact

| | |
|---|---|
| 🔻 **10–20x** | cost-per-output reduction on a live LLM pipeline (~$1K/mo → $50–100/mo) |
| 📚 **5,000+** | document corpora in production RAG pipelines — analyst review cycles cut 50% |
| ⚡ **Sub-5s** | responses at 50+ concurrent users, serving 1,000+ users |
| 🔌 **40%** | reduction in new-integration time via a modular MCP-style tool layer |
| 🛡️ **60%** | reduction in production pipeline failure rates |
| 👥 **3** | engineers led at Tkrupt |

---

## 🎯 Areas of Expertise

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Generative AI & LLMs

- RAG systems architecture & retrieval evaluation
- Model fine-tuning (LoRA / QLoRA / PEFT)
- Prompt engineering & token optimisation
- NLP, embeddings & semantic search
- Model routing, serving & cost optimisation

</td>
<td width="50%" valign="top">

### ⚡ Agents & Automation

- Multi-agent systems & orchestration
- Tool / function calling, MCP-style layers
- LangChain & LangGraph pipelines
- n8n advanced workflows
- API integration & data pipeline engineering

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🔧 Backend & Infrastructure

- FastAPI & REST API design
- Docker & cloud deployment (AWS / GCP)
- Vector databases & schema design
- Evaluation, observability & monitoring
- CI/CD and production reliability

</td>
<td width="50%" valign="top">

### 🔐 Security & Applied ML

- ISC2 Certified in Cybersecurity (CC)
- Secure system & API design
- Deep learning (GANs, CNNs)
- Steganography & digital watermarking
- Threat analysis fundamentals

</td>
</tr>
</table>

---

## 🛠️ Technical Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-8A2BE2?style=for-the-badge&logo=meta&logoColor=white)
![Unsloth](https://img.shields.io/badge/Unsloth-00C853?style=for-the-badge&logo=nvidia&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FF6F00?style=for-the-badge&logo=lightning&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)

**LLM Providers**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Llama](https://img.shields.io/badge/Llama-0866FF?style=for-the-badge&logo=meta&logoColor=white)

**Backend & Data**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)

**Vector Stores**

![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6B6B?style=for-the-badge&logo=databricks&logoColor=white)

**Infrastructure & Automation**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

---

## 💼 Experience

| Role | Where | When |
|---|---|---|
| **Independent AI Consultant** | Remote — EU & US clients | Aug 2026 – present |
| **AI Integrations Engineer** | Tkrupt, Lahore | Apr 2025 – Aug 2026 |
| **AI Engineer** | Zaltech AI, Lahore | Jul 2024 – Mar 2025 |
| **Freelance Full-Stack Developer** | Fiverr | Feb 2022 – Aug 2024 |

---

## 🏆 Whisper Frames

Co-founder. Deep-learning image steganography for digital rights protection and content-ownership verification.

🌍 Exhibited at **GISEC Global 2025**, Dubai World Trade Centre
🥈 Runner-up, **Zindigi Prize 2024** Islamabad Regionals — against 85+ startups
🚀 Selected for **National Incubation Center Lahore**, Cohort 3

---

## 🌱 Currently Exploring

```js
const exploring = {
  protocols:  ["MCP server design", "agent interoperability"],
  evaluation: ["LLM-as-judge harnesses", "retrieval eval at scale"],
  serving:    ["quantisation & model compression", "on-prem CPU inference"],
  research:   ["Arabic NLP", "synthetic supervision for low-resource tasks"],
};
```

---

## 🎓 Education

**BS Computer Science** — Pakistan Institute of Engineering & Applied Sciences (PIEAS), 2020–2024
**ISC2 Certified in Cybersecurity (CC)** · **LangChain for LLM Application Development** (DeepLearning.AI)

---

<p align="center">
  <i>Open to AI engineering roles — remote, Lahore or GCC.</i><br>
  <a href="mailto:musabjaved47@gmail.com">musabjaved47@gmail.com</a>
</p>
