# Hi, I'm Misun 👋

**NLP / ML Engineer** focused on multilingual LLM evaluation, alignment, and applied AI systems.

🎓 MSc Speech and Natural Language Processing @ University of Sheffield (2025–2026)

---

## 🔍 About Me

I build and evaluate NLP and machine learning systems, with particular depth in multilingual LLM evaluation and alignment.

My MSc research at the University of Sheffield investigates how alignment interventions and model behaviours transfer across languages, combining activation steering with behavioural, representational, and statistical evaluation.

Alongside research, I build applied AI systems spanning information retrieval, evidence-grounded LLM verification, evaluation pipelines, APIs, and reproducible ML infrastructure.

---

## 📊 Current Research

### Cross-Lingual LLM Alignment & Behaviour Evaluation

MSc research investigating whether alignment interventions derived in one language transfer reliably across languages, and how representational similarity relates to downstream behavioural effects.

- **Method:** Contrastive Activation Addition (CAA)
- **Models:** Three open-source LLM families
- **Languages:** English · Italian · Chinese · Korean · Kazakh
- **Evaluation:** Sycophancy · Cross-task transfer · Representation geometry
- **Analysis:** Layer-wise steering sweeps · PCA · Cosine similarity · Bootstrap confidence intervals · Random/permutation controls
- **Finding:** High cross-lingual representational similarity did not consistently translate into uniform behavioural transfer, revealing a representation–behaviour gap
- **Infrastructure:** Python · PyTorch · Hugging Face Transformers · SLURM · Linux HPC
- **Status:** Ongoing follow-up work toward publication
- **Repository:** [`cross-lingual-caa`](https://github.com/Ayana32/cross-lingual-caa)

---

## 🎯 Research Interests

- Multilingual NLP and cross-lingual transfer
- LLM alignment and model behaviour
- Representation learning and steering
- Multilingual model evaluation and reliability

---

## 🛠️ Technical Skills

**Machine Learning & NLP:** Python · PyTorch · Hugging Face Transformers · scikit-learn

**LLM Evaluation & Research:** Multilingual evaluation · Representation steering · Activation analysis · Behavioural evaluation · Statistical evaluation

**Retrieval & Applied AI:** BM25 · Dense Retrieval · Reciprocal Rank Fusion · Cross-Encoder Reranking · ChromaDB · Evidence-Grounded LLM Verification

**Engineering & Infrastructure:** FastAPI · Pydantic · Docker · pytest · Git · GitHub Actions CI · SLURM · Linux · Cloud GPU Execution · Weights & Biases

**Data & Applications:** SQL · Streamlit · Jupyter

**Languages:** Korean · English · Spanish · Kazakh

---

## 📂 Featured Projects

### 📑 ESG Compliance Checker — Applied RAG System

Evidence-grounded applied NLP system for evaluating corporate sustainability reports against GRI 305 disclosure requirements.

- **Retrieval:** Hybrid BM25 + dense retrieval with Reciprocal Rank Fusion and multilingual cross-encoder reranking over 7,703 indexed report chunks
- **Evaluation:** 0.963 Hit@5 and 0.798 MRR on 27 manually reviewed retrieval queries; 84.6% accuracy on a separate 39-case fixed-evidence verifier benchmark
- **Engineering:** Typed FastAPI/Pydantic backend · Streamlit frontend · Docker · 22 automated API/service/regression tests
- **Design:** Retrieval and verifier evaluation separated to isolate system failure modes

`RAG` · `Information Retrieval` · `Cross-Encoder Reranking` · `LLM Evaluation` · `FastAPI` · `Docker` · `pytest`

[View repository →](https://github.com/Ayana32/esg-report-compliance-checker)

---

### 🧪 Multilingual LLM Safety Evaluation

Reusable evaluation framework for comparing multilingual LLM safety behaviour across post-training stages.

- **Pipeline:** Configuration-driven Python evaluation with modular model, dataset, and scoring components
- **Evaluation:** Parallel English–Korean testing across SFT, DPO, and RLVR checkpoints
- **Engineering:** Typed schemas · Deterministic validation · GitHub Actions CI · Cloud GPU execution
- **Pilot finding:** Harmful-request refusal was approximately 2.5–2.9× lower in Korean than English across all three evaluated post-training stages

`LLM Evaluation` · `Python` · `PyTorch` · `Software Development` · `GitHub Actions` · `Cloud GPU`

[View repository →](https://github.com/Ayana32/multilingual-posttraining-eval)

---

### 🌐 Cross-Lingual LLM Alignment & Behaviour Evaluation

Research on cross-lingual transfer of activation-steering interventions across three open-source LLM families and five languages.

- **Method:** Contrastive Activation Addition (CAA)
- **Evaluation:** Behavioural effects · Representation geometry · Bootstrap confidence intervals · Controlled baselines
- **Finding:** High cross-lingual representational similarity did not consistently predict equivalent behavioural transfer
- **Infrastructure:** PyTorch · Hugging Face Transformers · SLURM · Linux HPC · W&B

`PyTorch` · `Hugging Face` · `CAA` · `Multilingual NLP` · `Model Evaluation` · `HPC`

[View repository →](https://github.com/Ayana32/cross-lingual-caa)

---

### 📈 Container Volume Prediction — First-Author Research

First-author LSTM forecasting study using correlation-based feature selection on container-volume data, reducing test RMSE by approximately 71% compared with the broader-input baseline.

`LSTM` · `Time Series` · `Machine Learning` · `Python`

[View repository →](https://github.com/Ayana32/Freight_Volume_Prediction)

---

## 📄 Publication

**Kim, M. et al. (2023).** *Implementation of Container Volume Prediction Technology using Deep Learning.* ACK 2023. — **First Author**

---

## 📬 Contact

- **LinkedIn:** [Misun Kim](https://www.linkedin.com/in/misun-kim-nlp)
- **Email:** [misunkim2732@gmail.com](mailto:misunkim2732@gmail.com)

<!--
**Ayana32/Ayana32** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
