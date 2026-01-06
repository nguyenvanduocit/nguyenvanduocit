## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer: deep technical expertise in backend systems and AI tooling (Go, TypeScript), active exploration of AI agents and the Model Context Protocol ecosystem, and product sense from shipping developer tools and iterating based on real-world usage.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server that makes Jira AI-native. Born from watching teams waste time on repetitive ticket operations. Now AI assistants can handle issue management, sprint planning, and workflow transitions directly. 76 stars, 20 forks, real teams using it in production. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin that solves the isolation problem of local knowledge bases. Lets you seamlessly integrate web content into your notes without breaking your flow. 216+ stars from knowledge workers who needed this exact bridge between their notes and the web. (TypeScript)

**[InstantCode](https://github.com/nguyenvanduocit/instantCode)** — Browser extension that eliminates context-switching when debugging frontend code. Click any element, ask AI about it—no copy-paste, no tab-switching. Recently integrated GitHub Actions for AI-driven continuous improvements. 50 stars from developers solving real debugging problems. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor because existing tools had messy, overcomplicated interfaces. Built with real-time collaboration using Liveblocks and Yjs. Solving the DX problem: clean interface, fast editing, no clutter. Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). Actively integrating Claude for autonomous build fixes. (TypeScript)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for direct GitHub Copilot API access. For developers who want programmatic integration with Copilot in their own workflows without the editor middleman. Shipping continuous improvements to authentication flow and TypeScript ergonomics. (TypeScript)

**[autosocial-trends](https://github.com/nguyenvanduocit/autosocial-trends)** — Daily automated trend research pipeline running in production. Eliminates manual overhead by delivering fresh trend data autonomously. Solves the content creator's problem: staying current without burning research time. Runs daily without manual intervention.

**[fetch-kit](https://github.com/nguyenvanduocit/fetch-kit)** — Go toolkit for handling web content fetching with common patterns like retries, timeouts, and user-agent management. Solves the repetitive boilerplate when building scrapers and research tools. 9 stars from Go developers who needed battle-tested HTTP utilities. (Go)

### Current focus (Jan 2026)

**Autonomous AI maintenance in production**: mimaid demonstrates the pattern in practice—Claude autonomously resolves TypeScript build failures via GitHub Actions. The Dec 29 incident proved the concept: Cloudflare Pages build failed, Claude analyzed logs, identified unused variable, opened PR, and merged the fix without human intervention. Production infrastructure now maintains itself. Key insight: build failures, unused variables, and lint errors are safe for autonomous handling. Architectural decisions, API changes, and security patches still need human judgment. Exploring patterns around when AI acts autonomously vs. escalates.

**Defining human-AI collaboration boundaries**: Real production usage across mimaid and InstantCode reveals clear patterns: agents excel at repetitive maintenance (builds, dependencies, lint fixes), humans own product direction and architecture. The question shifted from "can AI help?" to "what should AI own outright?" Daily autonomous commits prove the model works. Current work: extracting reusable orchestration patterns that other teams can adopt.

**Real-time collaboration meets AI reliability**: mimaid combines seamless multi-user diagram editing (Liveblocks + Yjs) with autonomous build health. Users get two benefits: instant collaborative UX and zero maintenance downtime. Testing whether this "human-facing collaboration + AI maintenance layer" architecture generalizes to other developer tools. The pattern shows promise beyond diagram editors.

**Programmatic AI beyond IDE constraints**: copilot-sdk enables direct GitHub Copilot API access without editor lock-in. Use cases emerging: CLI tools with AI suggestions, backend services generating code programmatically, CI/CD pipelines running AI-powered reviews. Dec 29 updates improved auth flows and TypeScript ergonomics based on integration feedback. Goal: enable headless AI workflows, not just interactive sessions.

**Production-grade autonomous systems**: autosocial-trends runs daily trend research unattended. Jan 5 commits confirm consistency. Building reliable AI operations requires: robust error handling, active monitoring, graceful degradation, and clear escalation paths. Moving from demo scripts to infrastructure that operates while you sleep.

**MCP ecosystem in production**: jira-mcp (76 stars, 20 forks) shows real teams deploying AI-Jira integration. MCP transitioned from "interesting protocol" to "critical integration layer." Contributing Go-based implementations and operational patterns from running MCP servers at scale. Current focus: making MCP production-ready, not just technically possible.

### Technical depth

- **Backend & systems**: Go for MCP servers, CLIs, and backend services. TypeScript for developer tooling and browser extensions
- **AI tooling**: MCP protocol implementation, agent orchestration, AI-assisted development workflows, building bridges between AI capabilities and existing developer workflows
- **Real-time systems**: Collaborative editing with Liveblocks, Yjs, and WebSocket-based architectures
- **Type safety**: Prioritizing type-safe APIs across Go and TypeScript—type-safety as a design requirement, not an afterthought
- **Continuous delivery**: GitHub Actions workflows that ship improvements based on real usage and user feedback. Actively testing AI-driven CI/CD patterns in production.

### Product thinking

I build by identifying real workflow friction and shipping solutions:
- **jira-mcp**: seeing teams waste hours on repetitive ticket operations, gave AI assistants native Jira access
- **obsidian-open-gate**: watching knowledge workers manually context-switch between apps
- **mimaid**: frustrated with bloated diagram editors when all I needed was clean Mermaid editing with real-time collaboration
- **InstantCode**: debugging frontend code shouldn't require constant tab-switching
- **autosocial-trends**: manual trend research was blocking content creation, so I automated it
- **copilot-sdk**: developers wanted programmatic Copilot access without being tied to IDE extensions
- **fetch-kit**: tired of writing the same HTTP boilerplate for every scraper and research tool

Stars validate the problem exists. Daily commits and iteration prove the solution works. Production usage proves it's reliable.

### How I work

- **Ship early, iterate based on usage**: InstantCode integrated GitHub Actions after seeing user patterns. autosocial-trends runs daily because that's what real users needed. mimaid deploys continuously to Cloudflare Pages with AI-driven automated fixes.
- **Technical depth meets product sense**: Build MCP servers in Go for performance, but design APIs thinking about developer ergonomics. Type safety matters because it reduces user pain, not just because it's technically correct.
- **AI exploration with engineering discipline**: Testing MCP integrations, AI-assisted development workflows, and agent orchestration—but always with production reliability in mind. Not just talking about AI, actively using it to ship better code faster. mimaid's autonomous build fixes prove the pattern works.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Hireable**: Yes — open to interesting projects in developer tooling, AI infrastructure, or workflow automation

I care about building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, MCP integrations, or solving real product problems in this space, let's connect.

---
*Last updated: January 6, 2026 (automated via GitHub Actions)*
