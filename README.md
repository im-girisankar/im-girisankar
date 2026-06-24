# Hi, I'm Girisankar G 👋

**AI Engineer — LLM systems, agentic tooling, evaluation & the data infra behind them.**

M.Tech in Data Science & AI (CUSAT), B.Tech CSE AI ML (VIT). I build production LLM systems and the tooling that
keeps them honest. Thesis on **proactive hallucination
detection via internal activation probing** [Mechanistic Interpretability]. Background spans agentic apps, LLM evaluation,
MLOps, and large-scale data engineering.

- 🔭 Focus: **LLM reliability & safety · agentic systems · MLOps & data pipelines**
- 🧠 Production experience: Azure OpenAI agents, RAG over unstructured documents, ETL on AWS (Airflow/PySpark)
- 🚧 Shipping a frontier-AI series through 2026: LLM guardrails, MCP tooling, agent evaluation, GraphRAG, local RAG & LoRA fine-tuning
- 📫 [LinkedIn](https://linkedin.com/in/im-girisankar) · girisankargopakumar@gmail.com

---

## 🛠️ Featured projects

Every repo runs and is tested (heavy LLM libs optional/lazy so cores run offline). Highlights with **real, reproduced numbers**:

- 🧪 **trust-probe** — a linear probe on **Qwen2.5-7B layer-19 activations detects TruthfulQA hallucinations at AUROC 0.916** (95% CI [0.898, 0.931]), peaking in the mid-late layers — reproducing my thesis's localization on a new model + public benchmark.
- 🛡️ **llm-redteam** — **1.00 precision, 0 false-positives** on held-out public jailbreaks (0.58 recall on novel framings).
- 📄 **doc2md-bench** — a real leaderboard over 3 CPU PDF→Markdown converters (MarkItDown best overall 0.795; PyMuPDF4LLM best at tables).

### LLM reliability & safety
| Project | What it does | Tests |
|---|---|---|
| [**trust-probe**](https://github.com/im-girisankar/trust-probe) | White-box ⊕ black-box hallucination "trust layer" + eval harness. **Validated: layer-19 probe AUROC 0.916 on TruthfulQA (Qwen-7B).** GPU validation runs via CI on Kaggle. | 58 |
| [**hallucination-detection-probing**](https://github.com/im-girisankar/hallucination-detection-probing) | My M.Tech thesis — detect & suppress hallucinations in Llama-3.1-8B from internal activations (AUC 0.737; layer-12–18 localization). | 9 |
| [**llm-reliability-kit**](https://github.com/im-girisankar/llm-reliability-kit) | Black-box eval library: self-consistency, NLI/lexical RAG faithfulness, a composite Hallucination Risk Index + eval harness. The deployable counterpart to the thesis. | 113 |
| [**llm-firewall**](https://github.com/im-girisankar/llm-firewall) | Runtime guardrail proxy: screens prompts (redteam detectors) and responses (reliability-kit HRI), blocking/flagging per policy — composes the repos above. | 57 |
| [**llm-redteam**](https://github.com/im-girisankar/llm-redteam) | Defensive robustness scanner — injection/jailbreak/exfiltration probes + a held-out benchmark (1.00 precision / 0.58 recall). | 154 |

### Agentic systems
| Project | What it does | Tests |
|---|---|---|
| [**repo-rag-agent**](https://github.com/im-girisankar/repo-rag-agent) | Chat with any Git repo — a real LangGraph retrieve→answer state machine with pluggable embedder/LLM/vector-store and Langfuse tracing. | 59 |

### MLOps & data
| Project | What it does | Tests |
|---|---|---|
| [**mlops-end-to-end**](https://github.com/im-girisankar/mlops-end-to-end) | Full train → track → register → serve → monitor workflow with PSI drift detection (mlflow/FastAPI/Evidently as optional backends). | 49 |
| [**modern-elt-pipeline**](https://github.com/im-girisankar/modern-elt-pipeline) | End-to-end ELT on GitHub-events data: DuckDB raw → staging → marts with data-quality checks (Dagster/dbt optional). | 51 |
| [**doc2md-bench**](https://github.com/im-girisankar/doc2md-bench) | Benchmark for MarkItDown & other PDF→Markdown converters across tables, reading order, headings, text fidelity & checkboxes — with a **real leaderboard** over 3 converters. | 92 |

---

## ⚙️ Tech

`Python` · `PyTorch` · `Transformers` · `LangGraph` · `LangChain` · `scikit-learn` · `DuckDB` ·
`pandas` · `FastAPI` · `Docker` · `AWS (EMR/Lambda)` · `Azure OpenAI` · `Airflow` · `PySpark`

## 🤝 Connect
[LinkedIn](https://linkedin.com/in/im-girisankar) · girisankargopakumar@gmail.com
