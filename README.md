<!--
  GitHub Profile README. Daniel Vazquez Sanchez.
  Repo must be named "danvazsan2" to render as the profile README.
-->

<img src="banner.svg" alt="Daniel Vazquez Sanchez - Mathematician and Machine Learning Engineer" width="100%" />

---

## About

Mathematics taught me to **trust what I can measure**, and that is how I approach every AI system I build: not as a black box, but as distributions and trade-offs I can reason about.

During my **Double Degree in Mathematics and Computer Engineering** at the University of Seville, I found that the part of engineering I love most is building systems with **verifiable outcomes**, where success is something you can rigorously test and confirm.

I am based in **southern Spain** 🇪🇸 and always open to connecting with teams who treat AI development as a rigorous discipline, especially in **retrieval, inference, and applied LLM systems** where correctness and performance are non-negotiable.

---

## Featured Work

### Local RAG Framework (Bachelor's Thesis)
A **fully local** retrieval-augmented generation framework over private documents **and** SQL databases, with no external APIs. It combines **hybrid search with cross-encoder reranking**, a **natural-language-to-SQL agent**, and a **cascaded query router**, behind a strict multi-layer security policy for safe interaction with relational enterprise data. Every number below is backed by a **reproducible offline evaluation suite**, and the system **abstains** when it lacks solid evidence.

![Retrieval](https://img.shields.io/badge/NDCG%4010-0.952-2ea44f?style=for-the-badge)
![Ranking](https://img.shields.io/badge/MRR%4010%20%2F%20HR%401-0.967-2ea44f?style=for-the-badge)
![Adversarial](https://img.shields.io/badge/Adversarial%20retrieval-%2B88%25-1f6feb?style=for-the-badge)
![NL2SQL](https://img.shields.io/badge/NL2SQL%20accuracy-93.75%25-1f6feb?style=for-the-badge)
![Abstention](https://img.shields.io/badge/Correct%20abstention-84.6%25-8957e5?style=for-the-badge)

### SpecuLLM.cpp (Custom Inference Engine, work in progress)
A from-scratch **C++ and CUDA** inference engine that accelerates local LLM decoding on **consumer hardware**. To break the memory-bandwidth bottleneck it uses **speculative sampling**, coordinating a small draft model and a large target model to multiply generation speed. A custom **rejection sampler** guarantees output that is statistically identical to the target model alone, a **zero-degradation** claim I verify through **mathematical hypothesis testing**. Built by hand: the transformer forward pass, a dual KV-cache with synchronized rollback, and the orchestrator.

![Speculative Sampling](https://img.shields.io/badge/Speculative%20Sampling-draft%20%2B%20target-1f6feb?style=for-the-badge)
![Fidelity](https://img.shields.io/badge/Output%20fidelity-zero%20degradation-2ea44f?style=for-the-badge)
![Verification](https://img.shields.io/badge/Verified%20by-hypothesis%20testing-8957e5?style=for-the-badge)

---

## Technical Toolkit

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML / AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

**Retrieval & Serving**

![RAG](https://img.shields.io/badge/RAG-1C3C3C?style=flat-square&logo=chainlink&logoColor=white)
![NL2SQL](https://img.shields.io/badge/NL2SQL-336791?style=flat-square&logo=databricks&logoColor=white)
![FAISS](https://img.shields.io/badge/Vector%20DBs-009688?style=flat-square&logo=meta&logoColor=white)
![LLM Serving](https://img.shields.io/badge/LLM%20Serving-412991?style=flat-square&logo=openai&logoColor=white)

**Tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

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
