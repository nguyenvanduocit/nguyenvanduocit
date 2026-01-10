## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer combining three strengths: deep technical expertise in backend systems and AI tooling (Go, TypeScript), active exploration of AI agents and MCP ecosystems, and product thinking from shipping developer tools people actually adopt.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server giving AI assistants native Jira access. Born from watching teams burn hours on repetitive ticket operations. Now issue management, sprint planning, and workflow transitions happen through natural conversation with Claude. 76 stars, 20 forks, deployed in production teams solving real workflow bottlenecks. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin bridging local knowledge bases with the web. Knowledge workers were manually context-switching between notes and research—this integration eliminated that friction. 218 stars from users who needed exactly this workflow bridge. (TypeScript)

**[InstantCode](https://github.com/nguyenvanduocit/instantCode)** — Browser extension ending context-switching during frontend debugging. Click any element, ask AI about it—no copy-paste, no tab-juggling. Claude GitHub Actions integration enables autonomous improvements based on usage patterns. 50 stars from developers fixing real workflow pain. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor built from frustration with bloated alternatives. Clean interface meets real-time collaboration (Liveblocks + Yjs) plus AI-driven maintenance. Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). Claude autonomously maintains the codebase through GitHub Actions—recent example: caught and fixed TypeScript build errors blocking Cloudflare Pages deployment without human intervention. Production proof that AI can own routine maintenance while humans focus on features. (TypeScript)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for direct GitHub Copilot API access, breaking editor lock-in. Enables programmatic AI workflows: CLI tools with AI suggestions, backend services generating code, CI/CD pipelines with AI-powered reviews. Continuous iteration on auth flows and TypeScript ergonomics based on real integration feedback from developers building headless automation. (TypeScript)

**[autosocial-trends](https://github.com/nguyenvanduocit/autosocial-trends)** — Daily automated trend research pipeline running in production. Content creators need current data without burning research time—this delivers it daily without human intervention. Demonstrates reliable autonomous operations with robust error handling and monitoring. (Automated workflow)

**[fetch-kit](https://github.com/nguyenvanduocit/fetch-kit)** — Go toolkit for web content fetching with battle-tested patterns: retries, timeouts, user-agent management. Extracted from repeatedly building scrapers and research tools. 9 stars from Go developers needing HTTP utilities that just work. (Go)

### Current focus (Jan 2026)

**Building Claude plugin ecosystem**: Deep in `aiocean/claude-plugins` (Jan 10, 2026)—exploring how to extend Claude's capabilities through composable plugins. The MCP protocol proves AI assistants need external integrations; now investigating how plugin architectures can make those integrations more modular, discoverable, and maintainable. Early-stage work translating lessons from Clik's MCP server management into reusable plugin patterns.

**Shipping Clik**: Rapidly iterated through 11 releases in 2 days (v0.4.1 → v0.11.0, Jan 8-9, 2026). Problem: developers juggle multiple MCP servers across Claude Desktop, Cursor, Zed—each with separate config files and manual JSON editing. Clik centralizes server management in one native macOS interface with visual config, health monitoring, and one-click installation. Multiple daily releases driven by early adopter feedback on installation flows, server lifecycle management, and UX polish. This rapid iteration demonstrates tight feedback loops: ship → observe usage → fix friction → ship again. Building in public, learning what developers actually need when managing 5+ MCP servers daily. (aiocean/clik-releases)

**AI autonomy in production infrastructure**: Production systems now maintain themselves through Claude GitHub Actions. mimaid and InstantCode prove the pattern: build failures trigger Claude, it analyzes logs, fixes errors, opens PRs, merges autonomously. Recent example: TypeScript unused variable broke Cloudflare Pages deployment—Claude caught it, fixed it, shipped it. Zero human intervention. Key insight: build failures, unused variables, lint errors, dependency updates are safe for full autonomy. Architectural decisions, API changes, security patches still need human review. Current work: refining boundaries between autonomous execution and human escalation.

**Extracting patterns from real usage**: Early 2026 activity shows clear boundaries emerging—AI excels at repetitive maintenance (builds, dependencies, lint), humans own product direction. The question shifted from "can AI help?" to "what should AI own completely?" Autonomous daily commits in mimaid and autosocial-trends prove it works. Current work: packaging these orchestration patterns so other teams can deploy autonomous AI maintenance without rebuilding infrastructure.

**Real-time collaboration with zero-maintenance infrastructure**: mimaid combines seamless multi-user editing (Liveblocks + Yjs) with AI-driven build health. Users get instant collaborative DX and zero downtime from broken builds. Testing if this "human-facing collaboration + AI maintenance layer" architecture scales to other developer tools beyond diagram editors.

**Programmatic AI workflows**: copilot-sdk unlocks GitHub Copilot API access without editor lock-in. Emerging use cases: CLI tools with AI suggestions, backend services generating code, CI/CD pipelines with AI reviews. Continuous iteration on auth flows and TypeScript ergonomics based on real integration feedback. Goal: enable headless AI automation, not just interactive coding sessions. Exploring integration patterns between Copilot and MCP for richer context.

**Daily autonomous operations**: autosocial-trends runs unattended trend research daily with consistent results. Building reliable AI operations means robust error handling, active monitoring, graceful degradation, clear escalation paths. Moving from demo scripts to infrastructure that operates overnight without human babysitting.

**MCP in production teams**: jira-mcp (76 stars, 20 forks) proves real teams deploy AI-Jira integration. MCP shifted from "interesting protocol" to "critical integration layer." Contributing Go implementations and operational learnings from running MCP servers at scale. Early 2026 activity shows continued interest in AI-assisted project management. Focus: making MCP production-ready, not just technically possible.

**Exploring agent orchestration and multi-agent systems**: Watching projects like claude-reflect (AI self-reflection patterns) and Auto-Claude (autonomous workflows) to understand emerging patterns in agent coordination. Current tooling focuses on single-agent workflows; multi-agent orchestration is the next frontier for complex tasks requiring different specializations. The rapid Clik iteration cycle demonstrates how fast feedback loops enable better product decisions—applying these lessons to agent orchestration where multiple specialized agents need to coordinate without human bottlenecks.

### Technical depth

- **Backend & systems**: Go for MCP servers, CLIs, backend services. TypeScript for developer tooling and browser extensions
- **AI tooling**: MCP protocol implementation, agent orchestration, autonomous workflows, building bridges between AI capabilities and existing systems
- **Real-time systems**: Collaborative editing with Liveblocks, Yjs, WebSocket architectures
- **Type safety**: Type-safe APIs across Go and TypeScript—a design requirement, not an afterthought
- **Continuous delivery**: GitHub Actions workflows shipping improvements based on usage patterns. Testing AI-driven CI/CD in production

### Product thinking

I build by spotting workflow friction and shipping fixes:
- **jira-mcp**: watched teams burn hours on repetitive ticket operations, gave AI native Jira access
- **obsidian-open-gate**: saw knowledge workers context-switching between apps, built the bridge
- **mimaid**: needed clean Mermaid editing with real-time collaboration, existing tools were bloated
- **InstantCode**: debugging frontend shouldn't mean constant tab-switching
- **autosocial-trends**: manual trend research blocked content creation, automated it
- **copilot-sdk**: developers wanted programmatic Copilot without IDE lock-in
- **fetch-kit**: wrote HTTP boilerplate too many times for scrapers and research tools

Stars validate the problem exists. Commits and iteration prove the solution works. Production usage proves it's reliable.

### How I work

- **Ship early, iterate on feedback**: InstantCode added GitHub Actions after observing usage patterns. autosocial-trends runs daily because users need daily data. mimaid deploys continuously with AI fixing builds autonomously.
- **Technical depth with product sense**: Build Go MCP servers for performance, but design APIs for developer ergonomics. Type safety matters because it reduces pain, not just for technical correctness.
- **AI exploration with production discipline**: Testing MCP integrations, autonomous workflows, agent orchestration—always with reliability in mind. Not just talking about AI agents, actively deploying them. mimaid's autonomous build fixes prove the model works in production.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Open to**: Developer tooling, AI infrastructure, autonomous workflows, MCP integrations

Building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, production MCP deployments, or solving real product problems in this space, let's talk.

---
*Last updated: January 10, 2026 (automated via GitHub Actions)*
