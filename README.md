# Claude Code — Architecture Explorer

An interactive guide to the Claude Code source code architecture, built for product managers, engineers, and anyone curious about how Claude Code works under the hood.

**Live site:** https://ahmed-sarkawt.github.io/cd-architecture-preview/

## What's inside

The guide covers:

- **Overview** — Subsystem map and entry point walkthrough
- **Data Flow** — How a message travels from user input to model response to tool execution
- **Tech Stack** — Bun, React/Ink, TypeScript, Anthropic SDK, GrowthBook
- **Startup & REPL** — Initialization, execution modes, QueryEngine vs query.ts
- **Query Loop** — The agentic loop, streaming, tool call interception, auto-compact
- **Tools** — All 25+ built-in tools and what they do
- **Permissions** — The multi-layer permission system (default, plan, bypassPermissions, etc.)
- **State & Hooks** — AppStateStore and React hook bindings
- **Settings** — 4-layer cascading config (user → project → local → policy)
- **Lifecycle Hooks** — PreToolUse, PostToolUse, Stop, and more
- **MCP Protocol** — External tool server integration
- **Plugins & Skills** — Marketplace extensions and slash command workflows
- **Agents & Tasks** — Sub-agents, task types, swarm/teams multi-agent mode
- **UI Components** — React+Ink terminal component tree
- **Services** — API, compact, MCP, analytics, auth, memory, voice
- **PM Guide & Token Tips** — How to use Claude Code as a PM, token cost strategies
- **Token Optimization** — What drives token usage in the source code and how to reduce it
- **Upcoming Features** — Voice mode, Buddy, KAIROS, Coordinator mode, Remote sessions, and more
- **Code Structure Reference** — Every significant file with PM-oriented descriptions

## About Claude Code

Claude Code is Anthropic's official CLI for Claude — an AI coding assistant that runs in your terminal, understands your codebase, and can read files, run commands, edit code, and manage multi-step tasks autonomously.

This repository contains an architecture overview of the source code, not the source code itself.
