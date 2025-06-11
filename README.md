# 🚀 AutoDev - Agentic AI Software Engineer 👩‍💻

# 📚 Table of Contents

• About

• Key Features

• System Architecture

• Getting Started

• Requirements

• Installation

• Usage

• Configuration

• Contributing

• Support

• License

• Star History

# 🧠 About
AutoDev is an intelligent, agentic AI software engineer designed to understand high-level human instructions, plan steps, perform research, and write code autonomously.

Built with LLMs, reasoning engines, and web automation tools, AutoDev brings the power of autonomous software development to your fingertips—whether it’s building features, debugging, or launching full-stack applications.

# ✨ Key Features
🤖 Supports Claude 3, GPT-4, Gemini, Mistral, Groq, and Local LLMs (via Ollama)

🧠 Advanced reasoning and planning capabilities

🔍 Intelligent web search and focused research

💬 Natural language command interface

💻 Multi-language code generation and editing

📂 Project-based context awareness

📊 Dynamic task tracking and visualization

🔌 Extensible architecture with plugin support

🏗️ System Architecture
See the Architecture Documentation for a detailed breakdown of AutoDev’s internal systems and components.

# 🚀 Getting Started
Requirements
bash
Copy
Edit
Python >= 3.10 and < 3.12  
Node.js >= 18  
bun (JS runtime)
Install uv for Python dependency management

Install bun

Optionally set up Ollama for local LLMs

Set API keys via the UI for model-based interactions

# Installation
Clone the repo:

bash
Copy
Edit
git clone https://github.com/stitionai/devika.git
cd devika
Create virtual environment & install Python dependencies:

bash
Copy
Edit
uv venv
source .venv/bin/activate  # Linux/macOS
.venv\Scripts\activate     # Windows
uv pip install -r requirements.txt
Install Playwright for browser automation:

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
Launch the AutoDev interface in your browser

Create or select a project

Choose your preferred search engine and model configuration

Type your objective — AutoDev will analyze, plan, and execute

Track progress, review output, and iterate with new commands

⚙️ Configuration
On first launch, AutoDev generates a config.toml file in the root directory.

Configure your keys via the settings UI:

API Keys

BING, GOOGLE_SEARCH, GOOGLE_SEARCH_ENGINE_ID

OPENAI, CLAUDE, GEMINI, MISTRAL, GROQ

NETLIFY (for deployment support)

API Endpoints

Customize endpoints for each provider (OpenAI, Ollama, Google, etc.)

# 🔐 Keep your API keys secure and avoid exposing them in public repositories.

# 🤝 Contributing
We welcome contributors! Please read our CONTRIBUTING.md to get started. Whether it's bug fixes, new features, or documentation improvements—we appreciate your support.

🛟 Support
Have questions or ideas?

Raise an issue in the issue tracker

Join the community discussions

Connect with others on our Discord Server

🪪 License
AutoDev is released under the MIT License. See the LICENSE file for details.

⭐ Star History
<p align="center"> <a href="https://star-history.com/#stitionai/devika&Date"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=stitionai/devika&type=Date&theme=dark" /> <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=stitionai/devika&type=Date" /> <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=stitionai/devika&type=Date" /> </picture> </a> </p>
We hope you find AutoDev a valuable companion in your development workflow. Contributions, feedback, and stars are always welcome! 💫
