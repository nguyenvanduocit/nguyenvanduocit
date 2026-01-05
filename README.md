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

**AI-first CI/CD patterns in production**: mimaid validates the autonomous maintenance pattern—Claude handles TypeScript build failures via GitHub Actions without human intervention. The milestone wasn't "AI fixed a bug" but rather "production infrastructure maintains itself while humans focus on features." Pattern proven Dec 29: Claude analyzed Cloudflare Pages logs, identified unused variable, generated fix, opened PR, merged autonomously. Real operational learnings: build failures, unused variables, and linting errors are safe for autonomous fixes. Architectural decisions, API changes, and security patches need human review. Exploring Auto-Claude workflows to codify the handoff between autonomous operations and human escalation.

**Human-AI workflow orchestration**: The question evolved from "can AI fix bugs?" to "when should AI act autonomously vs. wait for approval?" mimaid and InstantCode provide production evidence: agents excel at repetitive maintenance (builds, deps, lint), humans own product direction and architecture. Daily commits validate the pattern works. Current exploration: extracting reusable orchestration patterns from these working systems. Real teams need operational playbooks, not just technical capabilities. Studying what makes AI teammates reliable in production.

**Real-time collaborative tooling with autonomous backend**: mimaid demonstrates a product pattern worth generalizing—users get seamless multi-user Mermaid editing (Liveblocks + Yjs) while Claude autonomously maintains build health. Frontend delivers collaborative UX, backend stays green without manual intervention. Users benefit twice: instant team sync + zero downtime from build issues. Testing whether this "human-facing collaboration layer + AI maintenance layer" architecture generalizes beyond diagram editors to other developer tools.

**Programmatic AI access beyond IDE lock-in**: copilot-sdk (TypeScript SDK for direct GitHub Copilot API access) removes the "must use VS Code extension" constraint. Real use cases emerging: CLI tools with inline AI suggestions, backend services generating code programmatically, CI/CD pipelines running AI-powered code review. Updated Dec 29 with auth flow improvements and better TypeScript ergonomics based on integration feedback. Enabling headless AI workflows, not just interactive editor sessions.

**Production-grade autonomous pipelines**: autosocial-trends proves "set it and forget it" AI is achievable—daily trend research runs unattended (Jan 5 commit confirms consistency). Key learnings: robust error handling, active monitoring, graceful degradation, and clear anomaly alerting separate demos from production-grade automation. Building repeatable patterns where agents handle production workloads with well-defined escalation paths. Moving from one-off scripts to reliable infrastructure that operates while you sleep.

**MCP ecosystem maturation**: jira-mcp (76 stars, 20 forks) shows real teams integrating AI with Jira in production. MCP graduated from "interesting protocol" to "critical integration layer." The ecosystem transitioned from exploration to deployment—people build businesses on this now. Contributing Go-based implementations and operational patterns from running MCP servers at scale. Focus shifting from "how does MCP work?" to "how do we operate MCP in production?"

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
*Last updated: January 5, 2026 (automated via GitHub Actions)*
