# Awesome Model Context Protocol (MCP)

> **Note:** This repository contains an *automatically compiled* list of frameworks, tools, and resources related to the Model Context Protocol (MCP).

This curated list focuses on tools, implementations, and resources for the Model Context Protocol - an open protocol that enables seamless integration between LLM applications and external data sources and tools.

## What is Model Context Protocol (MCP)?

Model Context Protocol (MCP) is an open protocol developed by Anthropic that standardizes how AI applications connect with external data sources and tools. It enables:

- Sharing contextual information with language models
- Exposing tools and capabilities to AI systems
- Building composable integrations and workflows

Table of Contents:
- [Core MCP Frameworks & Implementations](#core-mcp-frameworks-&-implementations) 
    - [MCP Servers & Clients](#mcp-servers-&-clients) 
        - [MCP Servers](#mcp-servers) (24)

        - [MCP Clients](#mcp-clients) (12)

        - [MCP Proxies & Bridges](#mcp-proxies-&-bridges) (2)


    - [MCP Directories & Collections](#mcp-directories-&-collections) (2)

    - [MCP Utilities & Tools](#mcp-utilities-&-tools) (2)


- [Agent Frameworks & Orchestration](#agent-frameworks-&-orchestration) 
    - [Multi-Agent & Autonomous Frameworks](#multi-agent-&-autonomous-frameworks) 

        - [JavaScript/TypeScript Multi-Agent Frameworks](#javascript/typescript-multi-agent-frameworks) (1)






- [MCP Integration with Development Tools](#mcp-integration-with-development-tools) 




- [Domain-Specific MCP Applications](#domain-specific-mcp-applications) 





- [Multimodal & Specialized MCP Tools](#multimodal-&-specialized-mcp-tools) 




- [Cloud & Infrastructure MCP Solutions](#cloud-&-infrastructure-mcp-solutions) 

    - [Self-Hosted & Local Deployments](#self-hosted-&-local-deployments) (2)



- [Resources & Educational Materials](#resources-&-educational-materials) 
    - [Curated Lists & Collections](#curated-lists-&-collections) (2)


    - [Benchmarks & Evaluations](#benchmarks-&-evaluations) (1)





## Core MCP Frameworks & Implementations


### MCP Servers & Clients


#### MCP Servers

- [AgentDeskAI/browser-tools-mcp](https://github.com/AgentDeskAI/browser-tools-mcp) (★365 JavaScript) - BrowserTools MCP is a tool that monitors and captures browser data to enable AI applications through the Model Context Protocol.
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) (★68 TypeScript) - MemoryMesh is a knowledge graph server that utilizes the Model Context Protocol to provide structured memory persistence and dynamic tools for enhancing AI model interactions.
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) (★70 JavaScript) - A Model Context Protocol server that integrates DeepSeek's advanced language models with MCP-compatible applications.
- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) (★303 TypeScript) - A MCP server that delivers Figma design metadata to AI coding agents like Cursor.
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) (★106 JavaScript) - A MCP proxy server that enables integration between client tools and JetBrains IDEs.
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) (★202 TypeScript) - A TypeScript framework for building Model Context Protocol (MCP) servers with automatic tool, resource, and prompt discovery.
- [RafalWilinski/aws-mcp](https://github.com/RafalWilinski/aws-mcp) (★94 TypeScript) - An MCP server that allows AI assistant Claude to interact with AWS resources using natural language.
- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) (★124 TypeScript) - This project implements an MCP server that enables semantic search and retrieval augmented generation over Apple Notes for AI assistants like Claude.
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) (★899 ) - A curated list of production-ready and experimental Model Context Protocol servers that extend AI capabilities.
- [beclab/Olares](https://github.com/beclab/Olares) (★1871 Shell) - Olares is an open-source sovereign cloud OS that enables secure, self-hosted deployment of local AI models and applications through a Model Context Protocol-like integration.
- [cyanheads/atlas-mcp-server](https://github.com/cyanheads/atlas-mcp-server) (★88 TypeScript) - A Model Context Protocol server built in TypeScript with Neo4j integration that enhances project management and collaboration for LLM agents.
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) (★58 Python) - A Model Context Protocol server that provides secure and structured MySQL database interactions for AI assistants.
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) (★85 TypeScript) - A lightweight MCP server that provides natural terminal integration for command execution and REPL support in iTerm2.
- [heshengtao/comfyui_LLM_party](https://github.com/heshengtao/comfyui_LLM_party) (★1392 Python) - A comprehensive LLM agent framework built on ComfyUI that integrates MCP tools and various local and cloud LLM services.
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) (★119 TypeScript) - A VS Code extension and MCP server that enables Claude and other LLMs to interactively debug code.
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) (★93 JavaScript) - The Linear MCP Server integrates Linear's project management system with the Model Context Protocol to enable LLMs to interact with Linear issues.
- [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp) (★256 TypeScript) - FastMCP is a TypeScript framework for building Model Context Protocol (MCP) servers capable of handling client sessions.
- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) (★183 Python) - A shell and coding agent designed for integrating with Claude and ChatGPT on a desktop environment.
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) (★56 JavaScript) - An MCP server that enables persistent memory for Claude through a customizable local knowledge graph.
- [sigoden/llm-functions](https://github.com/sigoden/llm-functions) (★410 Shell) - A framework that enables the effortless creation of LLM tools and agents using plain Bash, JavaScript, and Python functions.
- [stripe/agent-toolkit](https://github.com/stripe/agent-toolkit) (★416 TypeScript) - The Stripe Agent Toolkit is a Python and TypeScript library that integrates the Stripe API with popular agent frameworks, including Model Context Protocol.
- [wong2/litemcp](https://github.com/wong2/litemcp) (★110 TypeScript) - LiteMCP is a TypeScript framework for building MCP servers elegantly.
- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) (★604 TypeScript) - Markdownify is an MCP server that converts various file types and web content into Markdown format.
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) (★82 TypeScript) - A desktop application that provides a simple web UI for managing MCP servers in the Claude app on MacOS.


#### MCP Clients

- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) (★70 HTML) - A cross-platform desktop chat application that leverages the Model Context Protocol to interface with various large language models.
- [BigSweetPotatoStudio/HyperChat](https://github.com/BigSweetPotatoStudio/HyperChat) (★133 JavaScript) - HyperChat is an open-minded chat client that integrates various LLM APIs and leverages the MCP protocol to enhance productivity.
- [Ejb503/multimodal-mcp-client](https://github.com/Ejb503/multimodal-mcp-client) (★116 TypeScript) - A multi-modal MCP client enabling voice-powered AI workflows with modern web technologies.
- [FlowArg/FlowUpdater](https://github.com/FlowArg/FlowUpdater) (★98 Java) - FlowUpdater is an open source solution for updating Minecraft with robust customization and MCP integration.
- [Hexeption/MCP-Reborn](https://github.com/Hexeption/MCP-Reborn) (★1135 ) - MCP-Reborn is a tool that facilitates the creation and modification of Minecraft modded clients using a reimagined Mod Coder Pack.
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) (★65 TypeScript) - A desktop GUI application for discovering, installing, and managing MCP servers.
- [ViaVersionMCP/ViaMCP](https://github.com/ViaVersionMCP/ViaMCP) (★58 Java) - A client-side implementation that integrates ViaVersion protocol switching into the Minecraft Coder Pack (MCP).
- [adhikasp/mcp-client-cli](https://github.com/adhikasp/mcp-client-cli) (★106 Python) - A simple command-line interface client for running LLM prompts and interacting with MCP servers.
- [daodao97/chatmcp](https://github.com/daodao97/chatmcp) (★700 Dart) - ChatMCP is a cross-platform AI chat client that integrates with the Model Context Protocol (MCP) to connect with various MCP servers.
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) (★610 Python) - mcp-agent is a lightweight, composable Python framework for building AI agents using the Model Context Protocol.
- [nanbingxyz/5ire](https://github.com/nanbingxyz/5ire) (★1021 TypeScript) - 5ire is a cross-platform desktop AI assistant and MCP client that connects to major AI service providers and supports local knowledge retrieval through an integrated MCP protocol.
- [punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) (★231 ) - A curated list of MCP clients.


#### MCP Proxies & Bridges

- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) (★282 Python) - MCP-Bridge is a middleware that connects the OpenAI API with MCP tools to facilitate seamless integration and communication.
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) (★54 Python) - mcp-proxy is a tool that bridges communication between MCP servers by converting between stdio and SSE protocols.



### MCP Directories & Collections

- [chatmcp/mcp-directory](https://github.com/chatmcp/mcp-directory) (★374 TypeScript) - A curated directory website that lists outstanding MCP Servers.
- [phase/MinecraftMappings](https://github.com/phase/MinecraftMappings) (★58 Kotlin) - A repository that offers transitive mappings for Minecraft versions from 1.7.10 through 1.15.2, enabling conversions between Spigot, MCP, Yarn, and Mojang formats.


### MCP Utilities & Tools

- [chkwon/PATHSolver.jl](https://github.com/chkwon/PATHSolver.jl) (★52 Julia) - PATHSolver.jl is a Julia wrapper for the PATH solver that enables solving mixed complementarity problems.
- [zortax/MinecraftInjectionAPI](https://github.com/zortax/MinecraftInjectionAPI) (★67 Java) - A lightweight API that uses MCP deobfuscation mappings to inject mods into Minecraft at runtime.



## Agent Frameworks & Orchestration


### Multi-Agent & Autonomous Frameworks



#### JavaScript/TypeScript Multi-Agent Frameworks

- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) (★8055 TypeScript) - Mastra is a TypeScript AI agent framework that enables rapid development of AI applications with support for workflows, agents, RAG, and easy integration with various LLM providers.







## MCP Integration with Development Tools






## Domain-Specific MCP Applications







## Multimodal & Specialized MCP Tools






## Cloud & Infrastructure MCP Solutions



### Self-Hosted & Local Deployments

- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) (★76 Python) - OpenDataMCP connects open data sources to LLMs via the Model Context Protocol using easy CLI-based setup and publishing tools.
- [dmayboroda/minima](https://github.com/dmayboroda/minima) (★535 Python) - Minima is an open source on-premises RAG solution with configurable containers for secure local document processing integrated with ChatGPT and MCP.




## Resources & Educational Materials


### Curated Lists & Collections

- [AlexMili/Awesome-MCP](https://github.com/AlexMili/Awesome-MCP) (★70 ) - A curated list of Model Context Protocol (MCP) resources including servers, SDKs, and tools.
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) (★3886 ) - A curated list of Model Context Protocol (MCP) servers for enhancing AI interactions.



### Benchmarks & Evaluations

- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) (★6709 Python) - Upsonic is a reliability-focused AI agent framework that leverages the Model Context Protocol (MCP) for production-ready multi-agent workflows.




## License

[<img src="http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)
