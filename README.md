# Ai-Chatbot-
# 🤖 Nova – Human-Like Conversational Chatbot

Nova is a human-like conversational chatbot designed to demonstrate
natural conversation, contextual awareness, emotional tone adaptation,
and long-term memory across sessions.

This project was built as part of a Conversational AI assignment and
focuses on realism, personalization, and simplicity.

---

## ✨ Features

- 🧠 Long-term memory using SQLite
- 💬 Human-like conversational flow
- 🎭 Context-aware tone adaptation (friendly, empathetic, playful)
- 🪪 Consistent persona & identity
- 🔁 Memory recall across sessions
- ⚡ Powered by Google Gemini (gemini-2.5-flash)

---

## 🏗️ Architecture Overview
User Input
↓
Tone Detection
↓
Memory Extraction (SQLite)
↓
Prompt Construction (Persona + Memory + Tone)
↓
Gemini LLM
↓
Natural Language Response

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **LLM:** Google Gemini (gemini-2.5-flash)
- **Memory Store:** SQLite
- **Runtime:** Local / Terminal-based

---

## 🚀 How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/chatbot-nova.git
cd chatbot-nova

