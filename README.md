# LLM Webpage Summarizer

A tool that leverages Large Language Models (LLMs) to generate concise summaries of webpage content. This project uses **Ollama** for local LLM inference, eliminating the need for cloud-based APIs.

## Features
- Extracts and summarizes text from webpages
- Runs entirely locally using Ollama (privacy-focused)
- Customizable summary length and focus areas
- Supports multiple LLM models (e.g., Llama 3, Mistral)

## Quick Start

### Prerequisites
- Python 3.8+
- Ollama installed locally ([Download Ollama](https://ollama.ai/))
- Required Python packages: `requests`, `bs4`, `openai`

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/ParagD004/LLM.git
   cd LLM
2. Start your local LLM (in PowerShell/Terminal):
   ```bash
   ollama run llama3

## Verify Ollama Installation

To check installed models and their status, run:

```bash
ollama list
