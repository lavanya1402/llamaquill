# 🦙 LlamaQuill — Blog Generator (Ollama + LangChain + Streamlit)

Generate thoughtful, audience-tuned blogs using **local LLMs via Ollama** — wrapped in a simple Streamlit UI and LangChain for prompting.

## ✨ Features
- Choose topic, target word count, and audience (Researchers / Data Scientists / General Audience)
- Select local Ollama model (`llama3`, `mistral`, `phi3`, `qwen2.5`) and tweak generation params
- Runs **fully local** (no cloud keys needed) if Ollama is available

## 🧱 Tech Stack
- **Ollama** (local LLM runtime)  
- **LangChain** (prompt templating + chat wrapper)  
- **Streamlit** (UI)

## 📦 Requirements
- Python 3.9+
- Ollama installed and running (https://ollama.com)
- The following Python packages (see `requirements.txt`):
  ```txt
  streamlit==1.39.0
  langchain==0.2.14
  langchain-community==0.2.12
