<!-- markdownlint-disable MD024 -->
# Changelog

All notable changes to `re-llm_engineering` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0] Tool Calling - 2026-03-05

### Added

- A notebook exploring tool calling with function dispatch, including:
  - Defining tools with JSON schema
  - Detecting `finish_reason == "tool_calls"` and parsing arguments
  - Looping until the model returns `finish_reason == "stop"`
  - Using a SQLite DB as a real data source (e.g. price lookup)

## [0.2.0] Tokenization and Stateless Memory - 2026-03-05

### Added

- Tokenization and stateless memory exploration notebook under `concepts/tokens-memory/`:
  - Demonstrates encoding/decoding text to token IDs with `tiktoken`
  - Multi-turn chat loop with manual conversation history and live token count before each OpenAI API call
  - Loads API key from `.env` (never hardcoded)
  - Prints warnings as context window limit is approached; documents behavior when limit is exceeded
  - Gradio UIs for token-aware chatbot and token inspector

## [0.1.0] Chat Completions - 2026-03-04

### Added

- Implementation of the "chat completions", including:
  - API client code for sending prompts and receiving responses from LLM providers
  - A Gradio UI for testing and comparing responses across providers
- Updates to CI workflows for testing and tagging

### Changed

- Refactored CI workflows so that `tag_on_merge` runs when the `test` job is skipped.
- Updated `docs/local_setup.md` with clearer virtual environment setup instructions.

## [0.0.0] Barebones - 2024-06-01

### Added

- Project directory structure and foundational organization
- Initial README.md with project overview, topics, and resource links
- docs/local_setup.md with uv-based environment setup instructions
- CHANGELOG.md for tracking changes
- .github/pull_request_template.md for LLM project PRs
- .github/ci.yml for CI workflows on pushes and PRs
