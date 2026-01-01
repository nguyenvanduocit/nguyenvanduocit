## Hi, I'm Duoc Nguyen 👋

I'm a Pi-shaped engineer: deep technical expertise in backend systems and AI tooling (Go, TypeScript), active exploration of AI agents and the Model Context Protocol ecosystem, and product sense from shipping developer tools and iterating based on real-world usage.

### What I build

**[jira-mcp](https://github.com/nguyenvanduocit/jira-mcp)** — Go-based MCP server that makes Jira AI-native. Born from watching teams waste time on repetitive ticket operations. Now AI assistants can handle issue management, sprint planning, and workflow transitions directly. 76 stars, real teams using it in production. (Go)

**[obsidian-open-gate](https://github.com/nguyenvanduocit/obsidian-open-gate)** — Obsidian plugin that solves the isolation problem of local knowledge bases. Lets you seamlessly integrate web content into your notes without breaking your flow. 215+ stars from knowledge workers who needed this exact bridge between their notes and the web. (TypeScript)

**[InstantCode](https://github.com/nguyenvanduocit/instantCode)** — Browser extension that eliminates context-switching when debugging frontend code. Click any element, ask AI about it—no copy-paste, no tab-switching. Integrated with GitHub Actions for continuous improvements from user feedback. 50 stars. (TypeScript)

**[mimaid](https://github.com/nguyenvanduocit/mimaid)** — Minimal Mermaid diagram editor because existing tools had messy, overcomplicated interfaces. Built with real-time collaboration using Liveblocks and Yjs. Solving the DX problem: clean interface, fast editing, no clutter. Live at [mimaid.aiocean.dev](https://mimaid.aiocean.dev). (TypeScript)

**[copilot-sdk](https://github.com/nguyenvanduocit/copilot-sdk)** — TypeScript SDK for direct GitHub Copilot API access. For developers who want programmatic integration with Copilot in their own workflows without the editor middleman. (TypeScript)

**[autosocial-trends](https://github.com/nguyenvanduocit/autosocial-trends)** — Daily automated trend research pipeline. Runs in production, delivering fresh trend data without manual overhead. Built to solve the content creator's problem: staying current without burning time on research.

**[socketrpc-gen](https://github.com/nguyenvanduocit/socketrpc-gen)** — Type-safe RPC over Socket.IO. Solves the DX gap where real-time communication breaks type safety, reducing runtime errors for teams using Socket.IO. (TypeScript)

### Current focus (Jan 2026)

**AI-first CI/CD refinement**: Building on the autonomous build-fixing pattern established in mimaid. Dec 29 demonstrated the full cycle: Claude analyzed Cloudflare Pages TypeScript error, created fix, merged PR—zero human intervention. Now refining this approach across multiple projects, establishing patterns for when AI should autonomously fix vs. alert. The goal: maintainable CI/CD that handles routine failures autonomously while escalating genuinely novel issues.

**Real-time collaboration tooling**: mimaid deployed collaborative diagram editing with Liveblocks + Yjs integration. Solving the problem where teams fumble with diagram sync across Slack/Notion. Real-time editing with AI-assisted error recovery means diagrams stay current without manual coordination overhead.

**Unlocking programmatic AI workflows**: copilot-sdk removes the IDE lock-in barrier. Latest work (Dec 29) focused on streamlined authentication and TypeScript ergonomics. Use case: integrate Copilot into custom tooling, CLIs, or backend workflows—not just editor extensions. Opening the door to AI-assisted automation that runs server-side or in CI/CD.

**Production-grade automation patterns**: autosocial-trends proves daily automated pipelines work at scale. Recent activity (Dec 28-30) shows consistent daily trend research with zero manual intervention. This isn't a demo—it's infrastructure that eliminates an entire job function. Key insight: reliable automation requires thoughtful error handling and monitoring, not just "run this daily."

**MCP ecosystem growth**: jira-mcp hit 76 stars, 20 forks—real adoption by teams integrating AI with enterprise workflows. The broader trend: MCP is moving from "interesting experiment" to "production integration layer." watching the ecosystem mature: more servers, better tooling, clearer patterns for AI-context standardization.

### Technical depth

- **Backend & systems**: Go for MCP servers, CLIs, and backend services. TypeScript for developer tooling and browser extensions
- **AI tooling**: MCP protocol implementation, agent orchestration, AI-assisted development workflows, building bridges between AI capabilities and existing developer workflows
- **Real-time systems**: Collaborative editing with Liveblocks, Yjs, and WebSocket-based architectures
- **Type safety**: Prioritizing type-safe APIs across Go and TypeScript—type-safety as a design requirement, not an afterthought
- **Continuous delivery**: GitHub Actions workflows that ship improvements based on real usage and user feedback. Testing AI-driven CI/CD patterns.

### Product thinking

I build by identifying real workflow friction and shipping solutions:
- **jira-mcp**: seeing teams waste hours on repetitive ticket operations, gave AI assistants native Jira access
- **obsidian-open-gate**: watching knowledge workers manually context-switch between apps
- **mimaid**: frustrated with bloated diagram editors when all I needed was clean Mermaid editing with real-time collaboration
- **InstantCode**: debugging frontend code shouldn't require constant tab-switching
- **autosocial-trends**: manual trend research was blocking content creation, so I automated it
- **copilot-sdk**: developers wanted programmatic Copilot access without being tied to IDE extensions

Stars validate the problem exists. Daily commits and iteration prove the solution works. Production usage proves it's reliable.

### How I work

- **Ship early, iterate based on usage**: InstantCode integrated GitHub Actions after seeing user patterns. autosocial-trends runs daily because that's what real users needed. mimaid deploys continuously to Cloudflare Pages with automated fixes.
- **Technical depth meets product sense**: Build MCP servers in Go for performance, but design APIs thinking about developer ergonomics. Type safety matters because it reduces user pain, not just because it's technically correct.
- **AI exploration with engineering discipline**: Testing MCP integrations, AI-assisted development workflows, and agent orchestration—but always with production reliability in mind. Not just talking about AI, actively using it to ship better code faster.

### Connect

- **Website**: [12bit.vn](https://12bit.vn)
- **Location**: Việt Nam
- **Company**: Sen Việt
- **Hireable**: Yes — open to interesting projects in developer tooling, AI infrastructure, or workflow automation

I care about building tools that make developers faster and workflows smoother. If you're working on developer tooling, AI agents, MCP integrations, or solving real product problems in this space, let's connect.

---
*Last updated: 2026-01-01*
