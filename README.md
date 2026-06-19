# Hi, I'm Girisankar G 👋

**AI Engineer — LLM systems, agentic tooling, evaluation & the data infra behind them.**

M.Tech in Data Science & AI (CUSAT). I build production LLM systems and the tooling that
keeps them honest. IBM WatsonX research grant recipient; thesis on **proactive hallucination
detection via internal activation probing**. Background spans agentic apps, LLM evaluation,
MLOps, and large-scale data engineering.

- 🔭 Focus: **LLM reliability & safety · agentic systems · MLOps & data pipelines**
- 🧠 Production experience: Azure OpenAI agents, RAG over unstructured documents, ETL on AWS (Airflow/PySpark)
- 📫 [LinkedIn](https://linkedin.com/in/im-girisankar) · girisankargopakumar@gmail.com

---

## 🛠️ Featured projects

Every repo below is built to run and is covered by tests (heavy LLM libraries kept optional/lazy
so the cores run offline) — **~530 passing tests across the portfolio.**

### LLM reliability & safety
| Project | What it does | Tests |
|---|---|---|
| [**hallucination-detection-probing**](https://github.com/im-girisankar/hallucination-detection-probing) | My M.Tech thesis — detect & suppress hallucinations in Llama-3.1-8B from internal activations (AUC 0.737; layer-12–18 localization). | 9 |
| [**llm-reliability-kit**](https://github.com/im-girisankar/llm-reliability-kit) | Black-box eval library: self-consistency, RAG faithfulness, a composite Hallucination Risk Index + eval harness. The deployable counterpart to the thesis. | 92 |
| [**llm-redteam**](https://github.com/im-girisankar/llm-redteam) | Defensive robustness scanner — probes your own LLM deployments with prompt-injection / jailbreak / exfiltration attacks and scores resistance. | 123 |

### Agentic systems
| Project | What it does | Tests |
|---|---|---|
| [**repo-rag-agent**](https://github.com/im-girisankar/repo-rag-agent) | Chat with any Git repo — a real LangGraph retrieve→answer state machine with pluggable embedder/LLM/vector-store and Langfuse tracing. | 59 |

### MLOps & data
| Project | What it does | Tests |
|---|---|---|
| [**mlops-end-to-end**](https://github.com/im-girisankar/mlops-end-to-end) | Full train → track → register → serve → monitor workflow with PSI drift detection (mlflow/FastAPI/Evidently as optional backends). | 49 |
| [**modern-elt-pipeline**](https://github.com/im-girisankar/modern-elt-pipeline) | End-to-end ELT on GitHub-events data: DuckDB raw → staging → marts with data-quality checks (Dagster/dbt optional). | 51 |
| [**ds-devsurvey-analysis**](https://github.com/im-girisankar/ds-devsurvey-analysis) | Data-science case study — what drives developer compensation? EDA + gradient boosting + feature importances. | 52 |
| [**doc2md-bench**](https://github.com/im-girisankar/doc2md-bench) | Benchmark for Microsoft markitdown & other PDF→Markdown converters across tables, reading order, headings, text fidelity & checkboxes. | 92 |

---

## ⚙️ Tech

`Python` · `PyTorch` · `Transformers` · `LangGraph` · `LangChain` · `scikit-learn` · `DuckDB` ·
`pandas` · `FastAPI` · `Docker` · `AWS (EMR/Lambda)` · `Azure OpenAI` · `Airflow` · `PySpark`

## 🤝 Connect
[LinkedIn](https://linkedin.com/in/im-girisankar) · girisankargopakumar@gmail.com
