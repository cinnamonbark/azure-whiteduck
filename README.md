# wd-ai-hackathon

## Installation

When running as devcontainer or codespace everything should be set up already.

When running locally `uv`needs to be installed:

```sh
curl --proto '=https' --tlsv1.2 -LsSf https://github.com/astral-sh/uv/releases/download/0.5.4/uv-installer.sh | sh

```

after installation run

```sh
uv sync
```

Also following vscode extensions are needed:

```sh
"ms-python.python"
"ms-toolsai.jupyter"
"ms-toolsai.jupyter-renderers"
"ms-toolsai.jupyter-keymap"
"charliermarsh.ruff"
"GitHub.copilo"
"GitHub.copilo-chat"
```

## Sanity check

Open `notebooks/00_hello_world.ipynb` and select `.venv`as kernel/virtual environment.

Execute the notebook to make sure it runs without error.

## AI Hackathon: Building Intelligent Applications with Semantic Kernel

This repository contains a series of Jupyter notebooks that guide you through building AI-powered applications using Semantic Kernel. The content progresses from basic concepts to advanced implementations, with each module containing both theoretical foundations and practical exercises.

### Prerequisites

- Python 3.8 or later
- Basic understanding of Python programming
- OpenAI API key or Azure OpenAI access
- Semantic Kernel library installed

### Notebooks Overview

#### Module 1: Introduction to Semantic Kernel

- **01_a_introduction_to_semantic_kernel.ipynb**: Theory module covering:
  - What is Semantic Kernel
  - Setting up the Kernel
  - Plugins (Native and Semantic)
  - Memory capabilities
  - Practical examples including an Emoji Translator
- **01_b_Introduction_to_semantic_kernel.ipynb**: Practical exercises for implementing small applications using core concepts:
  - Fusion-Chef: Recipe combination system
  - QnA Bot: Memory-based question answering
  - Roleplay Gamemaster: Interactive game system
  - Shell Meister: Natural language to shell command translator

