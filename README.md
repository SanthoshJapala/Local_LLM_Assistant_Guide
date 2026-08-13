# 🤖 Local LLM Assistant Guide

> **Run powerful AI coding assistants 100% locally — no cloud, no API keys, no data leaves your machine.**

[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-brightgreen)](#)
[![Ollama](https://img.shields.io/badge/Ollama-v0.32.x-blueviolet)](#)
[![llama.cpp](https://img.shields.io/badge/llama.cpp-latest-orange)](#)

---

## 🎯 Why Local LLMs?

| Benefit | Detail |
|---------|--------|
| 🔒 **Complete Privacy** | Your code never leaves your machine — zero telemetry, zero cloud calls |
| 💰 **Zero Cost** | No API subscriptions, no per-token billing, no usage limits |
| ⚡ **Offline Ready** | Works without internet after initial model download |
| 🛠️ **Full Control** | Choose your model, quantization, and hardware acceleration |

---

## 📚 Available Guides

### 1. 🔧 [Local LLM Coding Assistant Guide](Local_LLM_Coding_Assistant_Guide.ipynb)

A deep dive into building a local AI coding assistant **from scratch** on Windows — no middleware, no shortcuts.

| | |
|---|---|
| **Runtime** | `llama.cpp` compiled from source → `llama-server` |
| **Model** | Qwen3-4B-Q4_K_M (GGUF) |
| **IDE Integration** | Continue extension for VS Code |
| **Hardware** | ~16 GB RAM, Intel Iris Xe Graphics |

**What you'll learn:**
- Compiling `llama.cpp` from source for CPU, CUDA, Vulkan, and SYCL backends
- Understanding quantization trade-offs and hardware constraints
- Running `llama-server` as a local OpenAI-compatible endpoint
- Configuring Continue in VS Code for code completion and chat

---

### 2. 🚀 [Ollama Agentic Coding Guide](Ollama_Agentic_Coding_Guide.ipynb)

A streamlined guide for the **modern local AI ecosystem** — use Ollama as a drop-in replacement for OpenAI and power autonomous coding agents.

| | |
|---|---|
| **Runtime** | Ollama (auto-detects GPU: CUDA, ROCm, Metal) |
| **Models** | Qwen3, Devstral 2, Llama 4, and more |
| **Agents** | Continue, Cline, Claude Code, OpenHands |
| **Platform** | Windows, macOS, Linux |

**What you'll learn:**
- Installing Ollama and pulling models with one command
- Leveraging native tool-calling and OpenAI API compatibility
- Setting up autonomous coding agents (Cline, OpenHands/OpenDevin)
- Using `ollama launch` for seamless agent workflows

---

## ⚡ Quick Start

```bash
# Option A — Ollama (recommended for most users)
# 1. Install Ollama from https://ollama.com
# 2. Pull a model
ollama pull qwen3:4b

# 3. Start using it
ollama run qwen3:4b

# Option B — llama.cpp (for maximum control)
# Follow the step-by-step build instructions in the Local LLM Guide notebook
```

---

## 🧰 Prerequisites

- **OS:** Windows 10/11, macOS, or Linux
- **RAM:** 8 GB minimum (16 GB+ recommended)
- **Storage:** ~5 GB free for models
- **GPU (optional):** NVIDIA (CUDA), AMD (ROCm/Vulkan), Intel (SYCL/Vulkan), or Apple Silicon (Metal)
- **Software:** VS Code, Git, Python 3.10+ (for notebooks)

---

## 📁 Repository Structure

```
📂 Local_LLM_Assistant_Guide/
├── 📓 Local_LLM_Coding_Assistant_Guide.ipynb   # Bare-metal llama.cpp guide
├── 📓 Ollama_Agentic_Coding_Guide.ipynb         # Modern Ollama + agents guide
└── 📄 README.md                                  # This file
```

---

## 📝 Formatting Note

These guides are provided as **Jupyter Notebooks** (`.ipynb`) with executable code cells. You can:
- 📖 Read them directly on GitHub (rendered markdown + code)
- ▶️ Run the command-line snippets in a Jupyter environment
- 📋 Copy-paste commands into your terminal

---

## 🤝 Contributing

Contributions are welcome! If you've set up a local LLM workflow on different hardware or with different tools, feel free to open a PR or issue.

<p align="center">
  <b>⭐ If this guide helped you, consider giving it a star!</b>
</p>
