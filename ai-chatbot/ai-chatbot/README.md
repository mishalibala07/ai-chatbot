# AI Chatbot

A simple web-based AI chatbot built with Python (Flask) and the Anthropic API. It keeps conversation history, so the bot remembers what you said earlier in the chat.

## Features
- Clean chat interface with light and dark mode
- Remembers the conversation
- Easy to customize: change the personality in `SYSTEM_PROMPT` inside `app.py`

## Setup

1. Clone the repo
   ```
   git clone https://github.com/YOUR-USERNAME/ai-chatbot.git
   cd ai-chatbot
   ```
2. Create a virtual environment and install packages
   ```
   python -m venv venv
   source venv/bin/activate        # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Add your API key. Copy `.env.example` to `.env` and paste your key from https://console.anthropic.com
4. Run the app
   ```
   python app.py
   ```
5. Open http://127.0.0.1:5000

## Project structure
```
ai-chatbot/
├── app.py
├── requirements.txt
├── .env.example
├── .gitignore
└── templates/
    └── index.html
```

## Ideas to extend
- Add streaming responses
- Add a "Clear chat" button
- Give the bot a special role (study helper, recipe bot, travel guide)
- Deploy it on Render or Railway
