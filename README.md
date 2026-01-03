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

**AI-driven CI/CD patterns proven at scale**: mimaid autonomously fixed Cloudflare Pages TypeScript build failures (Dec 29) through full GitHub Actions workflow—Claude analyzed error logs, generated fix, opened PR, merged without human intervention. This validates the pattern: AI agents handling routine build failures while humans focus on architecture decisions. Now scaling this approach: which categories of failures are safe for autonomous fixes vs. requiring human review? Building production patterns for AI-first CI/CD that reduce toil without compromising safety.

**Real-time collaborative tooling in production**: mimaid ships live diagram editing with Liveblocks + Yjs. Solves the coordination problem where diagram updates get lost in Slack threads or stale Notion docs. Real-time sync plus AI-driven error recovery means teams maintain current architecture diagrams without manual overhead. InstantCode (Dec 28) integrated GitHub Actions for continuous improvement based on real usage patterns—tools that evolve with their users.

**Programmatic AI workflows without IDE lock-in**: copilot-sdk (Dec 29 updates) provides direct TypeScript SDK for GitHub Copilot API. Removes the "must use VS Code/JetBrains" constraint. Enables: custom CLI tools with Copilot suggestions, backend services using Copilot for code generation, CI/CD pipelines with AI-assisted code review. Latest work improved authentication flow and TypeScript ergonomics. Opening AI assistance to server-side workflows, not just interactive editing.

**Production automation infrastructure**: autosocial-trends ran daily without intervention (Dec 28-30), delivering fresh trend research autonomously. This isn't a demo—it's production infrastructure eliminating manual research tasks. Key learning: reliable automation needs robust error handling and monitoring, not just "cron job + script." Building patterns for autonomous agents that degrade gracefully and alert on anomalies.

**MCP ecosystem maturation**: jira-mcp reached 76 stars, 20 forks—real teams integrating AI with enterprise workflows. Watching MCP evolve from "interesting protocol" to "production integration layer." The ecosystem is maturing: more MCP servers launching, better tooling emerging, clearer patterns for context standardization. Contributing to this shift by building production-grade Go implementations and sharing learnings.

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
*Last updated: January 3, 2026*
