# Agent Configuration

How my AI tooling is set up for this bootcamp. Written so I can rebuild this on a new machine without digging through memory.

## Primary Tool: Claude Code

**Why Claude Code over alternatives:** Native CLI integration means I can work in the same terminal where I run builds, deploys, and git commands — no context-switching to a browser tab. The agentic capabilities (file editing, shell commands, multi-step reasoning) are the closest thing to pair programming without scheduling someone else's time. Compared to ChatGPT's code interpreter or Copilot's inline suggestions, Claude Code handles the "here's a vague goal, figure out the steps" workflow that dominates real development.

## Configuration

- **Model:** Claude Opus (latest) — reasoning-heavy tasks benefit from the larger model
- **Shell:** PowerShell on Windows 11
- **Working directory:** Project-local (each repo gets its own Claude Code session)
- **Memory:** Auto-memory enabled for accumulating project context across sessions

## Custom Slash Commands

*(none yet — will add as patterns emerge from repeated workflows)*

## MCP Servers

*(none connected yet — will document if/when I add integrations)*

## Skills Used

- `init` — generated the initial CLAUDE.md scaffolding
- `simplify` — for code review passes on demo artifacts

## Rebuild Checklist

If setting up on a fresh machine:

1. Install Claude Code CLI
2. Authenticate with Anthropic credentials
3. Clone this repo
4. Run `claude` in the repo directory — auto-memory and project context load automatically
5. Verify shell integration (PowerShell) works for git and build commands

---

*Last updated: 2026-05-19*
