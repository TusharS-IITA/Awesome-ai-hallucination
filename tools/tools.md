# Tools and Libraries for Uncertainty and Factuality

- **Hugging Face Transformers**
  **Purpose:** The foundational Python library for downloading and running open-source LLMs. It provides direct API access to the raw output logits, token probabilities, and hidden states required to calculate token-level uncertainty and entropy.
  [Official Repository](https://github.com/huggingface/transformers)

- **llama.cpp**
  **Purpose:** A highly optimized C++ inference engine for LLMs that runs efficiently on local Ubuntu environments. It allows for bare-metal access to token sampling parameters and logit outputs necessary for building custom low-level uncertainty estimation scripts without heavy Python overhead.
  [Official Repository](https://github.com/ggerganov/llama.cpp)

- **Language Model Evaluation Harness (lm-eval)**
  **Purpose:** A unified framework by EleutherAI for testing generative language models on a wide array of factuality and knowledge benchmarks, ensuring standardized measurement of model hallucinations.
  [Official Repository](https://github.com/EleutherAI/lm-evaluation-harness)

- **SelfCheckGPT**
  **Purpose:** A specialized library implementing zero-resource black-box hallucination detection. It automates the process of sampling multiple responses from an LLM and calculating semantic uncertainty and contradiction scores.
  [Official Repository](https://github.com/potsawee/selfcheckgpt)

- **TruLens**
  **Purpose:** A software tool for evaluating and tracking LLM applications, featuring built-in feedback functions to measure factual groundedness and detect hallucinations in Retrieval-Augmented Generation (RAG) setups.
  [Official Repository](https://github.com/truera/trulens)
