## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer with three dimensions of depth:

**Technical expertise**: Backend systems and AI tooling (Go, TypeScript). I build MCP servers, developer CLIs, and real-time collaborative systems with type safety as a design requirement.

**AI exploration**: Active work with AI agents, MCP protocol, and autonomous workflows. Not just discussing AI—deploying agents that fix builds, manage releases, and integrate enterprise systems in production.

**Product development**: Shipping tools, observing usage, fixing friction. I iterate rapidly based on real feedback—sometimes multiple releases in a day when users hit pain points.

I spot workflow problems and ship solutions. My projects eliminate context-switching, bridge AI with existing tools, and make complex workflows feel simple.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server giving AI assistants native Jira access. The problem: teams burning hours on repetitive ticket operations—status updates, sprint planning, bulk changes. Solution: issue management and workflow transitions through natural conversation with Claude. 79 stars, 19 forks show real teams deploying this in production. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin bridging local knowledge bases with the web. The problem: knowledge workers constantly context-switching between notes and research. Solution: seamless web integration that brings external data directly into your vault. 219 stars from users who needed exactly this workflow bridge. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor. The problem: existing Mermaid editors are bloated with features most users never touch. Solution: clean interface focused on editing + real-time collaboration (Liveblocks + Yjs). Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). AI agents autonomously maintain the codebase—fixing builds, updating deps. Production proof that AI can own routine maintenance while humans focus on product. (TypeScript)

**[claude-statusline](https://github.com/nguyenvanduocit/claude-statusline)** — Custom statusline for Claude Code with cost tracking and burn rate visibility. The problem: Claude Code users burning through API budgets blindly—no visibility into costs or session efficiency. Solution: shell-based statusline showing real-time spending, burn rate, and git context. Built and shipped Jan 16 with rapid iteration based on early feedback. Developer observability for AI coding. (Shell)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for GitHub Copilot API. The problem: developers needing programmatic Copilot access beyond editor extensions—for CI/CD, custom tooling, batch processing. Solution: clean SDK handling authentication, requests, and responses. 1 star, 1 fork—niche but real demand. (TypeScript)

**[goscrape](https://github.com/nguyenvanduocit/goscrape)** — Go-based website scraper for offline archival. The problem: need to preserve web content for offline docs, archival, or local development. Solution: reliable scraping with modern web handling. Updated Jan 8, 2026 with reliability improvements. (Go)

### Current focus (Jan 2026)

**Claude ecosystem tooling** (`aiocean/claude-plugins`): Latest work (4 pushes Jan 18) building plugins that extend Claude's capabilities. Active exploration of how to make AI assistants more powerful through extensibility. Focus on developer experience and seamless integration patterns.

**Developer observability for AI coding** (`claude-statusline`): Shipped Jan 16 with rapid same-day iteration—4 pushes on launch day responding to early feedback. The problem: developers burning through Claude API budgets with zero visibility—costs only visible when billing arrives. Solution: statusline with real-time cost tracking, burn rate, and git context. Proving observability matters in AI-assisted development.

**High-velocity CLI tooling** (`aiocean/clik-releases`): Sustained high development velocity—9 releases in Jan 12-13 alone. Building developer CLI tools with rapid iteration cycles. Each release addresses real usage patterns and friction points discovered through actual usage. Ship fast, learn fast, fix fast.

**AI autonomy in production** (`mimaid`): Multiple recent updates validating autonomous AI maintenance. Build failures trigger Claude agents that analyze logs, fix issues, open PRs, and merge—zero human intervention. Key insight: routine maintenance (builds, lint, deps) is safe for full autonomy. Architecture and security still need humans. Proving AI can own operational toil in production.

**MCP at production scale** (`jira-mcp`): 79 stars, 19 forks proving real teams deploy AI-Jira integration in production environments. MCP shifted from "interesting protocol" to "critical integration layer" connecting AI to enterprise systems. Contributing Go implementations and operational patterns from running MCP servers under real load. Focus: reliability and performance, not demos.

**Type-safe realtime systems** (`socketrpc-gen`): Addressing Socket.io's lack of TypeScript safety across client-server boundaries. The problem: runtime errors and poor DX in realtime apps where REST doesn't fit. Solution: code generation for compile-time type safety across the wire. Solving a fundamental pain point in collaborative and realtime applications.

**Structured AI exploration** (`research-kit`): Testing how AI agents systematize research workflows—hypothesis formation, data collection, synthesis. 9 stars from users exploring structured AI work beyond code generation. Learning what makes AI research tooling genuinely productive versus technically interesting.

### Technical depth

- **Backend & systems**: Go for MCP servers, CLIs, backend services. TypeScript for developer tooling and browser extensions. Shell scripting for CLI utilities and integrations
- **AI tooling**: MCP protocol implementation, agent orchestration, autonomous workflows, building bridges between AI capabilities and existing systems
- **Real-time systems**: Collaborative editing with Liveblocks, Yjs, WebSocket architectures
- **Type safety**: Type-safe APIs across Go and TypeScript—a design requirement, not an afterthought
- **Developer experience**: Building tools with clear metrics, cost visibility, and intuitive interfaces
- **Continuous delivery**: Rapid iteration cycles shipping improvements based on usage patterns

### Product thinking

I identify workflow friction, ship solutions, and iterate on feedback:

- **claude-statusline**: Developers burning API budgets with zero visibility → real-time cost tracking statusline (shipped Jan 16, 4 same-day updates)
- **aiocean/clik**: CLI development workflows → high-velocity tooling (9 releases v0.12.0→v0.16.16 in recent activity)
- **jira-mcp**: Teams spending hours on repetitive ticket operations → AI-native Jira access (79 stars, 19 forks, production deployments)
- **obsidian-open-gate**: Knowledge workers context-switching between notes and web → seamless integration (219 stars)
- **mimaid**: Bloated diagram editors → minimal Mermaid interface with AI-maintained codebase (production autonomous builds)
- **copilot-sdk**: Need programmatic GitHub Copilot access → clean TypeScript SDK
- **goscrape**: Web content preservation needs → reliable Go scraper

Stars show the problem is real. Commits show solutions work. Production deployments show it's reliable. Rapid iteration (sometimes multiple releases daily) shows I respond to user feedback.

### How I work

- **Ship early, iterate on feedback**: `claude-statusline` launched Jan 16 with 4 same-day updates. `clik` shipped 9 releases in recent activity cycles. `mimaid` deploys continuously with AI handling builds. Fast cycles reveal what actually matters.

- **Technical depth meets product thinking**: Build Go MCP servers for performance. Design APIs for developer ergonomics. Type safety reduces pain. Clean interfaces solve complexity. Surface metrics developers actually use, not vanity numbers.

- **AI in production, not just demos**: Deploying MCP servers under real load. Running autonomous AI agents that fix builds and manage releases. Testing agent orchestration with production discipline. Learning what works reliably versus what's just technically interesting.

- **Velocity matched to impact**: Developer friction gets immediate fixes (multiple daily releases). Infrastructure gets deliberate architecture. Production systems get reliability focus. Rapid iteration where it compounds learning.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Open to**: Developer tooling, AI infrastructure, autonomous workflows, MCP integrations

Building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, production MCP deployments, or solving real product problems in this space, let's talk.

---
*Last updated: 2026-01-18 - Active: Claude plugin development, high-velocity CLI tooling, AI observability*
