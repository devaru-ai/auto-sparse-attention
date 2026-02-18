# Self-Tuning Sparse Attention: Multi-Fidelity Hyperparameter Optimization for Transformer Acceleration

![Paper](https://img.shields.io/badge/Paper-Accepted_@_MiTA-blue)
![Optimization](https://img.shields.io/badge/Optimization-Bayesian-green)
![Task](https://img.shields.io/badge/Task-LLM_Acceleration-blue)

Official implementation of the paper **"Self-Tuning Sparse Attention: Multi-Fidelity Hyperparameter Optimization for Transformer Acceleration"** (MiTA 2026 Oral Presentation).


# 📢 TL;DR 
Current sparse attention mechanisms require exhaustive, manual grid search to find the optimal sparsity parameters for every single layer. We automated this process.
* **3.4x Faster Tuning:** Eliminates exhaustive grid search by automating hyperparameter discovery.
* **State-of-the-Art Quality:** Achieves 7.45 Perplexity on Llama-2-7B (at 70.7% sparsity), matching the theoretical Top-K Oracle.
* **100% Long-Context Recall:** Successfully passes the "Needle-in-a-Haystack" passkey retrieval test at 10K+ tokens.
* **Sub-linear Memory Scaling:** Theoretically reduces KV-Cache memory footprint by over 70%, allowing 32K+ context processing on consumer hardware.

