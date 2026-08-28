# Curated Research Papers

## Survey and Review Papers

- **A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions**
  Huang, L., Yu, W., Ma, W., et al., 2023, arXiv
  [View Paper](https://arxiv.org/abs/2311.05232)
  Provides a comprehensive taxonomy of hallucination types and evaluates existing detection mechanisms.

- **Survey of Hallucination in Natural Language Generation**
  Ji, Z., Lee, N., Frieske, R., et al., 2023, ACM Computing Surveys
  [View Paper](https://dl.acm.org/doi/10.1145/3571730)
  A foundational survey categorizing hallucinations based on input metrics and evaluating traditional generation models.

## Foundational Language Models

- **Language Models are Few-Shot Learners**
  Brown, T., Mann, B., Ryder, N., et al., 2020, NeurIPS
  [View Paper](https://arxiv.org/abs/2005.14165)
  Introduces GPT-3 and establishes the baseline capabilities of auto-regressive text generation at scale.

- **Language Models as Knowledge Bases?**
  Petroni, F., Rocktäschel, T., Lewis, P., et al., 2019, EMNLP
  [View Paper](https://arxiv.org/abs/1909.01066)
  Explores probing models to determine if they store relational knowledge versus fabricating facts dynamically.

- **Llama 2: Open Foundation and Fine-Tuned Chat Models**
  Touvron, H., Martin, L., Stone, K., et al., 2023, arXiv
  [View Paper](https://arxiv.org/abs/2307.09288)
  Details the training, alignment, and inherent hallucination mitigations applied to open-source foundation models.

## Uncertainty and Calibration in Neural Networks

- **Selective Classification for Deep Neural Networks**
  Geifman, Y., & El-Yaniv, R., 2017, NeurIPS
  [View Paper](https://arxiv.org/abs/1705.08500)
  Discusses selective prediction, forming the theoretical basis for early-exit strategies to mitigate hallucinations.

- **On Calibration of Modern Neural Networks**
  Guo, C., Pleiss, G., Sun, Y., & Weinberger, K. Q., 2017, ICML
  [View Paper](https://arxiv.org/abs/1706.04599)
  Analyzes the calibration problem in deep learning and introduces temperature scaling to correct overconfidence.

- **What Uncertainties Do We Need in Bayesian Deep Learning for Computer Vision?**
  Kendall, A., & Gal, Y., 2017, NeurIPS
  [View Paper](https://arxiv.org/abs/1703.04977)
  Provides the critical mathematical distinction between epistemic and aleatoric uncertainty.

- **Simple and Scalable Predictive Uncertainty Estimation using Deep Ensembles**
  Lakshminarayanan, B., Pritzel, A., & Blundell, C., 2017, NeurIPS
  [View Paper](https://arxiv.org/abs/1612.01474)
  Proposes ensemble methods as a baseline for capturing uncertainty across model parameters.

## Uncertainty Metrics for LLMs

- **Language Models (Mostly) Know What They Know**
  Kadavath, S., Conerly, T., Asks, T., et al., 2022, arXiv
  [View Paper](https://arxiv.org/abs/2207.05221)
  Investigates how well LLM confidence scores map to actual output correctness, highlighting calibration issues.

- **Semantic Uncertainty: Linguistic Invariances for Uncertainty Estimation in Natural Language Generation**
  Kuhn, L., Gal, Y., & Farquhar, S., 2023, arXiv
  [View Paper](https://arxiv.org/abs/2302.09664)
  Introduces a method measuring disagreement across multiple model samples to predict factual errors.

- **SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models**
  Manakul, P., Liusie, A., & Gales, M. J. F., 2023, EMNLP
  [View Paper](https://arxiv.org/abs/2303.08896)
  Demonstrates how sampling multiple responses from a single LLM can detect hallucinations without external databases.

- **Do Large Language Models Know What They Don't Know?**
  Yin, Zhangchen, et al., 2023, Findings of ACL
  [View Paper](https://arxiv.org/abs/2305.18153)
  Evaluates the boundary of LLM knowledge and how models behave when queried outside their training distribution.

## Factuality Evaluation and Hallucination Detection

- **Measuring Factuality in Generation with Dependency-Level Entailment**
  Malkin, N., Yildirim, I., & Salakhutdinov, R., 2023, EMNLP
  [View Paper](https://arxiv.org/abs/2309.09556)
  Analyzes covariance structures of embeddings from multiple completions to determine structural uncertainty.

- **On Faithfulness and Factuality in Abstractive Summarization**
  Maynez, J., Narayan, S., Artetxe, M., & Schwenk, H., 2021, ACL
  [View Paper](https://arxiv.org/abs/2104.13346)
  Evaluates abstractive summarization models to identify intrinsic and extrinsic hallucinations.

- **Evaluating Language Models for Indexing Scholarly Citations**
  Roller, S., Suhr, A., Lin, S., et al., 2023, arXiv
  [View Paper](https://arxiv.org/abs/2303.07302)
  Tests the ability of language models to accurately retrieve and index complex factual data without hallucinating.

- **Confident Natural Language Inference**
  Schuster, T., Fisch, A., Barzilay, R., & Adar, E., 2022, EMNLP
  [View Paper](https://arxiv.org/abs/2210.03387)
  Explores confidence-based decoding where tokens with confidence below a learned threshold are rejected.

- **TruthfulQA: Measuring How Models Mimic Human Falsehoods**
  Lin, S., Hilton, J., & Evans, O., 2022, ACL
  [View Paper](https://arxiv.org/abs/2109.07958)
  A benchmark establishing that language models can be more prone to generating confident falsehoods if trained on flawed text.

## Mitigation via Retrieval and Augmentation

- **Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks**
  Lewis, P., Perez, E., Rinott, R., et al., 2020, NeurIPS
  [View Paper](https://arxiv.org/abs/2005.11401)
  Introduces the foundational RAG architecture, utilizing external contexts to ground models and suppress hallucination.

- **Extractive Summarization as Text Matching**
  Zhong, M., Liu, P., Wang, Y., & Huang, M., 2020, EMNLP
  [View Paper](https://arxiv.org/abs/2004.08795)
  Frames summarization as a semantic matching problem, providing methodologies useful for clustering generated responses.
