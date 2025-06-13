# 🤖 AutoDev – Autonomous AI Software Engineer

AutoDev is an intelligent, agentic AI software engineer designed to understand high-level human instructions, plan steps, perform research, and write code autonomously.

Built with LLMs, reasoning engines, and web automation tools, AutoDev brings the power of autonomous software development to your fingertips—whether it’s building features, debugging, or launching full-stack applications.

> 📝 **Inspired By:** Devin by Cognition AI  
> AutoDev is our open-source response—aiming to match (or exceed) Devin’s performance on the SWE-bench benchmark.

---

## 📚 Table of Contents
- [About](#-about)
- [Demos](#-demos)
- [Key Features](#-key-features)
- [System Architecture](#-system-architecture)
- [Getting Started](#-getting-started)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
- [Configuration](#️-configuration)
- [Contributing](#-contributing)
- [Support](#-support)
- [License](#-license)
- [Star History](#star-history)

---

## 🧠 About

AutoDev simulates the role of a real software engineer: it interprets instructions, builds plans, writes code, researches problems, and improves itself iteratively—all through natural language and intelligent agents.

---

## 🎬 Demos

Watch AutoDev in action:

📹 **[Demo Video](#)** *(Coming Soon)*

---

## ✨ Key Features

- 🤖 Supports Claude 3, GPT-4, Gemini, Mistral, Groq, and Local LLMs (via Ollama)  
- 🧠 Advanced reasoning and planning capabilities  
- 🔍 Intelligent web search and focused research  
- 💬 Natural language command interface  
- 💻 Multi-language code generation and editing  
- 📂 Project-based context awareness  
- 📊 Dynamic task tracking and visualization  
- 🔌 Extensible architecture with plugin support  

---

## 🏗️ System Architecture

See the [Architecture Documentation](#) *(Coming Soon)* for a detailed breakdown of AutoDev’s internal systems and components.

---

## 🚀 Getting Started

### Requirements

```bash
Python >= 3.10 and < 3.12  
Node.js >= 18  
bun (JavaScript runtime)  
uv (Python dependency manager)  
Optional:

Ollama (for local LLM support)

API keys for OpenAI, Claude, Gemini, etc.

Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/stitionai/devika.git
cd devika
Set up the Python environment:

bash
Copy
Edit
uv venv
source .venv/bin/activate    # Linux/macOS
.venv\Scripts\activate       # Windows

uv pip install -r requirements.txt
Install Playwright for web automation:

bash
Copy
Edit
playwright install --with-deps
Start the backend:

bash
Copy
Edit
python devika.py
You should see:

bash
Copy
Edit
root: INFO   : AutoDev is up and running!
Start the frontend:

bash
Copy
Edit
cd ui/
bun install
bun run start
Visit http://127.0.0.1:3001 to begin using AutoDev.

Usage
Launch the interface in your browser

Create or select a project

Choose your search engine and preferred LLM

Type your objective

AutoDev will analyze, plan, and execute

Track progress and iterate

⚙️ Configuration
On first launch, a config.toml file will be created in the root directory.

Use the settings UI to configure:

API Keys:

BING, GOOGLE_SEARCH, GOOGLE_SEARCH_ENGINE_ID

OPENAI, CLAUDE, GEMINI, MISTRAL, GROQ

NETLIFY (for deployment support)

API Endpoints:

Customize endpoints for OpenAI, Ollama, Google, and others.

🔐 Tip: Keep your API keys secure. Never expose them in public repositories.
