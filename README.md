# Multi-Agent System using Meta LLaMA 3.3-70B (via OpenRouter API)

This project demonstrates how to build a **Multi-Agent AI System** that performs **market research** and **AI use case generation** for companies like Deloitte, McKinsey, and others using the **Meta LLaMA 3.3-70B-Instruct** model through the **OpenRouter API**.

Each agent plays a specific role — gathering data, analyzing it, and generating actionable insights — to simulate how intelligent AI agents can work collaboratively to automate research and strategy tasks.

---

## Project Overview

This project aims to show how multiple AI agents can:
- Conduct company-specific market research.
- Analyze key industry trends and challenges.
- Generate AI/ML and Generative AI use cases tailored to each company.
- Deliver results in a clear, structured format.

The system is modular, scalable, and easy to extend for other business use cases.

---

## Tech Stack

| Component | Technology Used |
|------------|-----------------|
| Programming Language | Python |
| API Model | Meta LLaMA 3.3-70B-Instruct (Free) |
| API Provider | [OpenRouter](https://openrouter.ai/meta-llama/llama-3.3-70b-instruct:free) |
| API Endpoint | `https://openrouter.ai/api/v1/chat/completions` |
| Environment | Jupyter Notebook |
| Libraries Used | `requests`, `json`, `os`, `time`, `dotenv` |

---

##  Model & API Configuration

### 🧩 Model Used:
```python
model = "meta-llama/llama-3.3-70b-instruct:free" which is freely available in open router website
just go and serch for open router--> sign in --> search 'free' in which you can get free models --> scroll down a bit and you will find create API key.
