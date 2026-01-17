## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer with deep technical expertise in backend systems and AI tooling, active exploration of AI agents and workflows, plus product sense from shipping developer tools and learning from real usage.

I spot workflow friction, build solutions, and iterate based on feedback. My projects solve real developer problems—eliminating context-switching, bridging AI with existing systems, and making workflows smoother. I ship, gather feedback, and refine.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server giving AI assistants native Jira access. The problem: teams burning hours on repetitive ticket operations—status updates, sprint planning, bulk changes. Solution: issue management and workflow transitions through natural conversation with Claude. 79 stars, 19 forks show real teams deploying this in production. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin bridging local knowledge bases with the web. The problem: knowledge workers constantly context-switching between notes and research. Solution: seamless web integration that brings external data directly into your vault. 218 stars from users who needed exactly this workflow bridge. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor. The problem: existing Mermaid editors are bloated with features most users never touch. Solution: clean interface focused on editing + real-time collaboration (Liveblocks + Yjs). Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). AI agents autonomously maintain the codebase—fixing builds, updating deps. Production proof that AI can own routine maintenance while humans focus on product. (TypeScript)

**[claude-statusline](https://github.com/nguyenvanduocit/claude-statusline)** — Custom statusline for Claude Code with cost tracking and burn rate visibility. The problem: Claude Code users burning through API budgets blindly—no visibility into costs or session efficiency. Solution: shell-based statusline showing real-time spending, burn rate, and git context. Built and shipped Jan 16 with rapid iteration based on early feedback. Developer observability for AI coding. (Shell)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for GitHub Copilot API. The problem: developers needing programmatic Copilot access beyond editor extensions—for CI/CD, custom tooling, batch processing. Solution: clean SDK handling authentication, requests, and responses. 1 star, 1 fork—niche but real demand. (TypeScript)

**[goscrape](https://github.com/nguyenvanduocit/goscrape)** — Go-based website scraper for offline archival. The problem: need to preserve web content for offline docs, archival, or local development. Solution: reliable scraping with modern web handling. Updated Jan 8, 2026 with reliability improvements. (Go)

### Current focus (Jan 2026)

**Developer observability for AI coding** (`claude-statusline`): Shipped Jan 16 with rapid same-day iteration. The problem: Claude Code users burning API budgets blindly—no cost visibility until billing arrives. Solution: real-time statusline showing spending, burn rate, and git context. Early feedback confirms developers need to see what they're spending as they code. Iterating to surface the metrics that actually matter.

**MCP tooling at velocity**: Building tools for the Model Context Protocol ecosystem. The problem: developers juggling 5+ MCP servers across multiple editors (Claude Desktop, Cursor, Zed) with fragmented JSON configs, no health monitoring, manual installation friction. Working on unified management interfaces, automatic health checks, streamlined installation. Ship → observe usage → fix friction → ship again.

**Type-safe realtime RPC** (`socketrpc-gen`): Active development on type-safe RPC over socket.io. The problem: Socket.io lacks TypeScript guarantees between client and server, causing runtime errors and poor DX. Solution: code generation ensuring compile-time type safety across the wire. Addressing a core pain point in realtime apps where traditional REST patterns don't work.

**AI autonomy in production** (`mimaid`): Validating autonomous AI maintenance. Build failures trigger Claude agents that analyze logs, fix errors, open PRs, and merge—zero human intervention. Key learning: build failures, lint errors, dependency updates are safe for full autonomy. Architectural decisions and security patches still need human oversight. Proving this pattern works in daily production use.

**MCP at scale** (`jira-mcp`): 79 stars, 19 forks show real teams deploying AI-Jira integration in production. MCP evolved from "interesting protocol" to "critical integration layer" connecting AI to enterprise tools. Contributing Go implementations and operational patterns from running MCP servers under real load. Focus: production reliability, not just technical demos.

**Structured AI workflows** (`research-kit`): Exploring spec-driven research toolkit (9 stars). Testing how AI agents can systematize research—hypothesis formation, data collection, synthesis. Part of ongoing exploration into structured AI workflows beyond code generation. Learning what makes research tooling genuinely useful versus just technically possible.

### Technical depth

- **Backend & systems**: Go for MCP servers, CLIs, backend services. TypeScript for developer tooling and browser extensions. Shell scripting for CLI utilities and integrations
- **AI tooling**: MCP protocol implementation, agent orchestration, autonomous workflows, building bridges between AI capabilities and existing systems
- **Real-time systems**: Collaborative editing with Liveblocks, Yjs, WebSocket architectures
- **Type safety**: Type-safe APIs across Go and TypeScript—a design requirement, not an afterthought
- **Developer experience**: Building tools with clear metrics, cost visibility, and intuitive interfaces
- **Continuous delivery**: Rapid iteration cycles shipping improvements based on usage patterns

### Product thinking

I build by spotting workflow friction and shipping fixes:
- **claude-statusline**: Claude Code users burning budgets blindly → statusline with real-time cost tracking (shipped Jan 16)
- **MCP tooling**: developers juggling 5+ servers across editors with manual JSON config → unified management interfaces
- **jira-mcp**: teams burning hours on repetitive ticket operations → AI-native Jira access (79 stars, 19 forks, production deployments)
- **obsidian-open-gate**: knowledge workers context-switching between apps → seamless web integration (218 stars)
- **mimaid**: bloated Mermaid editors → minimal interface + AI-maintained infrastructure
- **copilot-sdk**: need programmatic Copilot access → TypeScript SDK for direct API calls
- **goscrape**: preserving web content offline → reliable Go-based scraper

Stars validate the problem exists. Commits prove the solution works. Production usage proves it's reliable. Rapid iteration (multiple releases same day) proves I listen to users.

### How I work

- **Ship early, iterate on feedback**: claude-statusline went from idea to shipped in one day. MCP tools ship multiple releases addressing friction immediately. mimaid deploys continuously with AI fixing builds autonomously.
- **Technical depth with product sense**: Build Go MCP servers for performance, design APIs for developer ergonomics. Type safety matters because it reduces pain. Visual interfaces solve config complexity. Surface the metrics developers actually need.
- **AI exploration with production discipline**: Testing MCP integrations, autonomous workflows, agent orchestration—always with reliability in mind. Not just discussing AI agents, actively deploying them. mimaid's autonomous build fixes prove the model works in production.
- **Match pace to problem type**: New tools get rapid iteration (multiple updates daily). Infrastructure gets deliberate architecture. User-facing friction gets immediate fixes. Technical foundations get time to mature.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Open to**: Developer tooling, AI infrastructure, autonomous workflows, MCP integrations

Building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, production MCP deployments, or solving real product problems in this space, let's talk.

---
*Last updated: 2026-01-17*
