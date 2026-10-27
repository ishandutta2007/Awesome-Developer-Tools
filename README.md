# Awesome-Developer-Tools

# Awesome-Developer-Tools

**Top Developer Tools (Opensource) 🌟 Star if you like it! 🌟**



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on API Development, Low-Code Platforms, Code Editors, API Documentation & AI Coding Agents*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Developer Tools**. These tools enable developers to build, test, document, and ship software—from fully managed enterprise platforms with AI-powered coding agents to self-hosted editors, API clients, and low-code builders that give teams complete control over their development workflow.



**Examples** include Postman, GitHub Enterprise, GitLab, OutSystems, Mendix, Retool, Visual Studio Code, JetBrains, SwaggerHub, and Workday Extend (the category leaders in commercial space).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, API development, low-code platforms, and open developer infrastructure—ideal for developers and organizations seeking transparent, vendor-independent tooling.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Postman](https://www.postman.com/)**

  **API development and testing platform** with collections, environments, mock servers, and monitoring. **Pricing**: Free tier available; paid plans per user. **Free tier**: Yes, with limited collection runs and mock calls. **Best for**: teams wanting a polished, collaborative API client with broad protocol support and cloud sync.



- **[GitHub Enterprise](https://github.com/enterprise)**

  **Enterprise software development platform** with repository hosting, CI/CD (Actions), code review, and security scanning. **Pricing**: Per-user licensing; quote-based for enterprise. **Free tier**: None for Enterprise; GitHub Free available for individuals. **Best for**: organizations wanting an integrated DevOps platform with the largest open-source ecosystem.



- **[GitLab](https://about.gitlab.com/)**

  **DevOps platform** with source control, CI/CD, security, and project management in one application. **Pricing**: Free tier available; **Premium** at $29/user/month; **Ultimate** at $99/user/month (annual billing). **Free tier**: Yes, with 5 GB storage and 400 CI/CD minutes. **Best for**: teams wanting a single DevOps application with strong built-in CI/CD and security scanning.



- **[OutSystems Developer Studio](https://www.outsystems.com/)**

  **Enterprise low-code platform** for building web and mobile apps. **Pricing**: Quote-only; per-user and per-environment models. **Free tier**: Free personal environment with limitations. **Best for**: enterprises wanting a governed low-code platform for large-scale application portfolios.



- **[Mendix Studio Pro](https://www.mendix.com/)**

  **Low-code application development platform** with visual modeling and deployment options. **Pricing**: Free tier for individuals; paid plans per user and per app. **Free tier**: Yes, for personal use with limited resources. **Best for**: teams wanting collaborative low-code development with strong enterprise governance features.



- **[Retool](https://retool.com/)**

  **Low-code platform for building internal tools** with pre-built components and data source connectors. **Pricing**: Free tier available; **Team** at $10/user/month; **Business** at $50/user/month; **Enterprise** quote-only. **Free tier**: Yes, with limited users and apps. **Best for**: teams wanting to rapidly build internal admin panels and dashboards on top of existing data sources.



- **[Visual Studio Code](https://code.visualstudio.com/)**

  **Free, open-source code editor** with extensive extension ecosystem and AI features. **Pricing**: Free. **Free tier**: Full editor is free. **Best for**: developers wanting a lightweight, extensible editor with broad language support and integrated AI assistance.



- **[JetBrains](https://www.jetbrains.com/)**

  **Integrated development environments** (IntelliJ IDEA, PyCharm, WebStorm, etc.) with deep language intelligence. **Pricing**: Individual subscriptions from ~$8–$25/month depending on IDE; **All Products Pack** at $28.90/month (annual). **Free tier**: Free community editions for some IDEs (IntelliJ IDEA Community, PyCharm Community). **Best for**: developers wanting powerful, language-specific IDEs with advanced refactoring and debugging.



- **[SwaggerHub](https://swagger.io/tools/swaggerhub/)**

  **API design and documentation platform** built on OpenAPI Specification. **Pricing**: Free tier available; paid plans per user. **Free tier**: Yes, with limited API definitions and projects. **Best for**: teams wanting collaborative API design with hosted documentation and mock servers.



- **[Workday Extend](https://www.workday.com/)**

  **Low-code application development platform** for extending Workday. **Pricing**: Quote-only; bundled with Workday suite. **Free tier**: None. **Best for**: Workday customers wanting to build custom apps and workflows on the Workday platform.



## Open-Source GitHub Projects



- **[Hoppscotch](https://github.com/hoppscotch/hoppscotch)**

  **Open-source API development ecosystem** (MIT) — **the most widely adopted open-source Postman alternative** with a web-based, offline-first interface. **Features**: REST, GraphQL, WebSocket, SSE, and MQTT support; collections, environments, and request history; team collaboration (self-hosted); and a polished UI comparable to Postman . **Tech stack**: Vue.js, TypeScript. **Deploy**: Self-hosted (Docker) or use the hosted web app. **Best for**: developers wanting a familiar Postman-like experience with full self-hosting and no account requirement.



- **[Bruno](https://github.com/usebruno/bruno)**

  **Open-source IDE for exploring and testing APIs** (MIT) — **the leading local-first, git-friendly API client** with growing adoption. **Features**: Collections stored as plain files on disk (git-versionable); support for REST, GraphQL, and gRPC; environments and variables; test scripts; and no cloud sync or account required. **Tech stack**: Electron, React. **Deploy**: Desktop application (Windows, macOS, Linux). **Best for**: developers wanting a fast, offline API client where collections live in the repository alongside code.



- **[Resonance](https://github.com/letsfork/resonance)**

  **Local-first, zero-account open-source API client** (license per repo) — **a lightweight Rust/Tauri alternative to Postman and Insomnia**. **Features**: REST, GraphQL (including subscriptions), gRPC (with server reflection), WebSocket, SSE, and MQTT in one client; **~15 MB bundle size**; secrets stored in OS keychain; OpenAPI and Postman import; mock server; and collection runner . **Tech stack**: Tauri, Rust. **Deploy**: Desktop application. **Best for**: developers wanting an ultra-lightweight, privacy-focused API client with multi-protocol support and no cloud dependency.



- **[Windmill](https://github.com/windmill-labs/windmill)**

  **Open-source developer platform to turn scripts into workflows and UIs** (AGPL-3.0 for core) — **a fast-growing alternative to Retool and Airplane**. **Features**: Scripts in Python, TypeScript, Go, Bash, SQL, and more; auto-generated UIs from scripts; workflows and schedules; approval flows; and a **workflow engine 13x faster than Airflow** according to the project . **Tech stack**: Rust, Svelte, PostgreSQL. **Deploy**: Self-hosted (Docker, Kubernetes) or Windmill Cloud. **Best for**: developers wanting to build internal tools and workflows from existing scripts without rewriting them as low-code apps.



- **[Lowcoder](https://github.com/lowcoder-org/lowcoder)**

  **Open-source low-code platform for internal and customer-facing apps** (AGPL-3.0) — **a direct Retool/Appsmith alternative** with a focus on external apps. **Features**: Visual UI builder with 120+ components; native connections to PostgreSQL, MongoDB, MySQL, Redis, Elasticsearch, REST API, and more; JavaScript support throughout; RBAC; self-hosting; and **native embedding in websites** (no iFrame) . **Tech stack**: TypeScript, React, Node.js. **Deploy**: Self-hosted (Docker) or Lowcoder Cloud (free community tier). **Best for**: developers wanting a full-featured Retool alternative that can build both internal and external applications.



- **[Sourcey](https://github.com/sourcey/sourcey)**

  **Open-source documentation platform for APIs** (AGPL-3.0) — **a self-hosted alternative to SwaggerHub and Redocly**. **Features**: OpenAPI 2.0–3.2 support with auto-generated code samples in 10 languages; **native MCP server documentation**; Doxygen and godoc support; Markdown guides; **llms.txt generation** for AI agents; static HTML output; and no account required . **Tech stack**: TypeScript, Vite. **Deploy**: Static HTML (deploy anywhere) or dev server. **Best for**: teams wanting complete ownership of their API documentation with modern features like MCP and llms.txt support.



- **[Aider](https://github.com/Aider-AI/aider)**

  **Terminal-based AI pair programming tool** (Apache 2.0) — **the most established open-source AI coding agent** with ~49,600 GitHub stars . **Features**: Maps your codebase and edits it using cloud or local LLMs; automatic Git commits after each change; works in any terminal environment with no IDE dependency; and supports multiple model providers . **Tech stack**: Python. **Deploy**: CLI (`pip install aider-chat`). **Best for**: terminal-focused developers wanting AI-assisted coding with transparent, Git-versioned changes and no vendor lock-in.



- **[Cline](https://github.com/cline/cline)**

  **Open-source AI coding agent for VS Code** (Apache 2.0) — **the most widely installed VS Code AI agent** with 5.37 million marketplace installs . **Features**: Conservative default with confirmation required before every action; fully auditable source code; support for regulated cloud environments like AWS Bedrock; and broad provider support including Azure and GCP Vertex . **Tech stack**: TypeScript. **Deploy**: VS Code extension. **Best for**: teams with high compliance requirements wanting an AI coding agent with human-in-the-loop approval and full source visibility.



### Additional Strong Open-Source Options



- **Restfox** — Offline-first web HTTP client (MIT). Lightweight Postman alternative for browser and desktop. **Best for**: developers wanting a simple, offline API client without installation .

- **HTTPie** — Human-friendly HTTP client (BSD-3-Clause). CLI and desktop app for testing APIs. **Best for**: developers wanting a readable, scriptable HTTP client for the terminal or desktop .

- **Yaade** — Self-hosted collaborative API development environment (Apache 2.0). **Best for**: teams wanting a shared, self-hosted API workspace .

- **API Dash** — Beautiful cross-platform API client built with Flutter (Apache 2.0). **Best for**: developers wanting an AI-powered, lightweight Postman alternative .

- **Goose** — Extensible open-source AI agent in Rust (Apache 2.0) with desktop, CLI, and API. ~55,400 stars. **Best for**: developers wanting a model-agnostic AI agent with MCP extensibility .

- **Tabby** — Self-hosted, on-premises AI coding assistant (Apache 2.0). Open-source alternative to GitHub Copilot. **Best for**: organizations wanting a private AI coding assistant without cloud dependencies .



**Frameworks for building custom systems**: Combine **Hoppscotch** or **Bruno** for API development with **Sourcey** for documentation, **Windmill** or **Lowcoder** for internal tools and low-code apps, and **Aider** or **Cline** for AI-assisted coding—creating a comprehensive developer tooling stack matched to each team's workflow and compliance requirements.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Developer tools handling source code and API data must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls for proprietary code.

- **The "SaaS platform vs. self-hosted tool vs. AI agent" distinction matters.** **Postman, GitHub Enterprise, GitLab, OutSystems, Mendix, Retool, SwaggerHub, and Workday Extend** are commercial platforms. **Hoppscotch, Bruno, Resonance, and Sourcey** are self-hosted API tools. **Windmill and Lowcoder** are low-code platforms. **Aider, Cline, Goose, and Tabby** are AI coding agents. **Choose based on whether you need a managed service, a self-hosted tool, or an AI assistant.**

- **Hoppscotch is the most mature open-source Postman alternative** with a polished web UI and broad protocol support . **Bruno and Resonance** take a different approach—local-first, git-friendly, and lightweight—which appeals to developers who want collections versioned alongside code.

- **Sourcey is the strongest open-source SwaggerHub alternative** with native MCP documentation, llms.txt generation, and static HTML output . **The trade-off**: it is newer and has a smaller community than SwaggerHub or Redocly.

- **Windmill and Lowcoder are the leading open-source Retool alternatives.** Windmill excels at turning existing scripts into workflows and UIs with a very fast engine . Lowcoder offers a full visual builder with external app support and native website embedding . **Choose Windmill for script-first workflows; choose Lowcoder for visual app building.**

- **AI coding agents (Aider, Cline, Goose) are evolving rapidly.** **Aider** is the most established with transparent Git commits; **Cline** leads in VS Code installs with conservative approval workflows; **Goose** is a fast-growing Rust-based agent with MCP extensibility . **None are mature replacements for human developers**—treat them as accelerators with mandatory verification.

- **Pricing transparency varies.** VS Code is free; GitLab publishes tiers; JetBrains publishes subscription pricing. Postman, OutSystems, Mendix, Retool (Enterprise), SwaggerHub (Enterprise), and Workday Extend require sales contact for full quotes. **Validate with direct vendor conversations against your team size and usage needs.**

- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Source code and API credentials are sensitive**—ensure your hosting meets your organization's security requirements before deploying.



---



**Made for developers, platform teams, and organizations building transparent developer tooling solutions.**

Let's make Developer Tools more open, data-driven, and developer-friendly.
