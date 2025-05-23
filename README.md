<!--
  Detailed GitHub Project Portfolio for Dongjae Heo
  Role: Machine Learning Engineer
-->

# Dongjae Heo
**Machine Learning Engineer**

<!-- Hero section: professional headshot + tagline -->
<!-- ![Hero Image](assets/hero.png) -->

## 👋 About Me
I’m Dongjae Heo, a Machine Learning Engineer passionate about building domain-specific AI solutions. With extensive experience fine-tuning large language models, designing RAG systems, and delivering production-ready ML pipelines, I thrive in environments where cutting-edge research meets real-world impact.

---

## 🏆 Projects

### 1. KRX Financial LLM Competition (Team Leader)
**Oct – Dec 2024** | **Role:** Team Leader

**Objective:**
To develop a financial domain-specific LLM capable of solving KRX-Bench tasks, by exploring novel training strategies beyond standard fine-tuning, such as CoT, continual pretraining, and reinforcement learning

**Overview & Innovations:**
- Explored advanced training methods beyond vanilla fine-tuning:
  - **Continual Pretraining** on proprietary finance corpora
  - **DPO** and **ORPO**
  - **CoT Prompting** and **Knowledge Distillation** to enhance reasoning
- Generated high-quality MCQA datasets with CoT rationales using Claude and GPT-4o
- Adopted domain adaptation strategies inspired by:
  - *Adapting LLMs to Domains via Reading Comprehension*
  - *Improving Domain Adaptation through Extended-Text Reading Comprehension*

**Key Contributions:**
- Architected a distributed training pipeline using FSDP for large-scale model parallelism
- Curated and synthesized specialized financial MCQA data with rationale chains
- Implemented CoT prompting templates, DPO/ORPO fine-tuning routines, and distillation workflows
- Built an internal leaderboard (PostgreSQL + Plotly-Dash) for rigorous model evaluation and comparison

![KRX Leaderboard](images/score_board.png)

**Results:**
- Achieved **+13 points** improvement in financial accounting accuracy over baseline
- Secured **2nd place (prelims)** and **12th place (nationals)** among 100+ competing teams

<!-- Leaderboard screenshot -->
<!-- ![KRX Leaderboard](assets/krx_leaderboard.png) -->

---

### 2. Information Retrieval (RAG) Chatbot (Project Lead)
**Jun – Jul 2024** | **Role:** Project Lead

**Objective:**
Design and deploy a Retrieval-Augmented Generation (RAG) pipeline that answers domain queries with high relevance by fusing vector embeddings and BM25 scores.

**Overview:**
Built a modular retrieval system combining custom-trained embeddings for internal documents and open-source BM25 indexing. Integrated the retriever with a chat interface, enabling real-time Q&A enriched by retrieved context.

**Key Contributions:**
- **Embedding Model:** Fine-tuned a bilingual sentence-transformer on proprietary knowledge graphs to yield 768‑dim vectors.  
- **Fusion Strategy:** Developed a hybrid scoring mechanism that normalizes and merges cosine similarity with BM25 ranking to select top‑k passages.  
- **System Integration:** Deployed on FastAPI with Redis caching, achieving sub‑200ms retrieval latency.  
- **UX Design:** Frontend prototype in React; incorporated an interactive UI showing source citations alongside answers.

**Results:**
- **+20%** improvement in answer relevance compared to a pure BM25 baseline.  
- Handled **5,000+** queries per day with **99.5% uptime** post‑deployment.

<!-- RAG architecture diagram -->
<!-- ![RAG Architecture](assets/rag_architecture.png) -->

---

### 3. Dialogue Summarisation Competition (AI Engineer)
**Aug – Sep 2024** | **Role:** AI Engineer

**Objective:**
Enhance Korean–English dialogue summarisation by combining advanced preprocessing, keyword extraction, and model fine-tuning to excel in a national NLP contest.

**Overview:**
Performed exhaustive data cleaning on noisy dialogue transcripts, integrated morphological analysis for keyword guidance, and fine-tuned a 10B‑parameter EEVE model with LoRA and 4‑bit quantization to maximize performance under resource constraints.

**Key Contributions:**
- **Preprocessing:** Cleaned 50k+ dialogue pairs, fixed special-token errors, and removed semantic outliers via cosine-similarity filters.  
- **Keyword Pipeline:** Extracted salient terms using Komoran/Nori analyzers; injected keywords into prompts to steer summarisation.  
- **Name Standardisation:** Applied NER + Korean phoneme heuristics to align entity mentions across languages.  
- **Model Optimization:** Leveraged LoRA adapters and 4‑bit nf4 quantization to enable efficient fine‑tuning on a single 24 GB GPU.

**Results:**
- Ranked **Top 3** with a **ROUGE‑L score of 44.16**.  
- Demonstrated that extensive preprocessing + lightweight fine-tuning outperforms naive full‑parameter updates.

<!-- Rouge results chart -->
<!-- ![Summarization Dashboard](assets/summarization_results.png) -->

---

### 4. Template Extension Chrome Add‑On (Developer)
**Apr 2022** | **Role:** Developer

**Objective:**
Create a cross-platform Chrome extension to streamline repetitive communication by managing text/image templates directly in the browser.

**Overview:**
Developed a user-friendly UI for template creation, preview, and insertion. Designed backend APIs for real-time template storage and updates, and ensured compatibility across Gmail, LinkedIn, and messaging apps.

**Key Contributions:**
- **Frontend:** Built with React and Tailwind CSS; implemented drag‑and‑drop template editor.  
- **Backend API:** FastAPI + MongoDB for secure template CRUD operations.  
- **Extension Logic:** Injected content scripts to detect active text fields and offer insertion shortcuts.  
- **User Feedback Loop:** Collected usage metrics and heatmaps to refine UI/UX.

**Results:**
- Published on Chrome Web Store; received positive feedback from recruiters and sales teams.  
- Increased outreach efficiency by **30%** in internal user surveys.

<!-- Extension UI screenshot -->
<!-- ![Template Extension](assets/extension_screenshot.png) -->

---

## 🎓 Education & Certifications
- **B.Eng in AI & Big Data**, Cyber University of Korea (2024–2027)  
- **Top 3**, Upstage AI Lab (2024)  
- **AWS ML Engineer – Associate** (2025)

---

## 📫 Contact
I’m always open to collaborations and new challenges!  
- 📧 [dongjaeheo14@gmail.com](mailto:dongjaeheo14@gmail.com)  
- 🌐 [LinkedIn](https://www.linkedin.com/in/dongjaeheo/)

<!-- Optional: Add QR code or vCard -->
<!-- ![vCard](assets/vcard_qr.png) -->

