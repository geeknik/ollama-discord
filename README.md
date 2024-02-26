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
- free and open source discord bot
- local llm-powered chatbots, free from corporate control
- message chunking to fit into discord 2000 character limits per message
- ollama and openai are interchangeable via .env edits
