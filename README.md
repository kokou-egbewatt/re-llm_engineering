<!-- markdownlint-disable MD033 -->

<h1 align="center">LLM Engineering
<br>
<!-- Version Badge - update on release (must match Changelog.md) -->
<a href="https://github.com/kokou-egbewatt/re-llm_engineering/tags">
    <img src="https://img.shields.io/badge/version-0.0.0-blue" alt="Version">
</a>
</h1>
<p align="center">
  <i>A hands-on study of LLM Engineering.</i><br><br>

<!-- CI Badges -->

<a href="https://github.com/kokou-egbewatt/re-llm_engineering/actions/workflows/ci.yml">
    <img src="https://github.com/kokou-egbewatt/re-llm_engineering/actions/workflows/ci.yml/badge.svg" alt="CI">
</a>

<!-- License Badge -->

<a href="https://github.com/kokou-egbewatt/re-llm_engineering/blob/main/LICENSE">
  <img src="https://img.shields.io/badge/license-MIT-blue" alt="License: MIT">
</a>
</p>

## Overview

LLM Engineering is the discipline of building reliable, production-ready
systems powered by large language models (LLMs). It bridges the gap between raw
model capabilities and real-world applications. It combines software
engineering, prompt design, data pipelines, and evaluation to ship AI products
that actually work.

At its core, LLM engineering involves:

- **Prompt Engineering:** Crafting and iterating on inputs to reliably guide
  model behavior, including zero-shot, few-shot, and chain-of-thought
  techniques.
- **API Integration:** Connecting to hosted model providers (OpenAI, Anthropic,
  etc.) and managing tokens, costs, rate limits, and streaming responses.
- **Retrieval-Augmented Generation (RAG):** Grounding LLM outputs in external
  knowledge by combining vector databases, document retrieval, and in-context
  injection.
- **Fine-Tuning & Customization:** Adapting pre-trained models to specific
  domains or tasks using supervised fine-tuning (SFT), LoRA, or RLHF-based
  techniques.
- **Agents & Tool Use:** Building autonomous systems where LLMs reason, plan,
  and call external tools or APIs to complete multi-step tasks.
- **Evaluation & Testing:** Measuring model outputs systematically with
  benchmarks, LLM-as-judge patterns, and regression test suites.
- **Deployment & Observability:** Serving models in scalable, monitored
  pipelines with logging, latency tracking, and safety guardrails.

This repository is inspired by the `llm_engineering` course, focusing on
hands-on, practical aspects of working with large language models—from API
integration and prompt engineering to fine-tuning, deployment, and beyond. For
prerequisites and full local setup instructions, see
[docs/local_setup.md](docs/local_setup.md).
