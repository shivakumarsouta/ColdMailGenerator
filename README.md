## 📫 ColdMailGenerator

📧 *Generate Personalized Cold Emails with AI*

This project enables users to craft highly-targeted, professional cold emails automatically. By integrating cutting-edge AI tools, vector databases, and intuitive UI, it streamlines outreach efforts for job applications or client proposals.

---

## 🚀 Features

* **AI‑Generated Emails** – Powered by [LLaMA 3.1](https://github.com/facebookresearch/llama), Groq API, and LangChain.
* **Context Extraction** – Scrape and process job/career pages automatically.
* **Vector-Based Matching** – Retrieve relevant portfolio snippets using ChromaDB embeddings.
* **Interactive UI** – No-code interface built with Streamlit for quick deployment.

---

## 🏗️ Architecture

```text
User Input: Job URL or Description
↓
Scraping → Cleaning → Vector Encoding
↓
[LangChain + LLaMA + Groq]
↓
Generate Email Draft
↓
Streamlit UI (Display + Customize)
```

---

## 📦 Installation

```bash
# 1. Clone the repo
git clone https://github.com/shivkumars005/ColdMailGenerator.git
cd ColdMailGenerator

# 2. (Optional) Setup virtual environment
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Configure environment variables
create .env file and add your GROQ_API_KEY

# 5. Run the app
streamlit run app.py
```

---

## 🧪 Usage Guide

1. Paste a job posting URL or description.
2. App scrapes job title, requirements, and key info.
3. Portfolio items are retrieved via semantic search.
4. AI drafts a cold email using your profile and job match.
5. Review, customize, copy, and send.

---

## 🌟 Tech Stack

| Component       | Tech             |
| --------------- | ---------------- |
| LLM             | LLaMA 3.1        |
| Inference       | Groq API         |
| Chains & Agents | LangChain        |
| Embeddings      | ChromaDB         |
| UI              | Streamlit        |
| Dev/Prototype   | Python + Jupyter |

---

## 🧩 Customization Options

* **Vector DB** → Swap ChromaDB with FAISS, Pinecone, etc.
* **Model** → Replace LLaMA 3.1 with any other.
* **Deployment** → Streamlit Cloud, or Hugging Face Spaces

---

## 🙋‍♂️ Contact

[GitHub](https://github.com/shivkumars005) | [LinkedIn](https://linkedin.com/in/shivakumarsouta) | [Mail](shivakumarsouta18@gmail.com) | [Portfolio](https://shivakumarsouta-portfolio.vercel.app)

---

## 🙏 Credits

CodeBasics YT

---
