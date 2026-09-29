# Dhruv Khara

I build AI dev tools, security tooling, and crypto trading systems. Mostly Go and TypeScript.

## Projects

### AI dev tools

- **[Argus](https://github.com/BeLazy167/argus)**. A self-hostable code review GitHub App. It computes a review contract per PR to set review depth, then specialist agents post inline findings with confidence scores and suggested fixes. Demo at [argus.reviews](https://argus.reviews/).
- **[deliberate-coder](https://github.com/BeLazy167/deliberate-coder)**. An agent skill that makes the model state assumptions, edge cases, and failure modes before writing code.
- **[typesafe-mod](https://github.com/BeLazy167/typesafe-mod)**. A Claude Code function hook that sends decisions to TypeSafe's Jev model. One hook ranks installed skills against the prompt. A second hook answers the agent's either-or questions and returns a probability for each option.
- **[claude-mods-skill](https://github.com/BeLazy167/claude-mods-skill)**. A skill that teaches agents to build Claude Mods, the TypeScript function-hook plugins. Ships a working starter mod.
- **[mermaid-mcp](https://github.com/BeLazy167/mermaid-mcp)**. Renders Mermaid source to PNG or SVG over MCP or HTTP. Long-running Chromium workers do the rendering, and an in-memory cache answers repeat requests.

### Trading and data

- **[polymarket-btc-bot](https://github.com/BeLazy167/polymarket-btc-bot)**. Trades 5-minute BTC up/down markets on Polymarket. An ensemble model prices fair value, the bot sizes bets with positive expected value, and it exits at a target price. Paper mode included.
- **[hl-mcp](https://github.com/BeLazy167/hl-mcp)**. A remote MCP server for Hyperliquid written in Go. It exposes account reads, market data, and order placement, and it records every trade in a local SQLite audit. It exposes no withdrawal or key-management calls.
- **[freefinancialdataset](https://github.com/BeLazy167/freefinancialdataset)**. A Go server that exposes the 27 Financial Datasets MCP tools and matching REST routes, sourcing data through Monid. Hosted at [financialdatasets.rip](https://financialdatasets.rip).
- **[Elliott Wave Wiki](https://elliottwave.wiki/)**. A cheat sheet for Elliott Wave traders. It collects the patterns, Fibonacci levels, and entry and exit rules in one place.

Most of what I'm building lives in private repos. Drop me a line if you'd like a walkthrough.

## Stack

Go · TypeScript · Python · Rust · Next.js · Postgres · Bun

## Reach me

[Email](mailto:dhruvkhara167@gmail.com) · [LinkedIn](https://linkedin.com/in/belazy) · [X](https://x.com/belazyAF)
