## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer combining three strengths:
- **Deep technical expertise** in backend systems and AI tooling (Go, TypeScript)
- **Active exploration** of AI agents, MCP, and AI-assisted workflows
- **Product development knowledge** from shipping developer tools and learning from user feedback

I spot workflow friction, build solutions, and iterate based on real usage. My projects solve problems teams face daily: eliminating context-switching during debugging, bridging knowledge bases with the web, giving AI native access to project management systems.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server giving AI assistants native Jira access. Born from watching teams burn hours on repetitive ticket operations. Now issue management, sprint planning, and workflow transitions happen through natural conversation with Claude. 76 stars, 20 forks, deployed in production teams solving real workflow bottlenecks. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin bridging local knowledge bases with the web. Knowledge workers were manually context-switching between notes and research—this integration eliminated that friction. 218 stars from users who needed exactly this workflow bridge. (TypeScript)

**[InstantCode](https://github.com/nguyenvanduocit/instantCode)** — Browser extension ending context-switching during frontend debugging. Click any element, ask AI about it—no copy-paste, no tab-juggling. Claude GitHub Actions integration enables autonomous improvements based on usage patterns. 50 stars from developers fixing real workflow pain. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor built from frustration with bloated alternatives. Clean interface meets real-time collaboration (Liveblocks + Yjs) plus AI-driven maintenance. Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). Claude autonomously maintains the codebase through GitHub Actions—recent example: caught and fixed TypeScript build errors blocking Cloudflare Pages deployment without human intervention. Production proof that AI can own routine maintenance while humans focus on features. (TypeScript)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for direct GitHub Copilot API access, breaking editor lock-in. Enables programmatic AI workflows: CLI tools with AI suggestions, backend services generating code, CI/CD pipelines with AI-powered reviews. Continuous iteration on auth flows and TypeScript ergonomics based on real integration feedback from developers building headless automation. (TypeScript)

**[autosocial-trends](https://github.com/nguyenvanduocit/autosocial-trends)** — Daily automated trend research pipeline running in production. Content creators need current data without burning research time—this delivers it daily without human intervention. Demonstrates reliable autonomous operations with robust error handling and monitoring. (Automated workflow)

**[fetch-kit](https://github.com/nguyenvanduocit/fetch-kit)** — Go toolkit for web content fetching with battle-tested patterns: retries, timeouts, user-agent management. Extracted from repeatedly building scrapers and research tools. 9 stars from Go developers needing HTTP utilities that just work. (Go)

**[goscrape](https://github.com/nguyenvanduocit/goscrape)** — Go-based web scraping tool for downloading entire websites for offline access. Recently updated (Jan 8, 2026) with improvements for reliability and modern web handling. Solves the problem of preserving web content for offline documentation, archival, or local development. (Go)

### Current focus (Jan 2026)

**Building Claude plugin ecosystem**: Actively developing `aiocean/claude-plugins` (latest work: Jan 10, 2026). The problem: MCP proves AI assistants need external integrations, but developers still rebuild common patterns—authentication, rate limiting, error handling—for each server. Building a plugin architecture that makes MCP integrations more modular, discoverable, and maintainable. Translating lessons from Clik's rapid iteration into reusable patterns. Goal: reduce time from "I need Claude to access X" to working integration from days to minutes.

**Shipping Clik**: Rapid iteration cycle with 11 releases in 2 days (v0.4.1 → v0.11.0, Jan 8-9, 2026), now stabilizing with continued refinements (latest: Jan 9). The problem: developers managing 5+ MCP servers across Claude Desktop, Cursor, Zed face fragmented config files and manual JSON editing. Clik provides unified server management—visual config, health monitoring, one-click installation. Each release driven by early adopter feedback on installation flows, server lifecycle management, and UX polish. This demonstrates product iteration at speed: ship → observe friction → fix → ship again. The work continues: recent updates focus on stability, edge cases, and polish based on real usage patterns. (aiocean/clik-releases)

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
- **Clik**: developers juggling 5+ MCP servers across multiple editors with manual JSON config → unified visual management interface
- **claude-plugins**: teams rebuilding auth/rate-limiting/error-handling for each MCP server → reusable plugin patterns
- **jira-mcp**: watched teams burn hours on repetitive ticket operations → gave AI native Jira access (76 stars, 20 forks)
- **obsidian-open-gate**: knowledge workers context-switching between apps → built the integration bridge (218 stars)
- **mimaid**: needed clean Mermaid editing with real-time collaboration → minimal editor with AI-maintained infrastructure (2 stars)
- **InstantCode**: debugging frontend with constant tab-switching → click-and-ask workflow (50 stars)
- **copilot-sdk**: developers wanting programmatic Copilot without editor lock-in → TypeScript SDK for headless workflows
- **autosocial-trends**: manual trend research blocking content creation → automated daily pipeline
- **goscrape**: repeatedly needing offline website copies → reliable scraping tool
- **fetch-kit**: writing HTTP boilerplate for every scraper → reusable Go toolkit (9 stars)

Stars validate the problem exists. Commits and iteration prove the solution works. Production usage proves it's reliable. Rapid iteration cycles (like Clik's 11 releases in 2 days) prove I listen to users.

### How I work

- **Ship early, iterate on feedback**: Clik shipped 11 releases in 2 days based on early adopter feedback. InstantCode added GitHub Actions after observing usage patterns. autosocial-trends runs daily because users need daily data. mimaid deploys continuously with AI fixing builds autonomously.
- **Technical depth with product sense**: Build Go MCP servers for performance, but design APIs for developer ergonomics. Type safety matters because it reduces pain, not just for technical correctness. Clik's visual interface solves the JSON config problem.
- **AI exploration with production discipline**: Testing MCP integrations, autonomous workflows, agent orchestration—always with reliability in mind. Not just talking about AI agents, actively deploying them. mimaid's autonomous build fixes and autosocial-trends' daily operations prove the model works in production.
- **Rapid iteration when it matters**: When building Clik, shipped multiple releases daily to fix friction points immediately. When building infrastructure (claude-plugins), slower, more deliberate approach to get architecture right. Match pace to problem type.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Open to**: Developer tooling, AI infrastructure, autonomous workflows, MCP integrations

Building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, production MCP deployments, Claude plugin ecosystems, or solving real product problems in this space, let's talk.

---
*Last updated: January 11, 2026 (automated via GitHub Actions)*
