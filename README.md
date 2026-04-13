
# 💬 Floating AI Chatbot

A lightweight floating chatbot widget powered by the OpenAI API.

![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## Overview

A minimal, plug-and-play floating chatbot widget you can drop into any webpage. It renders as a button in the bottom-right corner and expands into a chat window connected to **GPT-4o Mini** via the OpenAI API — no frameworks or build tools required.

## File Structure

chatbot/
├── index.html   — markup and layout
├── style.css    — dark theme styling
└── script.js    — toggle logic + OpenAI API calls

## Setup

1. Clone or download this repository.
2. Open `script.js` and add your OpenAI API key and endpoint:

```js
const apiKey = "sk-...your-key-here...";
const apiUrl = "https://api.openai.com/v1/chat/completions";
```

3. Open `index.html` in a browser — no server required.

> ⚠️ **Never commit your API key to a public repository.** Use environment variables or a backend proxy for production.

## Configuration

| Option | Location | Default |
|---|---|---|
| `model` | `script.js` | `gpt-4o-mini` |
| `max_tokens` | `script.js` | `150` |
| Accent color | `style.css` | `#d32f2f` |
| Widget size | `style.css` | 350 × 450px |

## License

MIT
