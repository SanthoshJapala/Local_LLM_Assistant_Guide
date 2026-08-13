# Local LLM Assistant Guides

This repository contains comprehensive, step-by-step guides for setting up powerful, fully-local AI coding assistants on your own hardware. By running everything locally, you retain complete privacy over your codebase and avoid expensive API costs.

## Available Guides

### 1. [Local LLM Coding Assistant Guide](Local_LLM_Coding_Assistant_Guide.ipynb)
A deep dive into building a local AI coding assistant from scratch on Windows without using middleware. 
* **Core Technologies**: `llama.cpp`, `llama-server`, Qwen models, and the Continue VS Code extension.
* **Focus**: Hardware-specific build instructions (CPU, CUDA, Vulkan, SYCL), compiling from source, understanding performance constraints, and setting up a bare-metal local endpoint.

### 2. [Ollama Agentic Coding Guide](Ollama_Agentic_Coding_Guide.ipynb)
A streamlined guide focusing on the modern ecosystem using Ollama as a drop-in replacement for OpenAI.
* **Core Technologies**: Ollama, Continue, Cline, Claude Code, and OpenHands (OpenDevin).
* **Focus**: Leveraging Ollama's native tool-calling and OpenAI compatibility to power autonomous coding agents and advanced chat extensions effortlessly.

## Formatting Note
These guides are provided as Jupyter Notebooks (`.ipynb`) with customized executable code cells. This allows you to easily copy, paste, or run the command-line snippets directly if you are using a compatible Jupyter environment, while keeping the documentation highly readable.
