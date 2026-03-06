---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
{% include base_path %}

Education
======
* **Nazarbayev University**, Astana, Kazakhstan
  * BSc in Computer Science; CGPA 3.53/4.0 — **Top 5%** — August 2022 – June 2026
  * Full government scholarship & stipend; Dean's List for Academic Excellence (Spring 2025)
  * **Selected Coursework:** Natural Language Processing, Deep Learning, Machine Learning, Image Processing, Artificial Intelligence

* **Athens NLP 2025**, Athens, Greece
  * Machine Learning Summer School — September 4–10, 2025
  * Selected as 1 of 3 undergraduate students among 90 participants for an intensive NLP program with lectures and labs led by researchers including Mohit Bansal, Preslav Nakov, and Yulan He.

Research Experience
======
* **MBZUAI NLP Collaboration (with Prof. Preslav Nakov)** — Machine Learning Researcher — Remote
  * *November 2025 – Present*
  * *Project: CHARMemes — Harmful Meme Detection*
    * Co-developed CHARMemes, a 23,025-example benchmark of harmful memes from the Runet ecosystem using LLM-assisted annotation with targeted human adjudication; achieved Fleiss' κ = 0.721
    * Benchmarked CLIP, XLM-RoBERTa, and EfficientNet for fine-grained harmful-content classification in non-English multimodal data
  * *Project: Media Profiler — Automated Fact-Checking*
    * Architected a LangGraph multi-agent system automating MBFC methodology; specialized agents independently evaluate source credibility, factual verification, and propaganda detection
    * Fine-tuned DeBERTa-v3-Large classifiers for propaganda-technique identification within the pipeline; the full system doubled generation quality and outperformed a direct LLM baseline by 7% FACTScore

* **Nazarbayev University** — Research Assistant, Water Policy Analysis Project — Astana, Kazakhstan
  * *January 2025 – Present*
  * Developed a multi-agent LLM pipeline to classify groundwater governance across 157 national laws on six regulatory dimensions, producing the first global comparative dataset of groundwater legal frameworks
  * Built a retrieval and re-ranking pipeline for comparative legal analysis using sliding-window chunking, multiple embeddings (BGE, Qwen, Jina), and a BGE Re-Ranker for accurate legal text extraction and verification
  * Second author on a manuscript in preparation targeting Nature Sustainability; co-authored 3 presentations at groundwater governance and legal-policy venues

* **Outpeer.AI** — Machine Learning Researcher — Astana, Kazakhstan
  * *January 2026 – Present*
  * Fine-tuned Vision-Language Models (PaddleOCR-VL1.5, GLM-OCR, HunyuanOCR) for structural layout extraction; designed an agreement-based ensemble routing low-confidence cases to a frontier LLM, reducing API costs by 80%

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Technical Skills
======
* **Languages & Tools:** Python, C++, C, SQL, Git, Linux, Bash, Docker, Weights & Biases (WandB)
* **ML/AI:** PyTorch, Hugging Face Transformers, LangChain, LangGraph, OpenAI API, FAISS, RAG

Honors & Competitions
======
* **Yessenov Foundation Scholarship & Advanced LLM Program** — Fellow / Grant Recipient (~5% Acceptance Rate) — Remote
  * *February 2026 – July 2026*
  * Awarded a highly competitive national grant to complete an intensive frontier LLM engineering program, gaining hands-on expertise in distributed training, alignment, inference optimization, and multimodal architectures

* **AI Safety & LLM Evaluation Program \| Monoid** — Fellow — Remote
  * *March 2026 – June 2026*
  * Designing evaluation pipelines using Inspect AI and lm-eval-harness to systematically assess LLM alignment, robustness, and factual accuracy on benchmarks including TruthfulQA and MMLU

* **SemEval 2026 – Task 13: Machine-Generated Code Detection, Subtask C** — Machine Learning Researcher — Remote
  * *November 2025 – February 2026*
  * Placed **Top-9** globally on a private benchmark for 4-way machine-generated code detection by fine-tuning ModernBERT with metric learning and focal loss
