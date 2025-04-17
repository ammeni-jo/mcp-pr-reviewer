# 🧠 MCP PR Reviewer

This project demonstrates the **Model-Context-Protocol (MCP)** pattern to build a Notion + GitHub powered PR reviewer using a Language Model. 

## 🚀 Features

- MCP architecture: clear separation of model, context, and protocol
- Automatically fetches PR data from GitHub
- Logs the PR review into a Notion page using the Notion API
- Easily extensible with your own LLM or review logic

## 📦 Requirements

- Python 3.10+
- `openai`, `httpx`, `notion-client`, `python-dotenv`, `typer`, etc.

Install them with:

```bash
uv pip install -r requirements.txt
