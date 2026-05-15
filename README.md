# AI Text-to-Speech Automation

An AI-powered Text-to-Speech automation workflow built using n8n, Murf AI, and Google Gemini API. This project automates the process of converting user text into natural-sounding AI-generated speech through workflow automation.

---

## Live Demo

🔗 Render Deployment:
https://ai-text-to-speech-automation.onrender.com

🔗 GitHub Repository:
https://github.com/anil-kumar-reddy2005/Ai-text-to-speech-automation

---

## Features

* AI-powered Text-to-Speech generation
* Workflow automation using n8n
* Murf AI voice integration
* Google Gemini API integration
* Public webhook/chatbot deployment
* Real-time automated responses
* Cloud deployment using Render

---

## Technologies Used

* n8n
* Murf AI
* Google Gemini API
* Render
* GitHub
* Webhooks
* ngrok

---

## Workflow Architecture

```text
User Input
     ↓
Chat Trigger / Webhook
     ↓
Google Gemini Processing
     ↓
Murf AI Text-to-Speech
     ↓
Audio Response Generation
```

---

## Installation & Setup

### Clone Repository

```bash
git clone https://github.com/anil-kumar-reddy2005/Ai-text-to-speech-automation.git
```

### Start n8n

```bash
n8n start
```

### Public Deployment

```bash
ngrok http 5678
```

---

## Dockerfile

```dockerfile
FROM n8nio/n8n

EXPOSE 10000

ENV N8N_PORT=10000
ENV N8N_HOST=0.0.0.0
ENV N8N_PROTOCOL=https
```

---

## Resume Highlights

* Built an AI-powered text-to-speech automation workflow using n8n and Murf AI.
* Integrated Google Gemini API for AI-driven processing.
* Deployed a cloud-hosted automation workflow on Render.
* Implemented webhook-based chatbot integration and workflow orchestration.

---

## Future Improvements

* Multi-language voice support
* Voice customization
* Audio download functionality
* Database integration
* Advanced AI agent workflows

---

## Author

Anil Kumar Reddy

GitHub:
https://github.com/anil-kumar-reddy2005

---

## License

This project is created for educational and portfolio purposes.
