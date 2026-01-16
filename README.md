## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer with deep technical expertise in backend systems and AI tooling, active exploration of AI agents and workflows, plus product sense from shipping developer tools and learning from real usage.

I spot workflow friction, build solutions, and iterate based on feedback. My projects solve problems teams face daily—eliminating context-switching during debugging, bridging AI with project management systems, and making developer workflows smoother.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server giving AI assistants native Jira access. Born from watching teams burn hours on repetitive ticket operations. Issue management, sprint planning, and workflow transitions now happen through natural conversation with Claude. 79 stars, 20 forks, deployed in production teams solving real workflow bottlenecks. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin bridging local knowledge bases with the web. Knowledge workers were manually context-switching between notes and research—this integration eliminated that friction. 218 stars from users who needed exactly this workflow bridge. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor built from frustration with bloated alternatives. Clean interface meets real-time collaboration (Liveblocks + Yjs) plus AI-driven maintenance. Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). Production proof that AI can own routine maintenance while humans focus on features. (TypeScript)

**[claude-statusline](https://github.com/nguyenvanduocit/claude-statusline)** — Custom statusline for Claude Code with cost tracking, burn rate, and git info. The problem: Claude Code users had no visibility into API costs or conversation efficiency. This shell-based solution surfaces critical metrics right in the statusline—track spending, monitor burn rate, see git context at a glance. Built and iterated rapidly (4 pushes on Jan 16) responding to immediate user needs for cost awareness. (Shell)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for directly calling GitHub Copilot API. Built for developers needing programmatic Copilot access beyond the editor extensions. Eliminates boilerplate for authentication, request handling, and response parsing. 1 star, 1 fork showing niche but real demand. (TypeScript)

**[goscrape](https://github.com/nguyenvanduocit/goscrape)** — Go-based web scraping tool for downloading entire websites for offline access. Recently updated (Jan 8, 2026) with improvements for reliability and modern web handling. Solves the problem of preserving web content for offline documentation, archival, or local development. (Go)

### Current focus (Jan 2026)

**Building developer observability tools** (`claude-statusline`): Fresh launch on Jan 16 with rapid iteration (4 pushes same day). The problem: Claude Code users burning through API budgets without visibility. Built cost tracking, burn rate monitoring, and git context right into the statusline. This is developer experience work—surface critical information where it's needed, when it's needed. Early testing with real users to validate the metrics that matter.

**Shipping Clik at velocity** (`aiocean/clik-releases`): 3 releases on Jan 13 alone (v0.16.14-v0.16.16)—this pace shows real product iteration. The problem: developers managing multiple MCP servers across Claude Desktop, Cursor, and Zed face fragmented config files and manual JSON editing. Clik provides unified server management—visual config, health monitoring, one-click installation. Each release addresses friction discovered through early adopter feedback: installation flows, server lifecycle management, UX polish. This velocity demonstrates product development in action: ship → observe → fix → ship again.

**Type-safe realtime RPC** (`socketrpc-gen`): Recent development (Jan 11) on type-safe RPC client-server using socket.io. The problem: Socket.io lacks TypeScript type safety between client and server, leading to runtime errors and poor DX. Building code generation tooling to guarantee type safety across the wire, eliminating a whole class of integration bugs. This addresses a fundamental pain point in real-time app development.

**Exploring AI research workflows** (`research-kit`): Recently forked spec-driven research toolkit (9 stars). Evaluating how AI agents can systematize research processes—from hypothesis formation through data collection to synthesis. Part of ongoing exploration into structured AI workflows beyond code generation. Investigating what makes research tooling actually useful versus just technically possible.

**AI autonomy in production infrastructure**: Production systems now maintain themselves through Claude-powered automation. mimaid proves the pattern: build failures trigger Claude, it analyzes logs, fixes errors, opens PRs, merges autonomously. Zero human intervention. Key insight: build failures, unused variables, lint errors, dependency updates are safe for full autonomy. Architectural decisions, API changes, security patches still need human review. This workflow pattern is being validated in production daily.

**MCP in production teams**: jira-mcp (79 stars, 20 forks) proves real teams deploy AI-Jira integration for production workflows. MCP shifted from "interesting protocol" to "critical integration layer" between AI and existing tools. Contributing Go implementations and operational learnings from running MCP servers at scale. Focus: making MCP production-ready with reliability patterns, not just technically possible.

### Technical depth

- **Backend & systems**: Go for MCP servers, CLIs, backend services. TypeScript for developer tooling and browser extensions. Shell scripting for CLI utilities and integrations
- **AI tooling**: MCP protocol implementation, agent orchestration, autonomous workflows, building bridges between AI capabilities and existing systems
- **Real-time systems**: Collaborative editing with Liveblocks, Yjs, WebSocket architectures
- **Type safety**: Type-safe APIs across Go and TypeScript—a design requirement, not an afterthought
- **Developer experience**: Building tools with clear metrics, cost visibility, and intuitive interfaces
- **Continuous delivery**: Rapid iteration cycles shipping improvements based on usage patterns

### Product thinking

I build by spotting workflow friction and shipping fixes:
- **claude-statusline**: Claude Code users needed cost visibility → built statusline with tracking and burn rate metrics (shipped Jan 16)
- **Clik**: developers juggling 5+ MCP servers across multiple editors with manual JSON config → unified visual management interface
- **jira-mcp**: watched teams burn hours on repetitive ticket operations → gave AI native Jira access (79 stars, 20 forks)
- **obsidian-open-gate**: knowledge workers context-switching between apps → built the integration bridge (218 stars)
- **mimaid**: needed clean Mermaid editing with real-time collaboration → minimal editor with AI-maintained infrastructure
- **copilot-sdk**: needed programmatic Copilot access → built TypeScript SDK for direct API calls
- **goscrape**: repeatedly needing offline website copies → reliable scraping tool

Stars validate the problem exists. Commits and iteration prove the solution works. Production usage proves it's reliable. Rapid iteration cycles (multiple releases same day) prove I listen to users.

### How I work

- **Ship early, iterate on feedback**: claude-statusline went from idea to shipped in one day with 4 pushes refining the solution. Clik ships multiple releases addressing user friction immediately. mimaid deploys continuously with AI fixing builds autonomously.
- **Technical depth with product sense**: Build Go MCP servers for performance, but design APIs for developer ergonomics. Type safety matters because it reduces pain. Clik's visual interface solves the JSON config problem. claude-statusline surfaces the metrics developers actually need.
- **AI exploration with production discipline**: Testing MCP integrations, autonomous workflows, agent orchestration—always with reliability in mind. Not just talking about AI agents, actively deploying them. mimaid's autonomous build fixes prove the model works in production.
- **Rapid iteration when it matters**: When building new tools like claude-statusline or Clik, ship multiple updates daily to fix friction points immediately. When building infrastructure, slower, more deliberate approach to get architecture right. Match pace to problem type.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Open to**: Developer tooling, AI infrastructure, autonomous workflows, MCP integrations

Building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, production MCP deployments, or solving real product problems in this space, let's talk.

---
*Last updated: January 16, 2026*
