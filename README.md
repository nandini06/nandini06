# Nandini Agrawal

Software engineer focused on backend systems, AI infrastructure, and applied machine learning.

I am currently pursuing an MS in Computer Science at the University of Florida. Before graduate school, I worked at Goldman Sachs on payment and risk systems and interned at Amazon, where I built backend automation for an internal database workflow.

I enjoy working on systems where reliability, clear interfaces, and measurable behavior matter. My recent work explores reliable LLM serving, explainable financial risk analysis, and conversational scam detection.

[LinkedIn](https://www.linkedin.com/in/nandini-agrawal-06) · [Email](mailto:agrawalnandini15@gmail.com)

## Selected work

### [LLM Gateway and Semantic Caching Proxy](https://github.com/nandini06/llm_gateway_with_semantic_and_prompt_caching)

An asynchronous FastAPI gateway that reduces duplicate upstream requests through Redis vector caching and distributed single-flight coordination. Gemini is the primary provider, with OpenAI as a fallback for retryable failures. The service also separates gateway cache behavior from provider prompt-cache metadata and exposes structured logs and Prometheus metrics.

### [FinRisk Investigator](https://github.com/nandini06/FinRisk)

An explainable financial-risk investigation backend that combines deterministic anomaly scoring with structured transaction data and retrieved policy evidence. PostgreSQL stores transactions and reports, ChromaDB supports evidence retrieval, and a verifier can trigger one bounded retrieval and report-regeneration pass.

### [Conversational Scam Detection](https://github.com/nandini06/scam_detection)

A conversational scam-detection pipeline built around speaker-aware reconstruction, held-out conversation splits, Sentence Transformer embeddings, FAISS retrieval, and multi-model evaluation. The evaluation reports risky-class recall, false-positive rate, abstention rate, and latency instead of relying on a single aggregate score.

## Experience

- At Goldman Sachs, I worked on backend systems for payment migration, risk evaluation, and service performance testing. The work included migrating more than 60,000 payment instructions, implementing over 70 risk rules, and building replay tooling for workloads up to 20 times the existing request volume.
- At Amazon, I automated a backend database-update workflow that reduced a day-long manual process to a single operation.

## Technologies

Java, Spring Boot, Python, FastAPI, PostgreSQL, Redis, Docker, JavaScript, React, Node.js, ChromaDB, FAISS, Sentence Transformers, Gemini, and OpenAI.
