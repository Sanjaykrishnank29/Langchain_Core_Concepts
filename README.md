<div align="center">
  
# 🦜🔗 LangChain Updated: Advanced Agentic Workflows & LLM Integration

[![Python Version](https://img.shields.io/badge/python-3.14%2B-blue.svg)](https://www.python.org/downloads/)
[![LangChain](https://img.shields.io/badge/LangChain-1.3%2B-green.svg)](https://python.langchain.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-brightgreen.svg)](https://github.com/Sanjaykrishnank29/Langchain_Core_Concepts)

*A comprehensive exploration of modern LangChain capabilities, AI agents, and advanced LLM integration techniques.*

</div>

---

## 📖 Overview

Welcome to the **LangChain Updated** repository! This project serves as a structured, hands-on guide to mastering the latest features of [LangChain](https://python.langchain.com/). Designed for AI engineers, data scientists, and developers, this repository demonstrates how to build robust, scalable, and intelligent applications using Large Language Models (LLMs).

Whether you are looking to integrate multi-modal models, design sophisticated tool-calling agents, or enforce structured outputs, this repository provides production-ready code examples and detailed Jupyter Notebooks.

---

## 🚀 Key Features & Topics Covered

The repository is organized into focused modules, each demonstrating a core concept in the modern LangChain ecosystem:

- **1. LangChain Intro & Agents (`1-langchaininto.ipynb`)**
  - Introduction to LangChain v1.3+.
  - Building autonomous agents using `ChatGroq` and high-performance open-weight models (e.g., Qwen, Llama).
- **2. Model Integration (`2-modelintergration.ipynb`)**
  - Seamlessly integrating multiple LLM providers (OpenAI, Google GenAI, HuggingFace, Groq).
  - Standardizing interactions across diverse model architectures.
- **3. Tool Calling & Execution Loops (`3-tools.ipynb`)**
  - Empowering LLMs with external tools (e.g., APIs, custom Python functions).
  - Managing Tool Execution Loops and analyzing agent reasoning chains.
- **4. Message Management (`4-messages.ipynb`)**
  - Handling conversational context and chat history.
  - Deep dive into `AIMessage`, `HumanMessage`, and `ToolMessage` abstractions.
- **5. Structured Output (`5-structuredoutput.ipynb`)**
  - Forcing LLMs to return strict, parsable JSON or Pydantic models.
  - Ensuring reliability in data extraction pipelines.
- **6. Middleware & Advanced Concepts (`6-middleware.ipynb`)**
  - Utilizing callbacks, streaming, and middleware for monitoring and observing LLM applications.

---

## 🛠️ Technology Stack

This project utilizes cutting-edge tools in the Generative AI landscape:

- **Core Framework**: [LangChain](https://python.langchain.com/)
- **LLM Providers**: 
  - OpenAI (`langchain-openai`)
  - Groq (`langchain-groq`)
  - Google Gemini (`langchain-google-genai`)
  - HuggingFace (`langchain-huggingface`)
- **Environment Management**: `python-dotenv`, `uv`
- **Development**: Jupyter Notebooks (`ipykernel`)

---

## ⚙️ Setup & Installation

This project uses modern Python packaging via `pyproject.toml` and supports `uv` for lightning-fast dependency resolution.

### Prerequisites
- Python 3.14 or higher
- An API Key from at least one supported provider (e.g., Groq, OpenAI).

### Quickstart

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sanjaykrishnank29/Langchain_Core_Concepts.git
   cd langchain_updated
   ```

2. **Set up a virtual environment and install dependencies:**
   *Using `uv` (Recommended):*
   ```bash
   uv venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   uv pip install -e .
   ```
   *Using standard `pip`:*
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Configure Environment Variables:**
   Create a `.env` file in the root directory and add your API keys:
   ```ini
   GROQ_API_KEY=your_groq_api_key_here
   OPENAI_API_KEY=your_openai_api_key_here
   GOOGLE_API_KEY=your_google_api_key_here
   ```

4. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```
   Navigate to the `updatedlangchain/` directory and start exploring the notebooks!

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! If you have suggestions for new LangChain patterns or improvements to the existing notebooks, feel free to open a PR.

---

## 📝 License

This project is open-source and available under the **MIT License**. See the [LICENSE](LICENSE) file for more details.

---
<div align="center">
  <i>Built with ❤️ by an AI Enthusiast. Feel free to reach out for collaborations!</i>
</div>
