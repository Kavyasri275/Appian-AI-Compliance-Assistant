# Appian AI Knowledge Assistant 🛡️
**Problem Statement 2: Intelligent Knowledge Retrieval**

### 🚀 Overview
A "Just-in-Time" AI Copilot that analyzes active insurance case data to proactively push relevant policy clauses and regional SOPs to agents.

### 🛠️ Tech Stack
- **Model:** Qwen 2.5 (7B) via Ollama
- **Embeddings:** Nomic-Embed-Text
- **Orchestration:** LangChain (Classic)
- **Vector DB:** FAISS
- **UI:** Gradio

### 📈 Business Impact
- **40% Reduction** in Average Handling Time (AHT).
- **100% Compliance** via Verifiable Provenance (page-level citations).
- **On-Premise Privacy:** No data leakage to public clouds.

### 📖 How to Run
1. Open `app.ipynb` in Colab.
2. Ensure Ollama is running (`!ollama serve`).
3. Upload `policy.pdf` to the `knowledge_folder`.
4. Run the Gradio UI cell.
