<div align="center">

# Hi, I'm Huyen Trang 👋

### Data Science Student · AI/ML · Generative AI · Data Engineering

<p>
  <a href="https://github.com/YOUR_USERNAME">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="YOUR_LINKEDIN_URL">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:YOUR_EMAIL">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

</div>

---

<div align="center">

### DATA → INTELLIGENCE → SYSTEMS

</div>

I am a **Data Science student at the University of Science, Vietnam National University Ho Chi Minh City (HCMUS)**, interested in building practical systems across **Machine Learning, Deep Learning, Generative AI, and Data Engineering**.

My experience ranges from improving **semiconductor inspection and detection systems** at Intel to building **LLM-powered applications, data pipelines, and deep learning systems** through academic and personal projects.

I enjoy working across the full journey:

```text
Data
  ↓
Data Engineering
  ↓
Machine Learning / Deep Learning
  ↓
Generative AI & LLM Applications
  ↓
Reliable & Usable Systems
```

My goal is to bridge the gap between **data, intelligent models, and real-world applications**.

---

# 🔍 What I'm Interested In

<table>
<tr>
<td width="33%" valign="top">

### 🤖 AI & Machine Learning

Building and experimenting with models that solve real-world problems.

* Machine Learning
* Deep Learning
* Computer Vision
* Anomaly Detection
* Model Evaluation
* Experimentation

</td>

<td width="33%" valign="top">

### 🧠 Generative AI

Exploring how LLMs can be combined with data and software systems.

* LLM Applications
* RAG
* Multi-Agent Systems
* Prompt Engineering
* Vector Search
* AI-powered Applications

</td>

<td width="33%" valign="top">

### 🏗️ Data Engineering

Designing the data foundations that support analytics and AI systems.

* ETL / ELT
* Data Pipelines
* Big Data
* Data Modeling
* Workflow Orchestration
* Data Processing

</td>
</tr>
</table>

---

# 💼 Professional Experience

## Data Science Intern — Intel Products Vietnam

Working on **improving semiconductor inspection and detection systems** through data-driven analysis, automation, and system optimization.

My work focuses on analyzing operational and inspection data to identify system limitations, improve detection performance, reduce false alarms, and streamline diagnostic and monitoring workflows.

I also develop automated solutions that enhance the efficiency and reliability of existing inspection systems while collaborating with cross-functional engineering teams to address real-world manufacturing challenges.

**Focus:**
`System Improvement` · `Detection & Diagnostics` · `Anomaly Detection` · `False Alarm Reduction` · `Process Monitoring` · `Workflow Automation` · `Data-driven Optimization`

---

# 🚀 Featured Projects

<div align="center">

### From Data Infrastructure to Intelligent Applications

</div>

---

## 🧠 OmniLearn — Intelligent Learning Platform

An intelligent learning platform exploring the integration of **Large Language Models, Retrieval-Augmented Generation, and Multi-Agent Systems** into learning workflows.

### What I worked on

* Developed AI-powered learning workflows using LLM technologies.
* Explored **Retrieval-Augmented Generation (RAG)** for knowledge-grounded responses.
* Applied vector search for semantic retrieval.
* Experimented with **Multi-Agent Systems** for specialized learning tasks.
* Designed prompt workflows to improve response quality and grounding.
* Integrated AI capabilities into a broader learning application.

### System Direction

```text
User
  │
  ▼
Learning Application
  │
  ├───────────────┐
  │               │
  ▼               ▼
AI Chat        Learning Tasks
  │          Quiz · Flashcard
  │          Essay · Roadmap
  │
  ▼
Retrieval Layer
  │
  ▼
Vector Search
  │
  ▼
Knowledge Context
  │
  ▼
LLM / Agent Workflow
  │
  ▼
Grounded Response
```

### Tech Stack

`Python` · `LLM` · `RAG` · `Multi-Agent Systems` · `LangChain` · `FAISS` · `FastAPI` · `PostgreSQL` · `MinIO`

---

## 📊 TMDB Data Engineering & Analytics Platform

An end-to-end data engineering project focused on building a structured pipeline for **data ingestion, transformation, modeling, and downstream analytics**.

### What I worked on

* Built ETL/ELT workflows for movie-related datasets.
* Designed a **Bronze → Silver → Gold** data processing architecture.
* Used Apache Spark for large-scale data processing and transformation.
* Applied dbt for data transformation and data modeling.
* Used Dagster for workflow orchestration.
* Managed structured data with PostgreSQL.
* Used MinIO for object storage.
* Containerized the data platform using Docker.

### Data Architecture

```text
                 RAW DATA
                    │
                    ▼
            ┌───────────────┐
            │ Data Ingestion│
            └───────┬───────┘
                    │
                    ▼
            ┌───────────────┐
            │  BRONZE LAYER │
            │   Raw Data    │
            └───────┬───────┘
                    │
                    ▼
            ┌───────────────┐
            │ SILVER LAYER  │
            │ Cleaned Data  │
            └───────┬───────┘
                    │
                    ▼
            ┌───────────────┐
            │   dbt Models  │
            │ Transformation│
            └───────┬───────┘
                    │
                    ▼
            ┌───────────────┐
            │  GOLD LAYER   │
            │ Analytics Data│
            └───────┬───────┘
                    │
             ┌──────┴──────┐
             ▼             ▼
        Analytics      ML Workflows
```

### Tech Stack

`Python` · `SQL` · `Apache Spark` · `Spark MLlib` · `dbt` · `Dagster` · `PostgreSQL` · `MinIO` · `Docker`

---

## 🎨 Sketch-to-Image with Pix2Pix

A deep learning project focused on **sketch-to-image generation** using conditional Generative Adversarial Networks and the Pix2Pix framework.

The project explores image-to-image translation across multiple datasets, including **Facades, Edges2Shoes, and CUFS**.

### What I worked on

* Implemented Pix2Pix for paired image-to-image translation.
* Experimented with **U-Net-based generator architectures**.
* Explored conditional GAN training for sketch-to-image generation.
* Conducted model experiments and ablation studies.
* Evaluated generated results using quantitative image quality metrics.
* Built a Gradio demo for model inference.

### Model Direction

```text
             Input Sketch
                  │
                  ▼
        ┌──────────────────┐
        │     Generator    │
        │      U-Net       │
        └────────┬─────────┘
                 │
                 ▼
          Generated Image
                 │
                 │
        ┌────────┴─────────┐
        │                  │
        ▼                  ▼
   Real Image         Generated Image
        │                  │
        └────────┬─────────┘
                 ▼
           Discriminator
                 │
                 ▼
          Adversarial Loss
                 +
              L1 Loss
```

### Tech Stack

`Python` · `PyTorch` · `GAN` · `cGAN` · `Pix2Pix` · `U-Net` · `Computer Vision` · `Gradio`

---

# 🧩 My Technical Landscape

```text
                         AI / DATA SYSTEMS
                                │
              ┌─────────────────┼─────────────────┐
              │                 │                 │
              ▼                 ▼                 ▼
         AI / ML           GENERATIVE AI     DATA ENGINEERING
              │                 │                 │
        ┌─────┴─────┐     ┌─────┴─────┐     ┌─────┴─────┐
        │           │     │           │     │           │
     PyTorch     ML       LLM         RAG   Spark      ETL
     Scikit      Models   Agents      FAISS dbt       Dagster
     Learn                LangChain        SQL        Docker
```

---

# 🛠️ Toolbox

### Programming

`Python` · `SQL` · `R` · `C/C++`

### Machine Learning

`Pandas` · `NumPy` · `Scikit-Learn` · `XGBoost` · `LightGBM`

`Regression` · `Classification` · `Clustering` · `Decision Trees` · `Ensemble Learning`

### Deep Learning

`PyTorch` · `Neural Networks` · `CNN` · `GAN` · `cGAN` · `U-Net` · `Pix2Pix`

### Generative AI

`LLM Applications` · `RAG` · `Multi-Agent Systems` · `Prompt Engineering`

`LangChain` · `FAISS`

### Data Engineering

`Apache Spark` · `Spark MLlib` · `dbt` · `Dagster` · `ETL / ELT`

### Databases & Storage

`PostgreSQL` · `MySQL` · `MinIO`

### Development & Deployment

`FastAPI` · `Streamlit` · `Docker` · `Git` · `GitHub`

### Visualization

`Matplotlib` · `Power BI`

---

# 🏆 Achievements

| Achievement | Recognition                              |
| ----------- | ---------------------------------------- |
| 🥈          | Second Prize — SCUDEM                    |
| 🥉          | Third Prize — SCUDEM                     |
| 🏅          | Encouragement Prize — MCM/ICM            |
| 🏆          | Top 20 — MyInsight Datathon 2025         |
| 🔬          | Outstanding Research Certificates — 2025 |
| 🎓          | Vallet Scholarship                       |
| 🎓          | SCG Sharing The Dream Scholarship        |

---

# 🎓 Education

### University of Science, Vietnam National University Ho Chi Minh City

**Bachelor of Data Science**

`GPA: 8.65 / 10` · `TOEIC: 820`

### Relevant Areas

`Machine Learning` · `Deep Learning` · `Data Mining`

`Database Management` · `Data Engineering` · `Big Data`

`Statistical Data Processing` · `Python for Data Science`

---

# 📈 GitHub Activity

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" width="49%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=transparent&hide_border=true" width="49%" />

<br><br>

<img src="https://streak-stats.demolab.com?user=YOUR_USERNAME&theme=transparent&hide_border=true" width="70%" />

</div>

---

# 🌱 Currently Exploring

```text
                    DATA
                      │
                      ▼
              Data Engineering
                      │
                      ▼
                 AI / ML
                      │
                      ▼
               Generative AI
                      │
                      ▼
             LLM & Agent Systems
                      │
                      ▼
              Production Systems
```

I am continuously exploring how to move from **data and research ideas to practical intelligent systems**.

My current learning direction focuses on:

* Advanced Machine Learning & Deep Learning
* Generative AI and LLM Applications
* RAG and Agentic Systems
* Data Engineering at Scale
* Production-oriented AI Systems
* Building reliable and maintainable data-driven applications

---

# 💡 Build Philosophy

> **Good AI systems are more than models.**

> They are built from reliable data, thoughtful experimentation, useful applications, and engineering systems that make everything work together.

I believe a strong Data Scientist or AI Engineer should understand the journey from:

```text
Problem
  ↓
Data
  ↓
Analysis
  ↓
Model
  ↓
Evaluation
  ↓
Application
  ↓
Reliable System
```

I am interested in building systems that are not only **accurate**, but also **useful, reproducible, maintainable, and applicable to real-world problems**.

---

# 🤝 Let's Connect

I am always interested in connecting with people working on:

`Artificial Intelligence` · `Machine Learning` · `Data Science`

`Data Engineering` · `Generative AI` · `LLM Applications`

`Research` · `Applied AI` · `Interesting Technical Projects`

<div align="center">

### Thanks for visiting my profile! 👋

⭐ Feel free to explore my repositories and projects.

</div>
