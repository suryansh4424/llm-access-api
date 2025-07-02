# 🔐 Lightweight LLM Access API with FastAPI & Ollama

This is a simple yet functional Python-based API to **control access to a local LLM (Large Language Model)** using API key authentication and credit limits. Built with **FastAPI** and **Ollama**, this project lets you limit usage per user and serve AI responses securely from a local model.

## 🚀 Features

- 🌐 REST API to interact with a local AI model
- 🔑 API key-based authentication
- 💳 Token/credit system for usage control
- 🧠 Works with `ollama`-hosted models like `mistral`
- 📦 Lightweight and dependency-minimal

---

## 🛠️ Requirements

Make sure Python 3.9+ is installed, then run:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run
Start the API:

```bash
python -m uvicorn main:app --reload
```

Use test.py to make a test call:
```bash
python test.py
```
