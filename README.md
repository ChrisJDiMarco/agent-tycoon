# Agent Tycoon

An idle tycoon game in a single HTML file: build an AI empire from one laptop.

Click **Ship Work** (or press Space) to earn cash, then hire AI agents that earn for you, from Intern Bot and Researcher up through Builder, Deal Closer, Orchestrator and Agent Swarm. Each hire costs 15% more than the last. Buy stack upgrades (Notion Workspace, Slack Integration, n8n Automations, Firecrawl Data, Claude Opus, MCP Registry and more) to multiply agent output or click power. Once a run has earned $1M you can take the company public: an IPO resets agents and upgrades in exchange for permanent equity, and each equity point adds 10% to all future output. Buy in batches of 1, 10 or max.

Progress autosaves to the browser's `localStorage` every 5 seconds and when the tab is hidden, and the game credits offline earnings when you come back. A Reset button wipes the save.

Built by Chris DiMarco with Claude (Claude Cowork), June 2026.

## Run it

Open `index.html` in any modern browser. There is no build step, server or dependency. Fonts (Space Grotesk, JetBrains Mono) load from Google Fonts when online and fall back to system fonts offline.

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | The whole game: markup, styles and script |

Original location: `/Users/chrisdimarco/jarvis/owners-inbox/agent-tycoon.html`. Backed up 2026-10-16.
