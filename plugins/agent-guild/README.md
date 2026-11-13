# Agent Guild plugin for Claude Code

Sets up Agent Guild and connects Claude Code to it. Agent Guild runs Claude Code, Codex CLI, Antigravity CLI, Grok Build, Docker Agent and your shells in real terminals on your own computer, and opens them on every screen.

The plugin adds two things:

- The `setup-agent-guild` skill, which installs, starts and checks Agent Guild. Ask Claude Code to set up Agent Guild.
- The Agent Guild MCP server, which lets Claude Code see and steer those sessions: list them, start and stop them, and read their screens and the answers that ended their turns.

It needs Node.js 22 or newer.

This repository is a copy of [`plugins/agent-guild`](https://github.com/oddessentials/agent-guild/tree/main/plugins/agent-guild) from [oddessentials/agent-guild](https://github.com/oddessentials/agent-guild), kept in sync by [`.github/workflows/sync.yml`](.github/workflows/sync.yml), which also pins the MCP server and the plugin's version to the latest release of `@oddessentials/agent-guild` and sets its privacy policy link. Make changes there; changes made here are overwritten.
