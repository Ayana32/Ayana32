# Hi, I'm Misun 👋

**Multilingual LLM Alignment & Evaluation | NLP Research | Applied AI**

🎓 MSc Speech and Natural Language Processing · University of Sheffield (2025–2026; final award pending, predicted Distinction)

I investigate **when we can trust LLM behaviour across languages and tasks**—from the transfer of representation-level interventions to the reliability of multilingual safety evaluation. I also build reproducible NLP evaluation pipelines and evidence-grounded applied AI systems.

🌐 [Research homepage](https://ayana32.github.io/) · [CV](https://ayana32.github.io/cv.html) · [LinkedIn](https://www.linkedin.com/in/misun-kim-nlp/) · [Email](mailto:misunkim2732@gmail.com)

---

## 🔍 Research Focus

### Cross-Lingual Activation Steering

**Why:** English-derived steering interventions may not have comparable behavioural effects in other languages, even when representations appear similar.

- **MSc dissertation:** Evaluated Contrastive Activation Addition (CAA) across three open-weight LLM families and five languages (English, Italian, Chinese, Korean and Kazakh), studying sycophancy, truthfulness and representation–behaviour transfer.
- **Finding:** High cross-lingual representational similarity did not reliably predict equivalent behavioural effects. A descriptive cross-task comparison showed differing patterns across Qwen and OLMo.
- **How:** Layer-wise evaluations, held-out sets, bootstrap confidence intervals, and Gaussian and permutation random-vector baselines on HPC.
- **Follow-up:** Built a full **5×5 source–target transfer matrix** with **norm-matched controls** to distinguish source-vector effects from target-language responses. Joint manuscript in preparation (2027).

[Research repository →](https://github.com/Ayana32/cross-lingual-caa)

### Multilingual Post-Training Safety Evaluation

**Why:** Improvements in safety behaviour measured in English may not transfer to Korean, and automated safety judges may not be equally reliable across languages.

- **Evaluation:** 200 matched English/Korean prompts per language across OLMo 3 post-training checkpoints (SFT, DPO and RLVR).
- **Finding:** Scorer-measured harmful-request refusal rates were approximately **80% in English versus 10% in Korean**, with a substantial gap persisting under human validation.
- **Validation:** Stratified human review of **70 responses**, bootstrap and Bayesian uncertainty analysis; identified opposing patterns of safety-judge errors across languages.
- **Engineering:** Reproducible, configuration-driven evaluation components, typed schemas, deterministic validation and GitHub Actions CI.

[Safety evaluation repository →](https://github.com/Ayana32/multilingual-posttraining-eval)

---

## 🎯 Research Interests

- Multilingual LLM safety, evaluation and cross-lingual transfer
- Activation steering and representation engineering
- Generalisation of alignment interventions across languages and tasks
- Reliability of behavioural evaluation and LLM-as-judge systems

## 🛠️ Technical Skills

**Programming:** Python · SQL

**ML & NLP:** PyTorch · Hugging Face Transformers · scikit-learn

**LLM Alignment & Evaluation:** CAA · Representation analysis · Cross-lingual and cross-task evaluation · Post-training safety evaluation · LLM-as-judge validation · Human annotation and error analysis

**Experimental Methods:** Controlled experiments · Bootstrap confidence intervals · Bayesian uncertainty analysis · Random-vector baselines

**Retrieval & Applied AI:** BM25 · Dense retrieval · Reciprocal Rank Fusion · Cross-encoder reranking · ChromaDB · Evidence-grounded LLM verification

**Engineering & Research Infrastructure:** HPC/SLURM · Linux · Weights & Biases · Git · GitHub Actions CI · Docker · FastAPI · Flask · Pydantic · pytest · Streamlit

---

## 📂 Selected Projects

### 🧪 [Multilingual LLM Safety Evaluation](https://github.com/Ayana32/multilingual-posttraining-eval)
A reproducible research framework for comparing refusal behaviour across English and Korean after SFT, DPO and RLVR. Combines matched-prompt evaluation with human validation to examine both **model behaviour** and **safety-judge reliability**.

`LLM Evaluation` · `Multilingual Safety` · `Human Validation` · `PyTorch` · `GitHub Actions`

### 🌐 [Cross-Lingual CAA Research](https://github.com/Ayana32/cross-lingual-caa)
MSc dissertation and follow-up evaluation of activation-steering generalisation across three model families and five languages. Investigates the distinction between representation similarity and reliable behavioural transfer.

`Activation Steering` · `Representation Analysis` · `HPC/SLURM` · `Statistical Evaluation`

### 📑 [ESG Compliance Checker](https://github.com/Ayana32/esg-report-compliance-checker)
Evidence-grounded verification of corporate sustainability reports, mapping requirements to retrieved passages and traceable judgements over 11 reports. In the evaluation reported in my current CV, hybrid retrieval with reranking improved **Hit@5 from 83.3% to 100%** and **MRR from 0.628 to 0.819** compared with BM25-only retrieval.

Built with hybrid retrieval, reranking, a manually annotated gold set, FastAPI, Streamlit, Docker and automated tests. Retrieval and verifier errors were analysed separately.

`RAG` · `Information Retrieval` · `LLM Verification` · `FastAPI` · `Docker`

### 📈 [Container Volume Prediction](https://github.com/Ayana32/Freight_Volume_Prediction)
First-author LSTM forecasting research that reduced RMSE by approximately **71% relative to the baseline**. Published at ACK 2023.

`Time Series` · `LSTM` · `Python`

---

## 📄 Publications & Manuscripts

- **Kim, M.**, Kim, Y., Kim, E., Lee, B., Han, Y., & Lee, G. (2023). *Implementation of Container Volume Prediction Technology using Deep Learning.* ACK Conference Proceedings, 30(2). **First author.**
- *Cross-lingual and cross-task generalisation of representation-level interventions in multilingual LLMs.* **Manuscript in preparation (2027).**

## 🌍 Languages

Korean (Native) · English (Fluent) · Spanish (Intermediate) · Kazakh (Intermediate)
