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

**Validating AI-driven autonomous development in production**: mimaid and InstantCode both run GitHub Actions integrated with Claude—when builds fail, AI analyzes logs, generates fixes, opens PRs autonomously. Dec 29: mimaid fixed Cloudflare Pages TypeScript errors without human intervention. Pattern proven: AI handles routine maintenance (build failures, linting), humans focus on architecture. Exploring boundaries with Auto-Claude research—when should agents act vs. escalate? Building operational patterns for AI-maintained codebases.

**Agent orchestration evolving from demos to production workflows**: The question shifted from "can agents fix bugs?" to "how do teams coordinate human+AI work?" Recent exploration (Auto-Claude, multi-agent systems) targets practical orchestration: agents handle routine maintenance (dependency updates, build fixes, documentation), humans own product decisions and system design. Not automation theater—real production patterns for when AI acts autonomously vs. when it waits for approval.

**Real-time collaboration + autonomous operations as a product pattern**: mimaid validates the combo—Liveblocks/Yjs handles real-time diagram sync, Claude fixes build failures autonomously. Solves two user problems: teams stay in sync, uptime maintained without manual firefighting. This pattern (collaborative UX + autonomous maintenance) appears in production tools repeatedly. Testing if it scales beyond diagram editors to other developer tools.

**Opening programmatic AI access beyond IDE lock-in**: copilot-sdk (updated Dec 29) gives developers direct TypeScript SDK access to GitHub Copilot API. Use cases emerging: CLI tools with AI suggestions, backend services generating code, CI/CD with AI code review. Removes "must use VS Code" constraint. Latest improvements: auth flow reliability, TypeScript ergonomics based on real integration feedback. Enabling AI in server-side workflows, not just interactive editing.

**Production-grade automation infrastructure, not demos**: autosocial-trends runs daily (Dec 28-30 commits) delivering fresh trend data with zero manual intervention. Proves "set it and forget it" AI requires: robust error handling, monitoring, graceful degradation, anomaly alerts. Building patterns where autonomous agents run production workloads with clear escalation paths. Real-world validation beyond one-off scripts.

**MCP ecosystem reaching enterprise adoption**: jira-mcp (76 stars, 20 forks) seeing real teams integrate AI with Jira workflows in production. MCP matured from "interesting protocol" to "production integration layer." More servers shipping, tooling improving, context standardization patterns clarifying. Contributing production Go implementations and operational learnings. The ecosystem moved from exploration to deployment phase.

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
*Last updated: January 4, 2026 at 12:00 UTC*
