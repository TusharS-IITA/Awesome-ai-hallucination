# Awesome Token-Level Uncertainty in LLMs
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A carefully curated collection of research papers, datasets, tools, implementations, and free learning resources exploring how token-level uncertainty can predict and mitigate hallucinations in Large Language Models (LLMs).

## 📑 Contents
- [Overview](#-overview)
- [AI-Assisted Research Paper](#-ai-assisted-research-paper)
- [Citation Integrity Audit](#-citation-integrity-audit)
- [Curated Research Papers](#-curated-research-papers)
- [Datasets](#-datasets)
- [Tools and Libraries](#-tools-and-libraries)
- [GitHub Implementations](#-github-implementations)
- [Free Tutorials and Learning Resources](#-free-tutorials-and-learning-resources)

---

## 🔎 Overview
Large Language Models (LLMs) have achieved remarkable performance across diverse natural language tasks, but their tendency to generate plausible-sounding yet factually incorrect statements—known as hallucinations—remains a critical deployment hurdle. 

This repository focuses on **token-level uncertainty** as a mechanism for hallucination detection. During auto-regressive generation, an LLM produces a probability distribution over its vocabulary for every single token. Analyzing the uncertainty inherent in this distribution provides a window into the model's internal confidence. If high token-level uncertainty strongly correlates with factual errors, we can leverage these signals to flag unreliable outputs, trigger external retrieval (RAG), or instruct the model to abstain from answering. 

## 📄 AI-Assisted Research Paper
**Token-Level Uncertainty as a Predictor of Hallucination in Large Language Models**  
An AI-generated academic paper exploring the theoretical frameworks and current methodologies linking predictive uncertainty to factuality in language models.
> 🔗 [View Paper](paper/AI_Assisted_Research_Paper.pdf)

## 🔍 Citation Integrity Audit
A systematic evaluation of the AI-generated research paper's references. This audit rigorously checked 19 citations against scholarly databases, identifying genuine papers, fabricated metadata, and "Frankenstein" citations.
> 🔗 [View Audit PDF](citation-audit/Citation_Integrity_Audit.pdf) | 🔗 [View Audit Markdown](citation-audit/citation_audit.md)

## 📚 Curated Research Papers
A verified collection of 20 scholarly papers categorized by Survey Papers, Foundational Models, Calibration, Uncertainty Metrics, and Mitigation Strategies.
> 🔗 [Explore Curated Papers](references/references.md)

## 📊 Datasets
Specialized open-source benchmarks (such as TruthfulQA and HaluEval) for evaluating factual accuracy, hallucination rates, and model calibration.
> 🔗 [Explore Datasets](datasets/datasets.md)

## 🛠️ Tools and Libraries
Software frameworks and APIs for extracting token probabilities, computing semantic entropy, and evaluating generation factuality.
> 🔗 [Explore Tools](tools/tools.md)

## 💻 GitHub Implementations
High-quality, open-source repositories implementing uncertainty estimation algorithms and low-level inference engines.
> 🔗 [Explore Implementations](implementations/github-repositories.md)

## 🎓 Free Tutorials and Learning Resources
1. **[Stanford CS224N: Natural Language Processing with Deep Learning](https://web.stanford.edu/class/cs224n/)**  
   Free lecture series and materials from Stanford covering the foundational mathematics of auto-regressive generation, softmax probabilities, and model confidence.
2. **[Hugging Face NLP Course](https://huggingface.co/learn/nlp-course/chapter1/1)**  
   A completely free, comprehensive guide to manipulating open-source models, understanding tokenization, and extracting raw log probabilities.
3. **[llama.cpp Advanced C++ Inference Guide](https://github.com/ggerganov/llama.cpp/tree/master/examples)**  
   Open-source C++ examples demonstrating how to build custom low-level text generation pipelines, intercept token logits, and calculate confidence without Python overhead.
4. **[Ubuntu Machine Learning Environment Setup](https://ubuntu.com/blog/data-science-with-ubuntu)**  
   Canonical's free official guides for optimizing Ubuntu for deep learning workloads, ensuring efficient local execution of uncertainty estimation scripts.
5. **[PromptingGuide.ai: Hallucination Mitigation](https://www.promptingguide.ai/research/llm-hallucination)**  
   An open-access, regularly updated repository of techniques and research summaries on why models hallucinate and how to structure prompts to reduce uncertainty.
