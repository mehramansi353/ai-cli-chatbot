# 🤖 AI CLI Chatbot

A configurable Command Line Interface (CLI) chatbot built using Python that supports multiple Large Language Model (LLM) providers.

Currently Supported Providers

- OpenAI
- Google Gemini

- Google Gemini 3.5 Flash Model output/response from chatbot:

  <img width="1790" height="912" alt="image" src="https://github.com/user-attachments/assets/55f6cb7a-dfd7-4067-9ae8-924ce4080ace" />



- Open AI GPT 4o-mini Model output/response from chatbot:

  <img width="1777" height="836" alt="image" src="https://github.com/user-attachments/assets/6eacb79b-1e45-4568-9fa2-4c1c7901ef22" />

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
