# Research MCP Setup Example for Claude Code Web/App


https://github.com/user-attachments/assets/aa4ff1ed-7ffe-4284-9ddb-5348ce2cad8d


A pre-configured Claude Code setup with research agents for academic papers, GitHub projects, and Reddit discussions.

## Features

- **arXiv Search Agent** - Search and analyze academic papers
- **GitHub Search Agent** - Find and explore GitHub projects and code examples
- **Reddit Search Agent** - Research community discussions and opinions

## Quick Start
#### 1. Fork this repository
#### 2. Go to [Claude Code Web](https://claude.ai/code)  

#### 3. Click 'Add environment' button  
<img width="500" alt="Setup Environment Button" src="https://github.com/user-attachments/assets/a931f3b6-4b51-4908-b3a4-412c9e455ff6" />

#### 4. Setup like this.
- **Network Access:** Choose **Custom access** and allow all domains using a wildcard
- **Environment variables:** Environment Variables: Set up your Brave Search API key. You can get one from [Brave Search API](https://brave.com/search/api/).
- You can configure any MCP server you want in your fork and inject API keys as shown in the [`.mcp.json`](/.mcp.json) file.
<img width="500" alt="Environment Setup Modal" src="https://github.com/user-attachments/assets/443754cf-57d1-4b92-b6a2-e139f286f581" />  

#### 5. Select your forked repository for a new session and start asking questions
#### 6. Allow repository access (one-time setup)
#### 7. Once the environment is set up, you can use it on your phone as well (with official Claude app)!
<img width="500" alt="Mobile screenshot" src="https://github.com/user-attachments/assets/9667056e-6832-4dea-9bd1-bda9b7ad58d4" />

## Usage

You can simply ask questions like:
- “Find recent papers on transformer architectures using arxiv agent”
- “Search for React projects using TypeScript using github agent”
- “What do Reddit users think about the new iPhone? use reddit agent”

The appropriate research agent will automatically handle your query.
The research task may take a long time without feedback, so please be patient!
I hope Anthropic improves the feedback system for subagent task execution.

## Project Structure

```
.claude/agents/     # Agent definitions
.mcp.json          # MCP server configuration
arxiv-papers/      # Downloaded papers storage
```

## Requirements

- Claude Code Subscription (to access web or mobile app)
- API Key for BraveSearch
