# Seth Hobson

## Software Engineer | Applied AI | Data Engineering | Founder @ [Major 7 Apps](https://major7apps.com/)

Hello! I'm Seth Hobson, a software engineer with more than 15 years of experience building data applications, services, and distributed systems, mostly in finance and AI. I now build tools for AI coding agents and financial products, and I write about the infrastructure that AI agents run on.

### 👤 About me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wshobson)
[![Personal Site](https://img.shields.io/badge/Personal_Site-1f2937?style=for-the-badge&logo=rss&logoColor=white)](https://sethhobson.com)
[![Major 7 Apps](https://img.shields.io/badge/Major_7_Apps-111827?style=for-the-badge&logoColor=white)](https://major7apps.com/)
[![Substack](https://img.shields.io/badge/Substack-FF6719?style=for-the-badge&logo=substack&logoColor=white)](https://swappingsymbols.substack.com/)

### 💼 Professional experience

- Senior Applied AI Engineer, United Data Technologies (2025 to present)
- Founder, Major 7 Apps LLC (2024 to present)
- Senior Software Engineer, Kuali Inc. (2021 to 2023)
- Senior Software Engineer, Apple Inc. (2015 to 2021)
- Software development and web technologies (2009 to 2015)

### 🛠️ Skills

- AI and LLMs
  - Applied AI engineering and forward deployed engineering
  - Building AI, ML, and LLM features into applications
  - Improving LLM results with RAG, agentic RAG, agentic search, supervised fine-tuning (SFT), and RAFT
  - Infrastructure for agents, including MCP servers and gateways, plugins and harnesses for coding agents, and evals
- Software engineering
  - Software architecture and design
  - Full-stack development in Python, JavaScript, TypeScript, SQL, Go, C, and Rust
  - APIs with REST, GraphQL, gRPC, MCP, and A2A
- Data and infrastructure
  - Database design for relational and NoSQL databases
  - Data pipelines, data analysis, and visualization
  - Cloud and distributed systems on Azure and AWS, managed with Terraform

### 🎓 Education

- Master of Music in Vocal Performance, Indiana University Bloomington
- Bachelor of Science in Computer Science, Appalachian State University
- Bachelor of Music in Vocal Performance, Appalachian State University

### 📦 Products

#### [Ambient Alpha](https://ambientalpha.com)

Live market data for the big screen. A native tvOS app that puts market moves, sector breadth, your watchlist, and upcoming economic releases on an Apple TV, readable at a glance from across the room.

#### [QueryPlan](https://queryplan.dev)

Learn SQL performance from real execution plans. Interactive exercises are graded by running your actual queries, and result correctness and plan efficiency both count.

The [query plan visualizer](https://queryplan.dev/tool) is free, and you don't need an account to use it.

### 🚀 Open source projects

#### [Agentic Plugin Marketplace](https://github.com/wshobson/agents) ![GitHub stars](https://img.shields.io/github/stars/wshobson/agents?style=social)

A plugin marketplace of agents, skills, and commands for Claude Code, Codex CLI, Cursor, and other AI coding tools.

You install only the plugins you need, and each plugin loads only its own files into the model's context. I built it for Claude Code, and the same Markdown source also works in OpenAI Codex CLI, Cursor, OpenCode, Antigravity CLI, GitHub Copilot, and Pi. Adapters generate the format each tool reads, and CI checks the generated files against the installed tools. [Project overview](https://sethhobson.com/projects/agents/)

#### [Maverick MCP](https://github.com/wshobson/maverick-mcp) ![GitHub stars](https://img.shields.io/github/stars/wshobson/maverick-mcp?style=social)

An MCP server for market data analysis, screening, and backtesting that works with any MCP client.

The server runs on your own machine, and its core tools for market data, technical analysis, stock screening, and portfolio tracking don't need an API key. Optional extras add strategy backtesting and research that uses an LLM. [Project overview](https://sethhobson.com/projects/maverick-mcp/)

#### [Pensyve](https://github.com/major7apps/pensyve) ![GitHub stars](https://img.shields.io/github/stars/major7apps/pensyve?style=social)

Offline-first memory runtime for AI agents with 8-signal retrieval, FSRS decay, and native MCP support.

Pensyve stores facts, conversations, observations, and action outcomes so an agent can retrieve them in later sessions, and you can use it from Python, an MCP server, a command-line tool, or a REST API. Pensyve is open source under the Apache 2.0 license. The hosted Pensyve Cloud service closed on October 1, 2026, and the project is now in maintenance mode, so releases cover only security fixes and dependency updates. [Project overview](https://sethhobson.com/projects/pensyve/)

#### [Tiingo MCP](https://github.com/major7apps/tiingo-mcp) ![GitHub stars](https://img.shields.io/github/stars/major7apps/tiingo-mcp?style=social)

A Rust MCP server for the Tiingo market data API.

I wrote it with [rmcp](https://docs.rs/rmcp/latest/rmcp/). Its tools cover stocks (EOD, IEX, and consolidated prices), funds, forex, crypto, news, fundamentals, and corporate actions, and it can also open short-lived real-time market data subscriptions. The server also includes resources, a resource template, and prompts. You can install it from [crates.io](https://crates.io/crates/tiingo-mcp/) or with a prebuilt installer. [Project overview](https://sethhobson.com/projects/tiingo-mcp/)

### 📰 Newsletter

I write [Swapping Symbols](https://swappingsymbols.substack.com/), a personal blog about what I’m building and learning, including practical findings in AI, software, and other subjects I want to explore.
