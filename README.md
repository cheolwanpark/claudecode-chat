# Claude Code Research Chat

A specialized Claude Code setup with pre-configured research agents for academic papers, GitHub projects, and Reddit discussions.

## Features

- **arXiv Search Agent** - Search and analyze academic papers
- **GitHub Search Agent** - Find and explore GitHub projects and code examples
- **Reddit Search Agent** - Research community discussions and opinions

## Setup

Set the required environment variable:

```bash
export BRAVE_API_KEY=your_api_key_here
```

Get your API key from [Brave Search API](https://brave.com/search/api/).

## Quick Start

1. Open this project in Claude Code (Web or App)
2. The agents are automatically available in your session
3. Start asking research questions

## Usage

Simply ask questions like:

- "Find recent papers on transformer architectures"
- "Search for React projects using TypeScript"
- "What do Reddit users think about the new iPhone?"

The appropriate research agent will automatically help answer your question.

## Project Structure

```
.claude/agents/     # Agent definitions
.mcp.json          # MCP server configuration
arxiv-papers/      # Downloaded papers storage
```

## Requirements

- Claude Code (Web or Desktop App)
- Configured MCP servers for search capabilities
