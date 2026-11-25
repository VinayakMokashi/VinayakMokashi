## Hi, I'm Vinayak

I'm a Data Science master's student at Brown University's [Data Science Institute](https://dsi.brown.edu/), and I previously worked at Accenture. I build machine-learning and LLM systems that show their work.

**Looking for Data Scientist and AI/ML Engineer roles.** The best way to reach me is [LinkedIn](https://www.linkedin.com/in/vinayak-mokashi-36b1b1214/) or email: [vinayakmokashi305@gmail.com](mailto:vinayakmokashi305@gmail.com) or [vinayak_mokashi@brown.edu](mailto:vinayak_mokashi@brown.edu).

**Tools I use most:**

- **Languages and data:** Python, SQL (PostgreSQL, DuckDB), R and Julia
- **Machine learning:** PyTorch, Hugging Face Transformers and PEFT (LoRA) · scikit-learn, XGBoost and LightGBM · Optuna and SHAP
- **LLMs and agents:** LangGraph, LangChain and MCP · the Claude API, plus open-weight models on Groq and Ollama · guardrails and structured outputs with Pydantic
- **RAG and evaluation:** hybrid search (BM25 + dense) with cross-encoder re-ranking · Qdrant and ChromaDB · Ragas and LLM-as-a-judge · tracing with Langfuse
- **Engineering and MLOps:** FastAPI, Streamlit and Docker · pytest and GitHub Actions (CI/CD) · ONNX Runtime and drift monitoring · Terraform, Google Cloud (Cloud Run) and AWS
- **AI-assisted development:** Claude Code

### Featured projects

| Project | What it is |
|:--|:--|
| **[Filings Research Copilot](https://github.com/VinayakMokashi/filings-research-copilot)** | An agentic research copilot for SEC 10-K and 10-Q filings. Every claim is cited to the page or query it came from, and every reported number on FinanceBench comes with a 95% confidence interval. Live on Google Cloud: [demo](https://ui-499690143794.asia-south1.run.app) · [project page](https://vinayakmokashi.github.io/filings-research-copilot/)<br><sub>LangGraph · Qdrant · Text-to-SQL · MCP · Cloud Run · Terraform</sub> |
| **[Lug to Lug](https://github.com/VinayakMokashi/lug-to-lug)** | A true-to-scale watch try-on (in progress). The watch you already wear becomes the ruler for your wrist, and every render reports its own sizing error. [Project page](https://vinayakmokashi.github.io/lug-to-lug/)<br><sub>Computer vision · MediaPipe · Next.js · Cloud Run · Terraform</sub> |
| **[Text2SQL Analyst](https://github.com/VinayakMokashi/text2sql-analyst)** | Ask a database a question in plain English and get an answer, a short analysis and a chart, with the generated SQL one click away. Runs entirely on free, open-weight models. [Live demo](https://text2sql-analyst-88gmykwbxbueyfjt6db6px.streamlit.app/)<br><sub>Retrieval-augmented Text-to-SQL · Groq / Ollama · ChromaDB · SQLite · Streamlit</sub> |
| **[Retail Pricing Agent](https://github.com/VinayakMokashi/retail-pricing-agent)** | An LLM pricing agent built in six measured stages: from a prompt-only baseline, through RAG, tools and a self-correcting LangGraph agent, to a validated agent where the model chooses a price and code enforces every pricing rule.<br><sub>LangChain · LangGraph · RAG · Self-RAG · LLM-as-a-judge · structured output</sub> |
| **[Season or Change?](https://github.com/VinayakMokashi/season-or-change)** | An independent study of change-aware contrastive learning (CACo, CVPR 2023) for satellite imagery. It reproduces the paper's ablation, then finds no measurable gain from change-awareness at small scale. Team project for Brown's CSCI 1470 Deep Learning.<br><sub>PyTorch · self-supervised learning · remote sensing</sub> |
| **[Animal Shelter Outcome Prediction](https://github.com/VinayakMokashi/shelter-outcome-prediction)** | Predicts what will happen to a cat or dog using only what is known at intake (135k records, six imbalanced outcomes). Tuned XGBoost roughly triples the baseline's macro-F2. Final project for Brown's DATA 1030.<br><sub>scikit-learn · XGBoost · SHAP</sub> |
| **[Information Verifier](https://github.com/VinayakMokashi/information-verifier)** | Fact-checks a WhatsApp forward, screenshot, voice note or video link in Hindi, Marathi, Tamil, Bengali or English. It checks vetted fact-checkers first and labels anything that comes from the open web. Runs as a web app and a Telegram bot.<br><sub>Claude · FastAPI · speech-to-text · OCR · SQLite</sub> |

### LLM engineering series

Runnable, step-by-step repos that build up LLM engineering from the ground up.

- **Foundations:** [gpt-from-scratch](https://github.com/VinayakMokashi/gpt-from-scratch) (a GPT in one PyTorch file) · [byte-pair-encoding](https://github.com/VinayakMokashi/byte-pair-encoding) · [basic-language-model](https://github.com/VinayakMokashi/basic-language-model) · [basic-music-model](https://github.com/VinayakMokashi/basic-music-model) · [genai-setup](https://github.com/VinayakMokashi/genai-setup) · [website-summarizer](https://github.com/VinayakMokashi/website-summarizer)
- **Prompting:** [prompt-engineering-techniques](https://github.com/VinayakMokashi/prompt-engineering-techniques) (few-shot, chain-of-thought, self-consistency, structured output)
- **Retrieval (RAG):** [rag-embeddings-basics](https://github.com/VinayakMokashi/rag-embeddings-basics) → [rag-ragas-evaluation](https://github.com/VinayakMokashi/rag-ragas-evaluation) → [rag-advanced-techniques](https://github.com/VinayakMokashi/rag-advanced-techniques) (chunking, reranking, HyDE, agentic RAG) · [inventory-rag-agent](https://github.com/VinayakMokashi/inventory-rag-agent) (policy PDFs, live SQL and a calculator in one agent)
- **Agents:** [llm-tool-calling](https://github.com/VinayakMokashi/llm-tool-calling) (tool loops and an MCP server) · [agentic-patterns-from-scratch](https://github.com/VinayakMokashi/agentic-patterns-from-scratch) (Tool Use and ReAct, no framework) · [langgraph-workflows](https://github.com/VinayakMokashi/langgraph-workflows) · [llm-agent-memory](https://github.com/VinayakMokashi/llm-agent-memory) (short-term, semantic, episodic and long-term memory)
- **Evaluation:** [llm-agent-evals](https://github.com/VinayakMokashi/llm-agent-evals) (LLM-as-a-judge validated against human labels, RAG, tool-use and planning evals, a 50-task benchmark)
- **Fine-tuning:** [finetuning-part1](https://github.com/VinayakMokashi/finetuning-part1) (sentence embeddings and a BERT classifier) · [finetuning-part2](https://github.com/VinayakMokashi/finetuning-part2) (LoRA from the SVD up, instruction tuning)
- **Speed and cost:** [llm-inference-optimization](https://github.com/VinayakMokashi/llm-inference-optimization) (distillation, caching, quantization, KV caching, speculative decoding, model cascades)

### Classic ML and statistics

| Project | Methods |
|:--|:--|
| [brain-tumor-detection-localization](https://github.com/VinayakMokashi/brain-tumor-detection-localization) | ResNet50 detection and ResUNet segmentation of brain tumors in MRI scans |
| [movie-matchmaker](https://github.com/VinayakMokashi/movie-matchmaker) | Item-based collaborative filtering on MovieLens 100K |
| [retail-customer-segmentation](https://github.com/VinayakMokashi/retail-customer-segmentation) | K-means on autoencoder- and PCA-reduced purchase behaviour |
| [kidney-disease-detection](https://github.com/VinayakMokashi/kidney-disease-detection) | Feature selection and a comparison of classifiers on clinical data |
| [disaster-tweet-prediction](https://github.com/VinayakMokashi/disaster-tweet-prediction) | TF-IDF and Word2Vec features with SVM and Naive Bayes |
| [contender-popularity-analysis](https://github.com/VinayakMokashi/contender-popularity-analysis) | VADER sentiment and machine learning on election tweets |
| [attrition-survival-analysis](https://github.com/VinayakMokashi/attrition-survival-analysis) | Kaplan-Meier, Cox proportional hazards and random survival forests (R) |
| [nikkei-225-var-cointegration](https://github.com/VinayakMokashi/nikkei-225-var-cointegration) | Vector autoregression and Engle-Granger cointegration (R) |
| [starbucks-experiential-marketing-sem](https://github.com/VinayakMokashi/starbucks-experiential-marketing-sem) | Structural equation modeling and mediation analysis with lavaan (R) |
| [image-denoising-gibbs-sampling](https://github.com/VinayakMokashi/image-denoising-gibbs-sampling) | Gibbs sampling on a Markov random field |
| [gridworld-q-learning](https://github.com/VinayakMokashi/gridworld-q-learning) | Tabular Q-learning, from scratch |

### Scientific machine learning (Julia)

| Project | What it asks |
|:--|:--|
| [hodgkin-huxley-sciml](https://github.com/VinayakMokashi/hodgkin-huxley-sciml) | When can a universal differential equation recover a hidden ionic current in a Hodgkin-Huxley neuron? (paper and code) |
| [qsir-model](https://github.com/VinayakMokashi/qsir-model) | Can an SIR model with a small neural network inside learn quarantine strength from COVID-19 data? |
| [missing-physics-discovery-lotka-volterra](https://github.com/VinayakMokashi/missing-physics-discovery-lotka-volterra) | Can a UDE plus sparse symbolic regression rediscover the missing predator-prey term from noisy data? |

### Tools and side projects

- [pawlock](https://github.com/VinayakMokashi/pawlock): locks the keyboard and trackpad when a cat walks on them, with installers for Windows, macOS and Linux
- [tokenlens](https://github.com/VinayakMokashi/tokenlens): shows what your Claude Code sessions cost, and why
- [lecture-notes-creator](https://github.com/VinayakMokashi/lecture-notes-creator): turns a lecture recording and its slides into detailed study notes (Whisper and Claude)
- [backing-tracks](https://github.com/VinayakMokashi/backing-tracks): turns a YouTube or Instagram song into a karaoke backing track in your key and tempo (Demucs vocal removal, pitch-shifting and time-stretching)
- [resume-analyzer-app](https://github.com/VinayakMokashi/resume-analyzer-app): scores a resume against a job description (Groq, Streamlit, AWS)
- [cheese-podcast-pipeline](https://github.com/VinayakMokashi/cheese-podcast-pipeline): a containerized transcribe, generate, translate and synthesize pipeline on Google Cloud
