# llm-chat-completions-server

[![PyPI](https://img.shields.io/pypi/v/llm-chat-completions-server.svg)](https://pypi.org/project/llm-chat-completions-server/)
[![Changelog](https://img.shields.io/github/v/release/simonw/llm-chat-completions-server?include_prereleases&label=changelog)](https://github.com/simonw/llm-chat-completions-server/releases)
[![Tests](https://github.com/simonw/llm-chat-completions-server/actions/workflows/test.yml/badge.svg)](https://github.com/simonw/llm-chat-completions-server/actions/workflows/test.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/simonw/llm-chat-completions-server/blob/main/LICENSE)

LLM plugin to serve an OpenAI Chat Completions API endpoint

## Installation

Install this plugin in the same environment as [LLM](https://llm.datasette.io/).
```bash
llm install llm-chat-completions-server
```
## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then run the tests with `uv`:
```bash
cd llm-chat-completions-server
uv run pytest
```
To run LLM with your in-development plugin:
```bash
uv run llm --help
```
