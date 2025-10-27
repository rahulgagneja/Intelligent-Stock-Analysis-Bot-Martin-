🤖 AI Stock Analysis Telegram Chatbot (n8n + OpenAI)

An AI-powered Telegram chatbot built using n8n, OpenAI, and QuickChart API that delivers daily market analysis and technical insights for US and London-listed stocks — all directly on Telegram.

🚀 Features

📈 Real-time stock analysis using OpenAI’s language model

🧠 AI Agent memory for contextual conversations

💬 Telegram Bot integration for instant chat responses

📊 Auto-generated stock charts via QuickChart API

⚙️ Modular n8n workflow for easy customization

🌍 Supports US & London stock symbols (e.g., AAPL, TSLA, MSFT)

🧩 Workflow Overview

🔹 Nodes Used:

Telegram Trigger – receives user messages

PreProcessing / Settings – parses commands

OpenAI Chat Model – performs AI-based financial analysis

Simple Memory – maintains chat context

Get Chart / QuickChart API – generates stock charts

Send Chart / Send Analysis – replies with visual + text insights

| Company           | Symbol |
| ----------------- | ------ |
| Apple Inc.        | AAPL   |
| Tesla Inc.        | TSLA   |
| Microsoft Corp.   | MSFT   |
| Amazon.com Inc.   | AMZN   |
| Alphabet (Google) | GOOGL  |
| Meta Platforms    | META   |
| Netflix Inc.      | NFLX   |
| NVIDIA Corp.      | NVDA   |
(Works for all major US & London tickers supported by your stock API.)

🛠️ Setup Instructions

Create a bot using @BotFather and get your Bot Token

Add your token in the Telegram Trigger node in n8n

Add your OpenAI API Key in the AI Agent / OpenAI Chat Model node

Configure QuickChart API endpoint in your Get Chart node

Deploy the workflow on your local or cloud n8n instance

🧰 Tech Stack

n8n – Workflow automation platform

OpenAI – For natural language financial analysis

QuickChart API – Chart generation

Telegram Bot API – Chat interface

👨‍💻 Author

Rahul Gagneja
