# Awesome Claude dxt [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![Stars](https://img.shields.io/github/stars/milisp/awesome-claude-dxt?style=social)](https://github.com/milisp/awesome-claude-dxt/stargazers)
[![Forks](https://img.shields.io/github/forks/milisp/awesome-claude-dxt?style=social)](https://github.com/milisp/awesome-claude-dxt/network/members)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/dxt?style=flat&logo=reddit&label=subreddit)](https://www.reddit.com/r/dxt/)
[![Discord](https://img.shields.io/discord/1394197669794025564?logo=discord&label=discord)](https://discord.gg/N3gtxgJfby)
[![Last Commit](https://img.shields.io/github/last-commit/milisp/awesome-claude-dxt)](https://github.com/milisp/awesome-claude-dxt/commits)
[![License](https://img.shields.io/github/license/milisp/awesome-claude-dxt)](LICENSE)

<p align="center">
  🚀 <strong>New:</strong> <a href="https://www.producthunt.com/products/mcp-linker?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=awesome-claude-dxt">MCP Linker</a> — sync MCP servers between Claude Code, Codex, Cursor &amp; more — is live on Product Hunt!<br>
  <a href="https://www.producthunt.com/products/mcp-linker?utm_source=github&amp;utm_medium=readme&amp;utm_campaign=awesome-claude-dxt" target="_blank" rel="noopener noreferrer"><img alt="MCP Linker on Product Hunt" width="250" height="54" src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=1281069&amp;theme=light"></a>
</p>

A curated list of awesome (not only Claude) Desktop Extensions, tools, and resources

## What is DXT

[dxt](https://www.anthropic.com/engineering/desktop-extensions) is Desktop Extensions: One-click MCP server installation for Claude Desktop and other Desktop apps

> [!TIP]
> **⭐ Star the repo and follow [milisp](https://x.com/lisp_mi) on X and [github](https://github.com/milisp) for more**.

## Feature Projects

- [mcp-linker](https://github.com/milisp/mcp-linker) - mcp manager, add & syncs MCP server configurations across clients like Claude, Cursor
- [milisp/codexia](https://github.com/milisp/codexia) - The missing GUI for the OpenAI Codex CLI, (FileTree + notepad + git diff) all in a lightweight Tauri desktop app.

## Contents
- [Official Resources](#official-resources)
- [Community](#community)
- [Contributing](#contributing)
- [Extensions by Category](#extensions-by-category)
  - [Development Tools](#development-tools)
  - [Command Line](#command-line)
  - [File Management](#file-management)
  - [System Tools](#system-tools)
  - [Web Services](#web-services)
  - [Messaging](#messaging)
  - [Databases](#databases)
  - [Analytics](#analytics)
  - [AI Systems](#ai-systems)
  - [MCP Tools](#mcp-tools)
  - [API Integrations](#api-integrations)
  - [Data Analysis](#data-analysis)
  - [Knowledge Base](#knowledge-base)
  - [Media Creation](#media-creation)
  - [Productivity](#productivity)
  - [Professional Apps](#professional-apps)
  - [Finance](#finance)
  - [examples](#examples)
- [Development Tools](#development-tools-1)
- [Packaging & Management Tools](#packaging--management-tools)
- [Documentation & Tutorials](#documentation--tutorials)

## Official Resources
- [Desktop Extensions Announcement](https://www.anthropic.com/engineering/desktop-extensions) - Official blog post
- [DXT Specification](https://github.com/anthropics/dxt) - Open-source toolchain and specs
- [Submission Form](https://forms.gle/tyiAZvch1kDADKoP9) - Submit to official directory
- [Official examples](https://github.com/anthropics/dxt/tree/main/examples) - Official examples

## Community

* [r/dxt Reddit](https://www.reddit.com/r/dxt)
* [Discord](https://discord.gg/N3gtxgJfby)

## ☕ Support

[![GitHub Stars](https://img.shields.io/github/stars/milisp/awesome-claude-dxt?style=social)](https://github.com/milisp/awesome-claude-dxt/stargazers)

If you find this project helpful, please consider starring!

## Contributing
This list is community-maintained. See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines. Or [translate plan](./translate-plan.md)

## Extensions by Category

All extensions are located in the servers folder, each organized by owner/repo, and containing a `manifest.json` and `user_config.json`. If the `manifest.json` is verified by the community, a `verified.json` file will also be included.

### Real world ${__dirname} examples

If you have any disconnect issue check the `manifest.json` at these useful repos, python and nodejs

- [taylorwilsdon/google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) - Full natural language control over Google Calendar, Drive, Gmail, Docs, Sheets, Slides, Forms, Tasks and Chat through all MCP clients, AI assistants and developer tools

```md
"mcp_config": {
  "command": "uv",
  "args": [
    "run",
    "--directory",
    "${__dirname}",
    "python",
    "${__dirname}/main.py"
  ]
}
```

- [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) - GitHub code search and npm package exploration MCP server

### Development Tools

- [chrome-applescript](https://github.com/anthropics/dxt/tree/main/examples/chrome-applescript) - Browser automation via AppleScript
- [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) - Connect to Kubernetes cluster and manage pods, deployments, and services.
- [modelcontextprotocol/gitlab](https://github.com/modelcontextprotocol/servers/blob/main/src/gitlab) - GitLab API, enabling project management
- [modelcontextprotocol/git](https://github.com/modelcontextprotocol/servers/blob/main/src/git) - Tools to read, search, and manipulate Git repositories
- [bazinga012/mcp_code_executor](https://github.com/bazinga012/mcp_code_executor) - An MCP server that allows LLMs to execute Python code within a specified Conda environment.
- [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) - A Model Context Protocol server for Mem0, which helps with managing coding preferences.
- [modelcontextprotocol/github](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/github) - Repository management, file operations, and GitHub API integration
- [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) - Interact with [OpenAPI](https://www.openapis.org/) APIs.
- [semgrep/mcp](https://github.com/semgrep/mcp) - An MCP server for using Semgrep to scan code for security vulnerabilies. Secure your vibe coding!
- [manusa/kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server) - A powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for any Kubernetes resource, this server provides specialized tools to interact with your cluster.
- [kubestellar/console (kc-agent)](https://github.com/kubestellar/console) - AI-powered multi-cluster Kubernetes dashboard with a built-in MCP server (`kc-agent`) that exposes live fleet data (pods, deployments, Helm releases, GPU inventory, compliance policies) to any MCP-compatible AI agent — no cluster-side install required.
- [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) - A secure sandboxed Python code execution environment for MCP (Model-Client-Program) architecture.
- [supernovae-st/nika](https://github.com/supernovae-st/nika) - Read-only oracle for Nika AI workflows: validate `.nika.yaml` files, explain findings, and estimate cost before running — the MCP server ships inside the single Rust binary, with signed `.mcpb` bundles (macOS arm64 + Linux x64) on each release.
- [MindscapeHQ/mcp-server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) - MCP Server for Raygun's API V3 endpoints for interacting with your Crash Reporting and Real User Monitoring applications. This server provides comprehensive access to Raygun's API features through the Model Context Protocol.
- [baryhuang/mcp-server-any-openapi](https://github.com/baryhuang/mcp-server-any-openapi) - Interact with large [OpenAPI](https://www.openapis.org/) docs using built-in semantic search for endpoints. Allows for customizing the MCP server prefix.
- [yanmxa/multicluster-mcp-server](https://github.com/yanmxa/multicluster-mcp-server) - The gateway for GenAI systems to interact with multiple Kubernetes clusters.
- [leonardsellem/n8n-mcp-server](https://github.com/leonardsellem/n8n-mcp-server) - This MCP server provides tools and resources for AI assistants to manage n8n workflows and executions, including listing, creating, updating, and deleting workflows, as well as monitoring their execution status.
- [hannesj/mcp-openapi-schema](https://github.com/hannesj/mcp-openapi-schema) - Allow LLMs to explore large [OpenAPI](https://www.openapis.org/) schemas without bloating the context.
- [ShenghaiWang/xcodebuild](https://github.com/ShenghaiWang/xcodebuild) - 🍎 Build iOS Xcode workspace/project and feed back errors to llm.
- [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) - Provides a repo-packing MCP tool with configurable profiles that specify file inclusion/exclusion patterns and optional prompts.
- [lingodotdev/lingo.dev](https://github.com/lingodotdev/lingo.dev) - The [Model Context Protocol](https://modelcontextprotocol.io/introduction) (MCP) is a standard for connecting Large Language Models (LLMs) to external services. This guide will walk you through how to connect AI tools to Lingo.dev using MCP.
- [modelcontextprotocol/sentry](https://github.com/modelcontextprotocol/servers/blob/main/src/sentry) - Retrieving and analyzing issues from Sentry.io
- [apimatic/apimatic-validator-mcp](https://github.com/apimatic/apimatic-validator-mcp) - This repository provides a Model Context Protocol (MCP) Server for validating OpenAPI specifications using [APIMatic](https://www.apimatic.io/). The server processes OpenAPI files and returns validation summaries by leveraging APIMatic’s API.
- [riza-io/riza-mcp](https://github.com/riza-io/riza-mcp) - [Riza](https://riza.io) offers an isolated code interpreter for your LLM-generated code.
- [Boston343/starwind-ui-mcp](https://github.com/Boston343/starwind-ui-mcp) - This MCP provides relevant commands, documentation, and other information to allow LLMs to take full advantage of Starwind UI's open source Astro components.
- [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) - Model Context Protocol (MCP) is a [new, standardized protocol](https://modelcontextprotocol.io/introduction) for managing context between large language models (LLMs) and external systems. In this repository, we provide an installer as well as an MCP Server for [Cloudflare's API](https://api.cloudflare.com).
- [its-dart/dart-mcp-server](https://github.com/its-dart/dart-mcp-server) - Dart MCP Server
- [agentrpc/agentrpc](https://github.com/agentrpc/agentrpc) - > Universal RPC layer for AI agents across network boundaries and languages
- [yangkyeongmo/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) - A MCP Server that connects to [Apache Airflow](https://airflow.apache.org/) using official python client.
- [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) - This repository contains a Model Context Protocol (MCP) server with tools that can access the OpenTelemetry traces and
- [GongRzhe/JSON-MCP-Server](https://github.com/GongRzhe/JSON-MCP-Server) - JSON handling and processing server with advanced query capabilities using JSONPath syntax and support for array, string, numeric, and date operations.
- [hannesj/mcp-graphql-schema](https://github.com/hannesj/mcp-graphql-schema) - Allow LLMs to explore large GraphQL schemas without bloating the context.
- [21st-dev/magic-mcp](https://github.com/21st-dev/magic-mcp) - Magic Component Platform (MCP) is a powerful AI-driven tool that helps developers create beautiful, modern UI components instantly through natural language descriptions. It integrates seamlessly with popular IDEs and provides a streamlined workflow for UI development.
- [shannonlal/mcp-postman](https://github.com/shannonlal/mcp-postman) - MCP server for running Postman Collections locally via Newman. Allows for simple execution of Postman Server and returns the results of whether the collection passed all the tests.
- [bigcodegen/mcp-neovim-server](https://github.com/bigcodegen/mcp-neovim-server) - An MCP Server for your Neovim session.
- [rishikavikondala/mcp-server-aws](https://github.com/rishikavikondala/mcp-server-aws) - Perform operations on your AWS resources using an LLM.
- [ko1ynnky/github-actions-mcp-server](https://github.com/ko1ynnky/github-actions-mcp-server) - A Model Context Protocol (MCP) server for interacting with Github Actions.
- [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) - Integrate with Docker to manage containers, images, volumes, and networks.
- [shanejonas/openrpc-mpc-server](https://github.com/shanejonas/openrpc-mpc-server) - Interact with and discover JSON-RPC APIs via [OpenRPC](https://open-rpc.org/).
- [chargebee/agentkit](https://github.com/chargebee/agentkit) - MCP Server that connects AI agents to Chargebee platform.
- [ognis1205/mcp-server-unitycatalog](https://github.com/ognis1205/mcp-server-unitycatalog) - An MCP server that enables LLMs to interact with Unity Catalog AI, supporting CRUD operations on Unity Catalog Functions and executing them as MCP tools.
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) - The server proxies requests from client to JetBrains IDE.

### Command Line

- [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) 📇 🏠 🍎 🪟 🐧 - A swiss-army-knife that can manage/execute programs and read/write/search/edit code and text files.
- [daxaur/openpaw](https://github.com/daxaur/openpaw) - A CLI tool that adds 39 personal assistant skills to Claude Code — focus mode, task dashboard, smart home, email, calendar, and more.

### File Management

- [file-manager-python](https://github.com/anthropics/dxt/tree/main/examples/file-manager-python)

### System Tools

- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) - Integration with iTerm2 terminal emulator for macOS, enabling LLMs to execute and monitor terminal commands.
- [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) - Fast file searching capabilities across Windows (using [Everything SDK](https://www.voidtools.com/support/everything/sdk/)), macOS (using mdfind command), and Linux (using locate/plocate command).
- [kapilduraphe/okta-mcp-server](https://github.com/kapilduraphe/okta-mcp-server) - Interact with Okta API.
- [dvcrn/mcp-server-siri-shortcuts](https://github.com/dvcrn/mcp-server-siri-shortcuts) - MCP to interact with Siri Shortcuts on macOS. Exposes all Shortcuts as MCP tools.
- [SimonB97/win-cli-mcp-server](https://github.com/SimonB97/win-cli-mcp-server) - MCP server for secure command-line interactions on Windows systems, enabling controlled access to PowerShell, CMD, and Git Bash shells.
- [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) - A Model Context Protocol (MCP) server for executing command-line operations on remote servers via SSH.
- [GongRzhe/terminal-controller-mcp](https://github.com/GongRzhe/terminal-controller-mcp) - A MCP server that enables secure terminal command execution, directory navigation, and file system operations through a standardized interface.
- [modelcontextprotocol/time](https://github.com/modelcontextprotocol/servers/blob/main/src/time) - A Model Context Protocol server that provides time and timezone conversion capabilities. It automatically detects the system's timezone and offers tools for getting current time and converting between timezones.
- [dinghuazhou/sample-mcp-server-tos](https://github.com/dinghuazhou/sample-mcp-server-tos) - A sample MCP server for VolcEngine TOS that flexibly get objects from TOS.
- [ChristophEnglisch/keycloak-model-context-protocol](https://github.com/ChristophEnglisch/keycloak-model-context-protocol) - This MCP server enables natural language interaction with Keycloak for user and realm management including creating, deleting, and listing users and realms.
- [modelcontextprotocol/filesystem](https://github.com/modelcontextprotocol/servers/blob/main/src/filesystem) - Secure file operations with configurable access controls
- [Descope/descope-mcp-server](https://github.com/descope-sample-apps/descope-mcp-server) - An MCP server to integrate with [Descope](https://descope.com/) to search audit logs, manage users, and more.
- [MichaelAdamGroberman/mac-mcp](https://github.com/MichaelAdamGroberman/mac-mcp) - Native macOS control via Swift + AppKit + Accessibility + cached OSAKit. 32 typed allow-listed tools across windows, Finder, clipboard, screenshots, mouse/trackpad/keyboard (CGEvent), Mail/Calendar/Messages/Safari/Notes, iTerm/Terminal, and iPhone Mirroring. Code-signed Developer ID + hardened runtime for stable TCC grants. No `run_shell` / `run_applescript` escape hatches. Ships as a one-click `.mcpb`.

### Web Services

- [mendableai/firecrawl-mcp-server](https://github.com/mendableai/firecrawl-mcp-server) - Advanced web scraping with JavaScript rendering, PDF support, and smart rate limiting
- [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server) - Implementation of an MCP server for all [Apify Actors](https://apify.com/store).
- [executeautomation/mcp-playwright](https://github.com/executeautomation/mcp-playwright) - This MCP Server will help you run browser automation and webscraping using Playwright
- [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) - A server that flexibly fetches HTML, JSON, Markdown, or plaintext.
- [bharathvaj-ganesan/whois-mcp](https://github.com/bharathvaj-ganesan/whois-mcp) - MCP server that performs whois lookup against domain, IP, ASN and TLD.
- [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp) - This is a Python-based MCP server that provides OpenAI `web_search` build-in tool.
- [Omedia/mcp-server-drupal](https://github.com/Omedia/mcp-server-drupal) - Server for interacting with [Drupal](https://www.drupal.org/project/mcp) using STDIO transport layer.
- [pathintegral-institute/mcp.science](https://github.com/pathintegral-institute/mcp.science) - A Model Context Protocol (MCP) server for fetching webpages including html/pdf/plain text type content.
- [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) - A Model Context Protocol (MCP) server lets AI assistants like Claude use the Exa AI Search API for web searches. This setup allows AI models to get real-time web information in a safe and controlled way.
- [cyberchitta/scrapling-fetch-mcp](https://github.com/cyberchitta/scrapling-fetch-mcp) - Access text content from bot-protected websites. Fetches HTML/markdown from sites with anti-automation measures using Scrapling.
- [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) - An MCP server for Apify's open-source RAG Web Browser [Actor](https://apify.com/apify/rag-web-browser) to perform web searches, scrape URLs, and return content in Markdown.
- [RamXX/mcp-tavily](https://github.com/RamXX/mcp-tavily) - An MCP server for Tavily's search & news API, with explicit site inclusions/exclusions
- [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) - Provides tools to search Airbnb and get listing details.
- [ihor-sokoliuk/mcp-searxng](https://github.com/ihor-sokoliuk/mcp-searxng) - A Model Context Protocol Server for [SearXNG](https://docs.searxng.org/)
- [amap/amap-maps-mcp-server](https://www.npmjs.com/package/@amap/amap-maps-mcp-server) - MCP Server for the AMap Map API.
- [adenot/mcp-google-search](https://github.com/adenot/mcp-google-search) - Provides Google Search results via the Google Custom Search API
- [mfukushim/map-traveler-mcp]