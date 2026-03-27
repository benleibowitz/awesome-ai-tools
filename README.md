# Awesome AI Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

An opinionated collection of AI tools, models, and productivity solutions for developers and researchers. Explore the evolving AI landscape – contributions welcome!

**Legend**:
- ⭐ Author's top pick
- 🆕 New addition
- 🌟 Community favorite
- 💡 Innovative tool

## Contents

- [Quick Start](#quick-start)
- [AI Models](#ai-models)
- [LLM Clients](#llm-clients)
- [AI Back Ends](#ai-back-ends)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [AI Code Assistants](#ai-code-assistants)
- [AI Terminals](#ai-terminals)
- [AI IDEs](#ai-ides)
- [AI Git](#ai-git)
- [AI Web Browsers](#ai-web-browsers)
- [AI Productivity](#ai-productivity)
- [AI Image Generation](#ai-image-generation)
- [AI Research](#ai-research)

## Quick Start

If you're new to AI tooling and want some simple, easy ways to get your feet wet, I recommend:
- [Cursor](#cursor) - an IDE with AI
- [Warp](#warp) - an terminal with AI
- [Perplexity](#perplexity) - smarter web search
- [Claude Desktop](#claude-desktop) + a [simple filesystem MCP](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem#usage-with-claude-desktop) to get started with MCP
  - Ask Claude "what files are in my downloads folder?" or "write a simple Python script in my Downloads folder"

## AI Models

- ⭐ [Claude](https://www.anthropic.com/claude) - Talk to Claude, an AI assistant from Anthropic.
- [OpenAI API](https://openai.com/api/) - OpenAI's API provides access to GPT-3 and GPT-4 models, which performs a wide variety of natural language tasks, and Codex, which translates natural language to code.
- [Llama 2](https://ai.meta.com/llama/) - The next generation of Meta's open source large language model.

## LLM Clients

- ⭐ [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview) - Terminal integration with Anthropic's Claude models. Supports MCP.
- [OpenCode](https://opencode.ai/) - Open source CLI for using most LLM providers' models. This was good until Anthropic disallowed it in their terms of service unless you pay for API access (which is more expensive). Also, they're always a few steps behind Claude Code because they're trying to replicate all the new features.
- ⭐ <a id="claude-desktop">[Claude Desktop](https://claude.ai/download)</a> - Desktop app to interact with Claude, models from Anthropic. Supports MCP
- [OpenAI Codex](https://openai.com/codex/) - OpenAI's CLI tool for using their models
- [Google Gemini CLI](https://geminicli.com/) - Google's CLI tool for using their models
- [AnythingLLM](https://anythingllm.com/) - UI with agent integration to communicate with several model providers, supporting cloud and local models.

## AI Back Ends

- 💡 [Pieces OS](https://pieces.app) - A long-term memory agent that captures your work across IDEs, browsers, applications. Supports local and cloud models.
- [Ollama](https://ollama.com/) - Run LLMs locally.

## Model Context Protocol (MCP)

### MCP Lists

- [Awesome MCP Servers](https://mcpservers.org) - List of MCP servers.
- [MCP.so](mcp.so/servers) - List of MCP servers.
- [AWS MCP Servers](https://github.com/awslabs/mcp/) - MCP servers to use cost explorer, search documentation, create diagrams, and interact with services.

### MCP Frameworks

- [FastMCP](https://github.com/jlowin/fastmcp) - A framework to write your own MCP servers.

### MCP Security

- [MCP-Scan](https://github.com/invariantlabs-ai/mcp-scan) - Security scanner for MCP servers.

### MCP Servers

- ⭐ [AWS MCP servers](https://github.com/awslabs/mcp) - Interact with AWS services
- ⭐ [Filesystem](https://mcpservers.org/servers/modelcontextprotocol/filesystem) - Interact with your local filesystem.
- ⭐ [Terminal Controller](https://mcp.so/server/terminal-controller-mcp) - Secure terminal command execution, directory navigation, and file system operations.
- ⭐ [Playwright](https://github.com/microsoft/playwright-mcp) - Interact with Playwright for automating browser actions.
- [Fetch](https://mcpservers.org/servers/modelcontextprotocol/fetch) - Fetch content from the web. Many apps can do this natively.
- [Obsidian](https://mcpservers.org/servers/MarkusPfundstein/mcp-obsidian) - Interact with Obsidian notes.

## AI Code Assistants

- ⭐ [Cline](https://cline.bot/) - Coding assistant with bring-your-own-API-key integrations for most LLMs (very expensive with Claude, though).
- [Roo Code](https://github.com/RooVetGit/Roo-Code) - A fork of Cline.
- [Replit Ghostwriter](https://replit.com/site/ghostwriter) - Meet Ghostwriter, your partner in code.
- [Windsurf](https://windsurf.com) - Free AI-powered code acceleration toolkit.
- [GitHub Copilot](https://github.com/features/copilot) - Your AI pair programmer.
- [CodeWhisperer](https://aws.amazon.com/codewhisperer/) - Machine learning-powered coding companion from AWS.

## AI Terminals

- ⭐ <a id="warp">[Warp](https://www.warp.dev/)</a> - A terminal with native AI integration.

## AI IDEs

- ⭐ [VSCode](https://code.visualstudio.com) - IDE that got a lot better with recent plugins.
  - ⭐ [Cline](https://marketplace.visualstudio.com/items?itemName=saoudrizwan.claude-dev) - Coding assistant with bring-your-own-API-key integrations for most LLMs (very expensive with Claude 3.7 Sonnet, though).
  - [Roo Code](https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline) - A fork of Cline.
  - [GitHub Copilot](https://github.com/features/copilot) - In-IDE coding assistant.
  - [Pieces Plugin](https://pieces.app/plugins/vs-code) - Interact with Pieces from VSCode.
- ⭐ <a id="cursor">[Cursor](https://www.cursor.com/)</a> - IDE with native agent integrations and compatibility with different model providers. See [MCPs](#mcps) for possible MCP integrations for Cursor.
- [IntelliJ](https://www.jetbrains.com/idea/)
  - [Switch2Cursor](https://plugins.jetbrains.com/plugin/26309-switch2cursor) - Quickly switch from IntelliJ to Cursor.
  - [Pieces Plugin](https://pieces.app/plugins/jetbrains) - Interact with Pieces OS from IntelliJ.
  - [GitHub Copilot](https://plugins.jetbrains.com/plugin/17718-github-copilot) - In-IDE coding assistant.

## AI Git

- [OpenCommit](https://github.com/di-sukharev/opencommit) - Intelligent commit messages with LLMs.

## AI Web Browsers

- ⭐ [Opera](https://www.opera.com/) - A browser with several native AI tooling integrations like ChatGPT and Aria.
- ⭐ [Arc](https://arc.net/) - A browser with several AI features like contextual chat on a page.

## AI Browser Extensions
- [Pieces Web Extension](https://pieces.app/plugins/web-extension) - Interact with Pieces and web content in your web browser.

## AI Productivity

- [Obsidian](https://obsidian.md) - End-to-end encrypted note taking service.
  - [Pieces Plugin](https://pieces.app/plugins/obsidian) - A plugin to allow interaction with Pieces OS.
  - [mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) - Interact with your Obsidian notes from Claude via MCP.
- 💡 [Fabric](https://github.com/danielmiessler/fabric) - Standardized components for prompting AI to interact with information.

## AI Image Generation

- [Ideogram](https://ideogram.ai) - Generate images from text.

## AI Research

- ⭐ <a id="perplexity">[Perplexity](https://www.perplexity.ai/)</a> - AI-powered search engine and research assistant.
- 💡 [Fabric](https://github.com/danielmiessler/fabric) - Standardized components for prompting AI to interact with information.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
