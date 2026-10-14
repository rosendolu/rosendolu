<!--suppress HtmlDeprecatedAttribute -->

# Rosendo 👋

AI agent developer focused on **crypto intelligence**, **Rust financial infrastructure**, and practical developer tools.

[![Profile views](https://hits.sh/github.com/rosendolu.svg?label=Profile%20views&extraCount=509)](https://hits.sh/github.com/rosendolu/) [![GitHub](https://img.shields.io/badge/GitHub-rosendolu-181717?logo=github)](https://github.com/rosendolu)

I build AI-native systems that turn market data, technical indicators, and developer workflows into useful tools for people and agents.

## What I build

- 🤖 **AI agents & agent tooling** — MCP servers, tool calling, structured workflows, Skills, Rules, and integrations for Cursor and Claude Code.
- 🪙 **Crypto intelligence** — multi-exchange market data, technical analysis, portfolio views, arbitrage research, and automation primitives.
- 🦀 **Rust financial infrastructure** — reusable indicator libraries and performance-oriented components for quantitative applications.
- 🛠️ **Developer productivity tools** — CLI tools and open-source utilities that make AI-assisted development more repeatable.

## Featured projects

### 🪙 [crypto-mcp-server](https://github.com/rosendolu/crypto-mcp-server)

> An MCP server that gives AI assistants access to cryptocurrency market data and analysis workflows.
> [![Telegram](https://img.shields.io/badge/Telegram-Join-229ED9?logo=telegram)](https://t.me/crypto_mcp)

- Unified access to Binance, Gate, OKX, and other CCXT exchanges
- K-line and indicator analysis: MACD, Bollinger Bands, KDJ, EMA, RSI, and more
- Cross-exchange arbitrage analytics and multi-account portfolio views
- Designed for agent workflows in Cursor and Claude Code

```json
{
    "Crypto MCP Server": {
        "command": "npx",
        "args": ["-y", "crypto-mcp-server"],
        "env": {
            "BINANCE_API_KEY": "",
            "BINANCE_SECRET": "",
            "GATE_API_KEY": "",
            "GATE_SECRET": ""
        }
    }
}
```

### 🦀 [financial_indicators](https://github.com/rosendolu/financial_indicators)

> A Rust library for technical analysis and quantitative finance building blocks.

[![Crates.io](https://img.shields.io/crates/v/financial_indicators.svg)](https://crates.io/crates/financial_indicators) [![Docs](https://docs.rs/financial_indicators/badge.svg)](https://docs.rs/financial_indicators)

MA · EMA · MACD · KDJ · RSI · Bollinger Bands · DMI/ADX

```toml
[dependencies]
financial_indicators = "*"
```

### 🚀 [cursor-rules-deploy](https://github.com/rosendolu/cursor-rules-deploy)

> A CLI for deploying Cursor AI rules and templates so agent-assisted development can be shared and reproduced.

```bash
npx cursor-rules-deploy
```

### 🎨 [canvas-studio](https://github.com/rosendolu/canvas-studio)

> An earlier open-source canvas and video-editing project demonstrating experience in interactive tools, media workflows, and performance-sensitive UI.

[![Live demo](https://img.shields.io/badge/Live%20Demo-draw.rosendo.fun-blue)](https://draw.rosendo.fun)

## Engineering background

Before focusing on AI agents and crypto tooling, I built real-time media tools, canvas editors, VS Code extensions, and developer automation systems. That experience informs how I approach agent products today: make them observable, composable, fast, and useful in production.

## GitHub activity

<p align="center">
  <a href="https://github.com/rosendolu">
    <img src="https://github-readme-stats-one-bice.vercel.app/api?username=rosendolu&theme=gotham&show_icons=true&count_private=true&hide_border=true&role=OWNER,ORGANIZATION_MEMBER,COLLABORATOR" width="48%" alt="GitHub statistics" />
  </a>
  <a href="https://github.com/rosendolu">
    <img src="https://github-readme-streak-stats.herokuapp.com?user=rosendolu&theme=dark&hide_border=true" width="48%" alt="GitHub streak" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/rosendolu">
    <img src="https://github-readme-activity-graph.vercel.app/graph?username=rosendolu&theme=react-dark&hide_border=true&area=true" width="96%" alt="GitHub activity graph" />
  </a>
</p>

## Currently exploring

- Reliable long-running crypto agents with clear risk boundaries
- Rust services for market data, indicators, and event-driven analysis
- Better evaluation, observability, and reproducibility for tool-using agents

<p>
  <i>Building useful agents at the intersection of AI, crypto, and Rust.</i>
</p>
