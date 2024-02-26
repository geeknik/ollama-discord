# ollama-discord
### an ollama powered discord bot

Requirements:
- node 20.10.0+
- npm 10.2.3+
- ollama 0.1.27+
- serper api key
- openai api key (optional)

Usage:
```
screen -S ollamaDiscord
git clone https://github.com/geeknik/ollama-discord
cd ollama-discord
cp env.example .env
nano .env
npm install axios discord
node ollama-discord.js
ctrl-a-d
```

Features:
  - Free and open source discord bot
  - Local llm-powered chatbots, free from corporate control
  - Message chunking to fit into discord's 2000 character limit
  - ollama and openai are interchangeable via .env if you're hip to it

Known Issues:
  - Message chunking can result in broken lines, incomplete words
  - ThinkingMessages() doesn't convey enough information to user

TODO:
  - Improve message chunking heuristic
  - Add heuristic for estimating remaining time
  - Improve thinkingMessages() routine
  - Improve web search integration
