# HarshJudge Marketplace

Claude Code plugin marketplace for [HarshJudge](https://github.com/HuskyDanny/HarshJudge) — AI-native E2E testing orchestration.

## Setup

Add the marketplace to Claude Code:

```bash
/plugin marketplace add HuskyDanny/harshjudge-marketplace
```

## Install

```bash
/plugin install harshjudge@harshjudge-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **harshjudge** | E2E testing orchestration with visual evidence capture and live dashboard |

## What You Get

- **Skill**: Auto-triggers on E2E testing tasks (scenario creation, test execution, status checks)
- **MCP Server**: 12 tools for test lifecycle management (init, create, run, evidence, dashboard)
- **Dashboard**: Visual review of test scenarios, runs, and evidence

## Prerequisites

- Node.js 18+
- Claude Code with MCP support
- Playwright MCP server (for browser automation)

## License

MIT
