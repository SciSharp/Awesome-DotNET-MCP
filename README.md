[![MseeP.ai Security Assessment Badge](https://mseep.net/pr/scisharp-awesome-dotnet-mcp-badge.png)](https://mseep.ai/app/scisharp-awesome-dotnet-mcp)

# Awesome-DotNET-MCP
 Awesome ModelContextProtocol resources - A curated list of MCP DotNET resources

> A curated list of [Model Context Protocol (MCP)](https://modelcontextprotocol.io/) resources.

The Model Context Protocol (MCP) is an open protocol published by [Anthropic](https://www.anthropic.com/) in November 2024. It enables seamless integration between LLM applications and external data sources and tools. This repo is not just about MCP Servers but the whole ecosystem arround the protocol itself.


## Contents

- [SDKs](#sdks)
- [Servers](#servers)
- [Tools](#tools)
- [Learn](#learns)

## SDKs

### dotnet sdk
- [Offcial sdk](https://github.com/modelcontextprotocol/csharp-sdk) - The official C# SDK for Model Context Protocol servers and clients, maintained by Microsoft
- [MCPSharp](https://github.com/afrise/MCPSharp) - MCPSharp is a .NET library that helps you build Model Context Protocol (MCP) servers and clients
- [mcp-for-beginners](https://github.com/microsoft/mcp-for-beginners) - This open-source curriculum is designed to teach the concepts and fundamentals of the Model Context Protocol (MCP), with practical examples in .NET, Java, TypeScript, JavaScript and Python
- [McpDotNet.Extensions.SemanticKernel](https://github.com/StefH/McpDotNet.Extensions.SemanticKernel) - Microsoft SemanticKernel integration for the Model Context Protocol using mcpdotnet. Enables seamless use of MCP tools as AI functions.

### Offcial
- [Python](https://github.com/modelcontextprotocol/python-sdk) - Official Python SDK.
- [Typescript](https://github.com/modelcontextprotocol/typescript-sdk) - Official Typescript SDK.
- [Java](https://github.com/modelcontextprotocol/java-sdk) - Official Java SDK

### Community
- [Rust](https://github.com/jeanlucthumm/modelcontextprotocol-rust-sdk) - Community-driven Rust adaptation of offcials SDK. **:warning: Under development**.
- [Go](https://github.com/mark3labs/mcp-go) - Community-driven Go adaptation of offcials SDK. **:warning: Under development**.
- [FastMCP](https://github.com/punkpeye/fastmcp) - A TypeScript framework for building MCP servers capable of handling client sessions.

## Servers

All current MCP servers are not in one language. Here is a list from official repository with associated programming languages.

### DotNET 
- [NetContextServer](https://github.com/willibrandon/NetContextServer) - A .NET Codebase Context MCP Server that provides AI assistants with access to your .NET codebase through the MCP
- [PiecesMCPNet](https://github.com/jimbobbennett/PiecesMCPNet) - A C# implementation of MCP  using Pieces Long-Term Memory powered by the Pieces C# SDK.
- [DotNetMetadataMcpServer](https://github.com/V0v1kkk/DotNetMetadataMcpServer) - A Model Context Protocol (MCP) server that provides detailed type information from .NET projects for AI coding agents
- [mcp_studio](https://github.com/Ming-jiayou/mcp_demo) - A simple example of building an MCP client using C#
- [https://github.com/wondeks/unity-mcp](https://github.com/justinpbarnett/unity-mcp) - A Unity MCP server that allows MCP clients like Claude Desktop or Cursor to perform Unity Editor actions
- [RhinoMCPServer](https://github.com/4kk11/RhinoMCPServer) - A plugin for executing Model Context Protocol (MCP) server in Rhinoceros. It provides Rhino's functionality as MCP tools and enables efficient communication with MCP clients
- [revit-mcp-plugin](https://github.com/revit-mcp/revit-mcp-plugin) - This project is the Revit client (receives messages, operates Revit) and needs to be used in conjunction with revit-mcp(provides tools to AI).
- [spicedb-mcp](https://github.com/DGuhr/spicedb-mcp) - highly experimental MCP to ask spicedb some questions
- [mcpservers](https://github.com/StefH/mcpservers) - A collection of MCP (Model Context Protocol) servers as dotnet tools
- [iotgateway](https://github.com/iioter/iotgateway) - A cross-platform IoT gateway based on .net8
- [iotsharp](https://github.com/IoTSharp/IoTSharp) - IoTSharp is an open-source IoT platform for data collection, processing, visualization, and device management.
- [mcp-auth-servers](https://github.com/Azure-Samples/mcp-auth-servers) - Reference servers that demo how authentication works with the current Model Context Protocol spec.
- [remote-mcp-webapp-dotnet](https://github.com/Azure-Samples/remote-mcp-webapp-dotnet) - This project contains a .NET web app implementation of a Model Context Protocol (MCP) server. The application is designed to be deployed to Azure App Service.
- [remote-mcp-functions-dotnet](https://github.com/Azure-Samples/remote-mcp-functions-dotnet) - This is a quickstart template to easily build and deploy a custom remote MCP server to the cloud using Azure functions.
- [MCP_PostgreSQL](https://github.com/NghiaBHT/MCP_PostgreSQL) - MCP_PostgreSQL is a .NET solution that provides integration between Model Context Protocol (MCP) and PostgreSQL databases
- [KnowledgeBaseServer](https://github.com/mbcrawfo/KnowledgeBaseServer) - Model Context Protocol (MCP) server allowing LLMs to store and search knowledge in a SQLite database
- [azure-mcp](https://github.com/Azure/azure-mcp) - This repository is for development of the Azure MCP Server, bringing the power of Azure to your agents.
- [dotnet-mcp-hero](https://github.com/danielmackay/dotnet-mcp-hero) - A .NET-based superhero management system comprised of a Clean Architecture API backend and a Model Context Protocol (MCP) server for AI assistant integration.
- [mcp-dotnet-samples](https://github.com/microsoft/mcp-dotnet-samples) - This collection of samples demonstrates how to leverage the Model Context Protocol in .NET applications.
- [McpMidiSequencer](https://github.com/bradygaster/McpMidiSequencer) -
- [mcp-auth-servers](https://github.com/Azure-Samples/mcp-auth-servers) - Reference MCP servers that demo how authentication works with the current Model Context Protocol spec
- [QuickMCP](https://github.com/gunpal5/QuickMCP) - Effortlessly Build Model Context Protocol Servers with OpenAPI or Swagger or Google Discovery Specifications
- [eShopLite](https://github.com/Azure-Samples/eShopLite) - eShopLite is a set of reference .NET applications implementing an eCommerce site with features like Semantic Search, MCP, Reasoning models and mo
- [mcp-template-dotnet](https://github.com/NikiforovAll/mcp-template-dotnet) - This repository contains a template for creating a Model Context Protocol (MCP) application in .NET. It provides a basic structure and example code to help you get started with building your own MCP-enabled applications
- [mcpservers](https://github.com/StefH/mcpservers) - A collection of MCP (Model Context Protocol) servers as dotnet tools
- [hangfire-mcp](https://github.com/NikiforovAll/hangfire-mcp) - Enqueue background jobs using Hangfire MCP server
- [https://github.com/shyam-menon/MCPSecure](https://github.com/shyam-menon/MCPSecure) - Secure MCP Server and Client Samples
- [runjs](https://github.com/CharlieDigital/runjs) - An MCP server that lets LLMs generate and execute JavaScript safely in an embedded .NET runtime sandbox using the Jint library. Includes support for fetch and API secrets management + injection into API calls
- [sjtu-mcp-server](https://github.com/SJTU-Geek/sjtu-mcp-server) - 本项目基于MCP协议构建校园服务Agent，通过标准化接口将大模型与校园信息系统（如课表查询、图书馆预约、成绩分析等）深度对接，用户仅需自然语言指令即可完成复杂操作
- [DBChatPro](https://github.com/alex-wolf-ps/dbchatpro) - DBChatPro is an application designed to facilitate seamless communication with your database.
- [AvaloniaUI.MCP](https://github.com/decriptor/AvaloniaUI.MCP) - Professional Model Context Protocol Server for AvaloniaUI Development
- [SQL-AI-samples](https://github.com/Azure-Samples/SQL-AI-samples) - Samples using AI and Azure SQL DB

#### Official
- [FileSystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) - Secure file operations with configurable access controls.
- [Github](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Repository management, file operations, and GitHub API integration.
- [Gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) - GitLab API, enabling project management.
- [Google Drive](https://github.com/modelcontextprotocol/servers/tree/main/src/gdrive) - File access and search capabilities for Google Drive.
- [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - Read-only database access with schema inspection.
- [Slack](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Channel management and messaging capabilities.
- [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) - Knowledge graph-based persistent memory system.
- [Puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) - Browser automation and web scraping.
- [Brave Search](https://github.com/modelcontextprotocol/servers/tree/main/src/brave-search) - Web and local search using Brave's Search API.
- [Google Maps](https://github.com/modelcontextprotocol/servers/tree/main/src/google-maps) - Location services, directions, and place details.
- [AWS Knowledge Base Retrieval](https://github.com/modelcontextprotocol/servers/tree/main/src/aws-kb-retrieval-server) - Retrieve information from the AWS Knowledge Base using the Bedrock Agent Runtime.
- [WASImancer](https://github.com/sea-monkeys/WASImancer) - WASImancer is an innovative Model Context Protocol (MCP) server built with Node.js that enhances tool execution through WebAssembly plugins

#### Community
- [Cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) - Deploy, configure & interrogate your resources on the Cloudflare developer platform (e.g. Workers/KV/R2/D1).
- [Raygun](https://github.com/MindscapeHQ/mcp-server-raygun) - Interact with your crash reporting and real using monitoring data on your Raygun account.
- [Kagi](https://github.com/ac3xx/mcp-servers-kagi) - A Model Context Protocol server implementation for Kagi's API.
- [Exa.ai](https://github.com/theishangoswami/exa-mcp-server) - Use the Exa AI Search API for web searches.
- [Youtube](https://github.com/anaisbetts/mcp-youtube) - Uses `yt-dlp` to download subtitles from YouTube.
- [AppleScript](https://github.com/joshrutkowski/applescript-mcp) - Implements interaction with macOS via AppleScript.
- [Make](https://github.com/integromat/make-mcp-server) - Turn Make scenarios into callable tools for AI assistants.
- [VSCode Devtools (Bifrost)](https://github.com/biegehydra/BifrostMCP) - Connect to VSCode IDE and use semantic tools like `find_usages`.
- [mem0-mcp](https://github.com/pinkpixel-dev/mem0-mcp) - Enables long-term memory for AI agents through a simple API or as a drop-in MCP server
### Python

#### Official
- [Git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Tools to read, search, and manipulate Git repositories.
- [Sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - Database interaction and business intelligence capabilities.
- [Sentry](https://github.com/modelcontextprotocol/servers/tree/main/src/sentry) - Retrieving and analyzing issues from Sentry.io.
- [Fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) - Web content fetching and conversion for efficient LLM usage.
- [Stdio](https://github.com/modelcontextprotocol/python-sdk/blob/main/src/mcp/server/stdio.py) - Communicate with an MCP client through standard input/output streams.
- [Websocket](https://github.com/modelcontextprotocol/python-sdk/blob/main/src/mcp/server/websocket.py) - WebSocket server transport. This is an ASGI application, suitable to be used with a framework like Starlette and a server like Hypercorn.

#### Community
- [OpenAI](https://github.com/pierrebrunelle/mcp-server-openai) - Query OpenAI models directly from Claude.
- [Phabricator](https://github.com/baba786/phabricator-mcp-server) - Interact with Phabricator API.
- [Obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) - Interact with Obsidian.
- [Filesystem](https://github.com/philgei/mcp_server_filesystem) - File operations with configurable access controls.
- [ZenML](https://github.com/zenml-io/mcp-zenml) - Chat with your MLOps and LLMOps pipelines using the official ZenML MCP server.

### Go
- [Filesystem](https://github.com/mark3labs/mcp-filesystem-server) - File operations with configurable access controls.

## Tools

### Official
- [Server inspector](https://github.com/modelcontextprotocol/inspector) - Visual testing tool for MCP servers.
- [supergateway](https://github.com/supercorp-ai/supergateway) - Run MCP stdio servers over SSE and SSE over stdio. AI gateway.
- [mcp-agents-hub](https://github.com/mcp-agents-ai/mcp-agents-hub) - The open-source ecosystem for building, discovering, and deploying Model Context Protocol servers and clients
- [mcp-k8m](https://github.com/weibaohui/k8m) - k8m is an AI-driven Mini Kubernetes AI Dashboard lightweight console tool designed to simplify cluster management. It is built on AMIS and uses kom as the Kubernetes API client. k8m comes with built-in interaction capabilities powered by the Qwen2.5-Coder-7B model and supports integration with your private AI models
- [koala-ai](https://token-ai.cn/koala-ai) - KoalaAI is a cross-platform desktop application designed to provide users with a friendly interface for interacting with large language models (LLMs).
- [Unla](https://github.com/AmoyLab/Unla) - A lightweight gateway service that instantly transforms existing APIs into MCP servers with zero code changes. Features Docker deployment and management UI, requiring no infrastructure modifications

### Community
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel/tree/main/dotnet/samples/Demos/ModelContextProtocol) - Support for Semantic kernel.
- [MCP Installer](https://github.com/anaisbetts/mcp-installer) - A server that installs other MCP servers for you.
- [MCP get](https://github.com/michaellatman/mcp-get) - A command-line tool for installing and managing Model Context Protocol (MCP) servers.
- [Fast MCP](https://github.com/jlowin/fastmcp) - Create tools, expose resources, and define prompts with clean Pythonic code.
- [MCPP.NET](https://github.com/xuzeyu91/MCPP.Net) - MCPP.Net is an implementation of the Model Context Protocol (MCP) server based on.NET 8, which supports dynamically converting Swagger APIs into MCP tools, enabling AI tools to call these APIs via the MCP protocol.
- [McpServerToolGenerator/](https://github.com/dotnetspark/McpServerToolGenerator/) - McpServerToolsGenerator is a Roslyn incremental source generator for C# that automatically generates static tool classes for server-side tools in the ModelContextProtocol (MCP) ecosystem


## Learns

### Articles
- [Building MCP Servers in C# with MCPSharp: A Complete Tutorial](https://medium.com/@afrise/building-ai-powered-tools-in-c-with-mcpsharp-a-complete-tutorial-0daadc63cfbc)
- [Integrating Model Context Protocol Tools with Semantic Kernel: A Step-by-Step Guide](https://devblogs.microsoft.com/semantic-kernel/integrating-model-context-protocol-tools-with-semantic-kernel-a-step-by-step-guide/)
- [Simplifying Model Context Protocol (MCP) Server Distribution with .NET Global Tools](https://nikiforovall.github.io/dotnet/2025/04/02/mcp-template-getting-started.html)
- [mcp-workshop-dotnet](https://github.com/Azure-Samples/mcp-workshop-dotnet) - This provides workshop materials using official MCP SDK
