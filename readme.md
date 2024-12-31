# Lit Bot

A simple chatbot written with Python, Langchain, and Streamlit. Uses `llama3.2` for LLM running locally via Ollama.

## Setup

### Create a virtual environment
You can use whatever you like, I use `venv` because I've been using it for a while and it works for me.

```sh
python3 -m venv .venv  
```

### Start the virtual environment

```sh
source .venv/bin/activate
```

---
## Install packages

```sh
python3 -m pip install -r requirements.txt
```
---
## Run it via Streamlit

```sh
streamlit run chat_stream.py 
```

View it http://localhost:8501

---
## Dependencies

- [Langchain](https://github.com/)
- [Streamlit](https://github.com)
- [python-dotenv](https://pypi.org/project/python-dotenv/)
- [ChatOllama](https://python.langchain.com/docs/integrations/chat/ollama/)
- [Ollama](https://ollama.com/)