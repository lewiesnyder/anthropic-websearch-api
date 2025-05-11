# Anthropic Websearch API

A simple example of web search RAG using [Anthropic](https://www.anthropic.com/news/web-search-api)'s **Web Search Tool** as part of the [Anthropic API](https://docs.anthropic.com/en/docs/build-with-claude/tool-use/web-search-tool).

## Usage

### Requirements
1. `python ^3.11`
2. [uv](https://docs.astral.sh/uv/) for dependency management
3. An Anthropic account and API key added to a `.env` file as `ANTHROPIC_API_KEY`

### Setup
```bash
uv venv
source .venv/bin/activate
uv sync
```

### Run
Open [notebook.ipynb](notebook.ipynb) and run the notebook
