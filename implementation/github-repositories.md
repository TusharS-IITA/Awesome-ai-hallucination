# GitHub Implementations for Uncertainty and Hallucination Detection

- **Semantic Uncertainty (semantic_uncertainty)**
  **What it implements:** The official code for the foundational paper "Semantic Uncertainty: Linguistic Invariances for Uncertainty Estimation in Natural Language Generation" (Kuhn et al., 2023). It calculates semantic entropy by generating multiple outputs and clustering them by meaning.
  **Why it is relevant:** It provides the exact Python implementation for translating raw token-level uncertainty into a reliable predictor of factual hallucinations.
  [Repository Link](https://github.com/lorenzkuhn/semantic_uncertainty)

- **LM-Polygraph**
  **What it implements:** A comprehensive suite of state-of-the-art uncertainty estimation methods for LLMs, including maximum token probability, predictive entropy, and semantic-level variance.
  **Why it is relevant:** It serves as an all-in-one testing ground for researchers to compare how different uncertainty metrics correlate with hallucinations across various models.
  [Repository Link](https://github.com/IINemo/lm-polygraph)

- **llama.cpp**
  **What it implements:** A bare-metal inference engine written entirely in C++ that executes large language models locally with minimal dependencies.
  **Why it is relevant:** For low-level system design and performance optimization on Linux architectures, this implementation exposes raw token-level logits and generation probabilities directly via C++ data structures, bypassing heavy Python wrappers to build custom uncertainty estimation algorithms.
  [Repository Link](https://github.com/ggerganov/llama.cpp)

- **FActScore (Factual Precision in Long-Form Text Generation)**
  **What it implements:** The official code for breaking down generated text into atomic facts and verifying them against a knowledge source using a retrieval-augmented pipeline.
  **Why it is relevant:** While token-level uncertainty captures statistical doubt, this implementation provides the necessary semantic fact-checking layer to confirm if a low-confidence token actually resulted in a hallucination.
  [Repository Link](https://github.com/shmsw25/FActScore)

- **Chain-of-Verification (CoVe)**
  **What it implements:** Code structures for prompt-based hallucination mitigation where the LLM is forced to draft a response, plan verification questions, answer them independently, and output a revised response.
  **Why it is relevant:** It demonstrates how to handle model uncertainty programmatically without altering model weights, reducing hallucinations strictly through in-context logic sequences.
  [Repository Link](https://github.com/composable-models/chain-of-verification)
