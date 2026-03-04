# Local Environment Setup

This guide will help you set up your local development environment for the
re-llm_engineering project.

## Prerequisites

- Python 3.9 or higher
- API keys for any LLM providers you intend to use (e.g., OpenAI, Anthropic)

## Install and Sync Dependencies with uv

If you haven't set up uv, see the [uv installation guide](https://github.com/astral-sh/uv#installation).

To initialize the repository and install all dependencies from the frozen lock
file, run:

```bash
uv sync --frozen
```

## Setting Up the Virtual Environment

Follow these steps to set up the virtual environment for the project:

1. **Create the virtual environment**

   ```bash
   uv venv --python 3.12.12
   ```

2. **Activate the virtual environment** (optional but useful):

   ```bash
   source .venv/Scripts/Activate
   ```

## Set Up Environment Variables

Create a `.env` file in the project root based off the `.env.example` file and
add your API keys:

```bash
cp .env.example .env
```

Then, edit the `.env` file to add your API keys:

```bash
OPENAI_API_KEY=your-openai-key
ANTHROPIC_API_KEY=your-anthropic-key
```
