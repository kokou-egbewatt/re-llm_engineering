<!-- markdownlint-disable MD024 -->
# Changelog

All notable changes to `re-llm_engineering` will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] Chat Completions - 2026-03-04

### Added

- Implementation of the "chat completions", including:
  - API client code for sending prompts and receiving responses from LLM providers
  - A Gradio UI for testing and comparing responses across providers
- Updates to CI workflows for testing and tagging

### Changed

- Refactored CI workflows to ensure `tag_on_merge` runs even if `test` is skipped.
- Updated `docs/local_setup.md` with clearer virtual environment setup instructions.

## [0.0.0] Barebones - 2024-06-01

### Added

- Project directory structure and foundational organization
- Initial README.md with project overview, topics, and resource links
- docs/local_setup.md with uv-based environment setup instructions
- CHANGELOG.md for tracking changes
- .github/pull_request_template.md for LLM project PRs
- .github/ci.yml for CI workflows on pushes and PRs
