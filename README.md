# Ollama Router: Open-Source LLM Tool Routing with Python

Welcome to **Ollama Router**, an open-source Python project that demonstrates how to build a tool-enabled LLM router using [Ollama](https://ollama.com/) and custom Python functions. This project shows how to connect LLMs to external tools (like weather and email), route user queries to the right tool, and maintain a secure, controlled workflow — all running locally and fully open source.

---

## 🚀 Features

- **LLM Tool Routing**: Automatically detects user intent and routes requests to the appropriate tool (e.g., get weather, send email).
- **Ollama Integration**: Uses Ollama to run open-source LLMs locally — no data leaves your machine.
- **Custom Tools**: Includes Python implementations for sending emails and fetching weather data.
- **Security-Focused Prompting**: Enforces strict tool activation protocols and input validation.
- **Extensible**: Easily add new tools or models.

---

## 📂 Project Structure

- `Ollama_router.ipynb` - Main Jupyter notebook with all code and documentation.

**Key Components:**
- Tool definitions (`send_email`, `get_weather`)
- Python functions for each tool
- System prompt for secure, controlled tool access
- Ollama LLM chat integration and routing logic

---

## 🛠️ Requirements

- Python 3.8+
- [Ollama](https://ollama.com/) installed and running locally
- Required Python packages:
  - `ollama`
  - `python_weather`
  - `smtplib`, `email` (standard library)
  - `asyncio`

Install dependencies with:

```bash
pip install ollama python_weather
