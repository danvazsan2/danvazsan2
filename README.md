<!--
  GitHub Profile README. Daniel Vazquez Sanchez.
  Repo must be named "danvazsan2" to render as the profile README.
-->

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg" />
  <img src="banner-light.svg" alt="Daniel Vazquez Sanchez - Mathematician and Machine Learning Engineer" width="100%" />
</picture>
</div>

---

## About

I build LLM systems and I use mathematics to prove they work.

I'm a Machine Learning Engineer with a **Double Degree in Mathematics & Computer Science**. Over the last year I designed and built production-grade LLM systems, working end-to-end from architecture to evaluation.

My Mathematics background taught me to trust only what I can measure, knowing that a result without proof is just a guess. That means I build LLM systems with evaluation as part of the design: reliable outputs, measurable quality and fewer surprises in production.

I am based in southern Spain 🇪🇸 and open to working with teams who treat AI development as a rigorous discipline, especially the mathematical side of LLMOps: retrieval, evaluation, and inference, where correctness and performance are non-negotiable.

---

## Featured Work

### Local RAG Framework (Bachelor's Thesis)

A **fully local** retrieval-augmented generation framework over private documents **and** SQL databases, with no external APIs. It combines **hybrid search with cross-encoder reranking**, a **natural-language-to-SQL agent**, and a **cascaded query router**, behind a strict multi-layer security policy for safe interaction with relational enterprise data. Every number below is backed by a **reproducible offline evaluation suite**, and the system **abstains** when it lacks solid evidence.

![Retrieval](https://img.shields.io/badge/NDCG%4010-0.952-2ea44f?style=for-the-badge)
![Ranking](https://img.shields.io/badge/MRR%4010%20%2F%20HR%401-0.967-2ea44f?style=for-the-badge)
![Adversarial](https://img.shields.io/badge/Adversarial%20retrieval-%2B88%25-1f6feb?style=for-the-badge)
![NL2SQL](https://img.shields.io/badge/NL2SQL%20accuracy-93.75%25-1f6feb?style=for-the-badge)
![Abstention](https://img.shields.io/badge/Correct%20abstention-84.6%25-8957e5?style=for-the-badge)

### JudgeCal

An **open-source framework** that treats an LLM judge as a noisy measuring instrument instead of ground truth. It applies **Rogan-Gladen bias correction** and **clustered-bootstrap confidence intervals**, then verifies both against human gold labels rather than asking you to trust them. On a frozen 14B-judge run over 17,790 responses it cut mean judge error from **14.4 to 2.1 points** and showed that **11 of 13 "significant wins"** on a leaderboard were statistical illusions. Every headline number regenerates from **one deterministic command** with no GPU, and CI fails the build if any of them drifts.

![Bias](https://img.shields.io/badge/Judge%20bias-14.4%20%E2%86%92%202.1%20pts-2ea44f?style=for-the-badge)
![Coverage](https://img.shields.io/badge/CI%20coverage%20of%20gold-100%25-2ea44f?style=for-the-badge)
![Wins](https://img.shields.io/badge/Significant%20wins-13%20%E2%86%92%202%20real-1f6feb?style=for-the-badge)
![Reproducible](https://img.shields.io/badge/Reproduce-1%20command%2C%20no%20GPU-8957e5?style=for-the-badge)

---

## Technical Toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-7C3AED?style=for-the-badge)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![sentence-transformers](https://img.shields.io/badge/sentence--transformers-0A9EDC?style=for-the-badge)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

**Retrieval & Serving**

![LanceDB](https://img.shields.io/badge/LanceDB-00897B?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![Chroma](https://img.shields.io/badge/Chroma-FF6F61?style=for-the-badge)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![FlagEmbedding](https://img.shields.io/badge/BGE%20%2F%20FlagEmbedding-5A2D82?style=for-the-badge)
![Docling](https://img.shields.io/badge/Docling-1A1A2E?style=for-the-badge)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![conda](https://img.shields.io/badge/conda-44A833?style=for-the-badge&logo=anaconda&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

---

## Outside the Code

When I step away from distributions and trade-offs, you will usually find me at the **gym**, deep into a **film or an anime**, or lost in a good **video game**. I am a firm believer that a balanced mind is what actually fuels the creativity hard engineering problems demand.

---

## Connect

If you are tackling hard problems in retrieval, inference, or applied LLM systems where correctness and performance are non-negotiable, I would enjoy hearing about what you are building.

<div align="center">
<a href="https://www.linkedin.com/in/daniel-v%C3%A1zquez-s%C3%A1nchez-352969239/">
  <img src="https://img.shields.io/badge/LinkedIn-Daniel%20V%C3%A1zquez%20S%C3%A1nchez-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="mailto:danielvazquezsanchez13@gmail.com">
  <img src="https://img.shields.io/badge/Email-danielvazquezsanchez13%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
</div>
