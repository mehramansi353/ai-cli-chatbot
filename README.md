# 🤖 AI CLI Chatbot

A configurable Command Line Interface (CLI) chatbot built using Python that supports multiple Large Language Model (LLM) providers.

Currently Supported Providers

- OpenAI
- Google Gemini

---

## Features

- Provider-based architecture
- Configuration-driven model selection
- Environment variable support
- Interactive CLI conversation
- Easy provider switching
- Clean modular codebase

---

## Project Structure

```text
.
├── main.py
├── llm_provider.py
├── config.json
├── requirements.txt
├── .env.example
├── README.md
└── .gitignore
```

---

## Installation

```bash
git clone https://github.com/mehramansi353/ai-cli-chatbot.git

cd ai-cli-chatbot

pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file

```
OPENAI_API_KEY=your_key
GEMINI_API_KEY=your_key
```

---

## Running

```
python main.py
```

---

## Architecture

```
User

↓

CLI

↓

LLM Provider

↓

OpenAI / Gemini

↓

LLM Response
```

---

## Future Improvements

- Conversation History
- Streaming Responses
- Anthropic Claude
- Ollama Support
- Logging
- Retry Mechanism
- Unit Testing

---

## Author

Mansi Mehra