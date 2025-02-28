# Awesome Model Context Protocol (MCP)

> **Note:** This repository contains an *automatically compiled* list of frameworks, tools, and resources related to the Model Context Protocol (MCP).

This curated list focuses on tools, implementations, and resources for the Model Context Protocol - an open protocol that enables seamless integration between LLM applications and external data sources and tools.

## What is Model Context Protocol (MCP)?

Model Context Protocol (MCP) is an open protocol developed by Anthropic that standardizes how AI applications connect with external data sources and tools. It enables:

- Sharing contextual information with language models
- Exposing tools and capabilities to AI systems
- Building composable integrations and workflows

- [Core MCP Frameworks & Implementations](#core-mcp-frameworks-&-implementations) 
    - [MCP Servers & Clients](#mcp-servers-&-clients) 
        - [MCP Servers](#mcp-servers) (22)

        - [MCP Clients](#mcp-clients) (12)

        - [MCP Proxies & Bridges](#mcp-proxies-&-bridges) (2)


    - [MCP Directories & Collections](#mcp-directories-&-collections) (2)

    - [MCP Utilities & Tools](#mcp-utilities-&-tools) (4)


- [Agent Frameworks & Orchestration](#agent-frameworks-&-orchestration) 
    - [Multi-Agent & Autonomous Frameworks](#multi-agent-&-autonomous-frameworks) 
        - [Python Multi-Agent Frameworks](#python-multi-agent-frameworks) (1)

        - [JavaScript/TypeScript Multi-Agent Frameworks](#javascript/typescript-multi-agent-frameworks) (1)






- [MCP Integration with Development Tools](#mcp-integration-with-development-tools) 

    - [Terminal & Shell Integrations](#terminal-&-shell-integrations) (1)



- [Domain-Specific MCP Applications](#domain-specific-mcp-applications) 





- [Multimodal & Specialized MCP Tools](#multimodal-&-specialized-mcp-tools) 




- [Cloud & Infrastructure MCP Solutions](#cloud-&-infrastructure-mcp-solutions) 

    - [Self-Hosted & Local Deployments](#self-hosted-&-local-deployments) (1)



- [Resources & Educational Materials](#resources-&-educational-materials) 
    - [Curated Lists & Collections](#curated-lists-&-collections) (2)


    - [Benchmarks & Evaluations](#benchmarks-&-evaluations) (1)





## Core MCP Frameworks & Implementations


### MCP Servers & Clients


#### MCP Servers

- [AgentDeskAI/browser-tools-mcp](https://github.com/AgentDeskAI/browser-tools-mcp) (★364 JavaScript) - A tool that monitors and processes browser logs using a Chrome extension and NodeJS middleware integrated with an MCP server.
- [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) (★68 TypeScript) - MemoryMesh is a TypeScript-based knowledge graph server that utilizes the Model Context Protocol (MCP) to provide structured memory persistence for AI models.
- [DMontgomery40/deepseek-mcp-server](https://github.com/DMontgomery40/deepseek-mcp-server) (★70 JavaScript) - A robust server that implements the Model Context Protocol for integrating DeepSeek's advanced language models with MCP-compatible applications.
- [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) (★303 TypeScript) - A specialized MCP server that provides streamlined Figma layout data to enhance AI coding workflows in Cursor.
- [JetBrains/mcp-jetbrains](https://github.com/JetBrains/mcp-jetbrains) (★106 JavaScript) - A model context protocol proxy server for JetBrains IDE integration and local deployment.
- [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) (★76 Python) - A Python-based project that connects open data with large language models using the Model Context Protocol.
- [QuantGeekDev/mcp-framework](https://github.com/QuantGeekDev/mcp-framework) (★202 TypeScript) - A TypeScript framework that provides an elegant and efficient solution for building Model Context Protocol (MCP) servers.
- [RafalWilinski/aws-mcp](https://github.com/RafalWilinski/aws-mcp) (★94 TypeScript) - This project provides an MCP server that enables natural language interaction with AWS via Claude.
- [RafalWilinski/mcp-apple-notes](https://github.com/RafalWilinski/mcp-apple-notes) (★124 TypeScript) - MCP Apple Notes is an MCP server that enables semantic search and retrieval augmented generation over your Apple Notes for seamless AI assistant integration.
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) (★899 ) - A curated list of production-ready and experimental Model Context Protocol servers that extend AI capabilities.
- [beclab/Olares](https://github.com/beclab/Olares) (★1871 Shell) - Olares is an open-source sovereign cloud OS that enables secure, self-hosted deployment of local AI models and applications through a Model Context Protocol-like integration.
- [cyanheads/atlas-mcp-server](https://github.com/cyanheads/atlas-mcp-server) (★88 TypeScript) - An adaptive Model Context Protocol server built in TypeScript that leverages Neo4j for intelligent project and task management while enabling seamless collaboration among LLM agents.
- [designcomputer/mysql_mcp_server](https://github.com/designcomputer/mysql_mcp_server) (★58 Python) - A Model Context Protocol server for secure interaction with MySQL databases enabling table listing, data reading, and SQL query execution.
- [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) (★85 TypeScript) - It is an MCP server that facilitates command execution and terminal interaction within iTerm sessions.
- [heshengtao/comfyui_LLM_party](https://github.com/heshengtao/comfyui_LLM_party) (★1392 Python) - A comprehensive LLM agent framework built on ComfyUI that integrates MCP tools and various local and cloud LLM services.
- [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) (★119 TypeScript) - This project enables interactive debugging via any LLM like Claude using the Model Context Protocol and a VS Code extension.
- [jerhadf/linear-mcp-server](https://github.com/jerhadf/linear-mcp-server) (★93 JavaScript) - A Model Context Protocol server that integrates Linear's issue tracking system with LLMs to streamline project management.
- [punkpeye/fastmcp](https://github.com/punkpeye/fastmcp) (★256 TypeScript) - A TypeScript framework for building Model Context Protocol (MCP) servers.
- [shaneholloman/mcp-knowledge-graph](https://github.com/shaneholloman/mcp-knowledge-graph) (★56 JavaScript) - An MCP server that enables persistent memory for Claude through a local knowledge graph.
- [wong2/litemcp](https://github.com/wong2/litemcp) (★110 TypeScript) - LiteMCP is a TypeScript framework that elegantly facilitates the development of MCP servers.
- [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) (★604 TypeScript) - Markdownify is an MCP server that converts various file types and web content into Markdown format.
- [zueai/mcp-manager](https://github.com/zueai/mcp-manager) (★82 TypeScript) - A desktop application that provides an intuitive web UI for managing Model Context Protocol (MCP) servers for the Claude Desktop app on MacOS.


#### MCP Clients

- [AI-QL/chat-mcp](https://github.com/AI-QL/chat-mcp) (★70 HTML) - A cross-platform desktop chat application that leverages the Model Context Protocol (MCP) to interface with various large language models.
- [BigSweetPotatoStudio/HyperChat](https://github.com/BigSweetPotatoStudio/HyperChat) (★133 JavaScript) - HyperChat is an open-minded chat client that integrates various LLM APIs and productivity tools through the MCP protocol.
- [Ejb503/multimodal-mcp-client](https://github.com/Ejb503/multimodal-mcp-client) (★116 TypeScript) - A multi-modal MCP client that empowers voice-controlled AI workflows leveraging Google Gemini and Anthropic MCP.
- [Hexeption/MCP-Reborn](https://github.com/Hexeption/MCP-Reborn) (★1135 ) - MCP-Reborn is a tool that facilitates the creation and modification of Minecraft modded clients using a reimagined Mod Coder Pack.
- [Jeamee/MCPHub-Desktop](https://github.com/Jeamee/MCPHub-Desktop) (★65 TypeScript) - A desktop application that enables users to discover, install, and manage MCP servers without requiring command-line expertise.
- [OxideWaveLength/Minecraft-Hack-BaseClient](https://github.com/OxideWaveLength/Minecraft-Hack-BaseClient) (★319 Java) - A base Minecraft hacked client for version 1.8.8 built using the Minecraft Coders Pack with multiple mod features.
- [ViaVersionMCP/ViaMCP](https://github.com/ViaVersionMCP/ViaMCP) (★58 Java) - ViaMCP is a client-side implementation for the Minecraft Coder Pack that enables protocol version switching and integration fixes.
- [adhikasp/mcp-client-cli](https://github.com/adhikasp/mcp-client-cli) (★106 Python) - A simple CLI tool for running LLM prompts and implementing an MCP client.
- [daodao97/chatmcp](https://github.com/daodao97/chatmcp) (★700 Dart) - ChatMCP is a cross-platform AI chat client that integrates with the Model Context Protocol (MCP) to connect with various MCP servers.
- [lastmile-ai/mcp-agent](https://github.com/lastmile-ai/mcp-agent) (★610 Python) - mcp-agent is a lightweight, composable Python framework for building AI agents using the Model Context Protocol.
- [nanbingxyz/5ire](https://github.com/nanbingxyz/5ire) (★1020 TypeScript) - 5ire is a cross-platform desktop AI assistant and MCP client that connects to major AI service providers and supports local knowledge retrieval through an integrated MCP protocol.
- [punkpeye/awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) (★231 ) - A curated list of Model Context Protocol (MCP) clients that enable secure and standardized AI model interactions with various resources.


#### MCP Proxies & Bridges

- [SecretiveShell/MCP-Bridge](https://github.com/SecretiveShell/MCP-Bridge) (★281 Python) - MCP-Bridge is a middleware service that provides an OpenAI-compatible endpoint to interact with MCP tools.
- [sparfenyuk/mcp-proxy](https://github.com/sparfenyuk/mcp-proxy) (★54 Python) - mcp-proxy is a proxy tool that bridges MCP servers using SSE transport and stdio interfaces to facilitate flexible communication between clients and servers.



### MCP Directories & Collections

- [chatmcp/mcp-directory](https://github.com/chatmcp/mcp-directory) (★374 TypeScript) - A directory listing of awesome MCP servers with a live preview and community links.
- [phase/MinecraftMappings](https://github.com/phase/MinecraftMappings) (★58 Kotlin) - A tool that creates transitive mappings converting between different Minecraft version naming schemes such as Spigot, MCP, Yarn, and Mojang.


### MCP Utilities & Tools

- [FlowArg/FlowUpdater](https://github.com/FlowArg/FlowUpdater) (★98 Java) - FlowUpdater is an open source Java solution for updating Minecraft, featuring support for Vanilla, Forge, Fabric, and MCP configurations.
- [chkwon/PATHSolver.jl](https://github.com/chkwon/PATHSolver.jl) (★52 Julia) - PATHSolver.jl is a Julia package that wraps the PATH Solver to solve mixed complementarity problems.
- [sigoden/llm-functions](https://github.com/sigoden/llm-functions) (★410 Shell) - A lightweight framework for creating LLM tools and agents using Bash, JavaScript, and Python functions.
- [zortax/MinecraftInjectionAPI](https://github.com/zortax/MinecraftInjectionAPI) (★67 Java) - A simple API using MCP deobfuscation mappings to inject mods at runtime for Minecraft.



## Agent Frameworks & Orchestration


### Multi-Agent & Autonomous Frameworks


#### Python Multi-Agent Frameworks

- [stripe/agent-toolkit](https://github.com/stripe/agent-toolkit) (★416 TypeScript) - A Python and TypeScript library that integrates the Stripe API into agent workflows with seamless support for MCP and popular agent frameworks.


#### JavaScript/TypeScript Multi-Agent Frameworks

- [mastra-ai/mastra](https://github.com/mastra-ai/mastra) (★8055 TypeScript) - Mastra is a TypeScript AI agent framework that enables rapid development of AI applications with support for workflows, agents, RAG, and easy integration with various LLM providers.







## MCP Integration with Development Tools



### Terminal & Shell Integrations

- [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw) (★183 Python) - wcgw is a shell and coding agent designed for Claude and ChatGPT that enables autonomous command execution and intelligent code editing on local machines.




## Domain-Specific MCP Applications







## Multimodal & Specialized MCP Tools






## Cloud & Infrastructure MCP Solutions



### Self-Hosted & Local Deployments

- [dmayboroda/minima](https://github.com/dmayboroda/minima) (★535 Python) - Minima is an open source on-premises RAG solution with configurable containers for secure local document processing integrated with ChatGPT and MCP.




## Resources & Educational Materials


### Curated Lists & Collections

- [AlexMili/Awesome-MCP](https://github.com/AlexMili/Awesome-MCP) (★70 ) - A curated list of Model Context Protocol (MCP) resources including servers, SDKs, and tools.
- [punkpeye/awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) (★3885 ) - A curated list of Model Context Protocol (MCP) servers for enhancing AI interactions.



### Benchmarks & Evaluations

- [Upsonic/Upsonic](https://github.com/Upsonic/Upsonic) (★6707 Python) - Upsonic is a reliability-focused AI agent framework that leverages the Model Context Protocol (MCP) for production-ready multi-agent workflows.




## License

[<img src="http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)
