# MantleScope 🛰️

**AI-powered onchain intelligence dashboard for the Mantle L2 network.**

Built for the **Mantle Turing Test Hackathon 2026**. Connects to live Mantle RPC, visualizes onchain activity, and layers a multi-model AI analyst on top — so you can ask questions about wallets and transaction flows in plain language.

🔗 **Live demo:** [mantlescope-fawn.vercel.app](https://mantlescope-fawn.vercel.app)

## Features

- **Live onchain data** — connects directly to Mantle RPC (`rpc.mantle.xyz`) via ethers.js, with a configurable custom RPC endpoint
- **Dashboard** — live transactions, top whale wallets, 24h volume by protocol (Merchant Moe, Agni, mETH, USDY…)
- **Wallet Analyzer** — token holdings, recent transactions, and behavioral read for any Mantle address
- **Multi-model AI analyst** — switch between DeepSeek V3 / R1, Claude Sonnet 4, and GPT-4o / 4o-mini; the app speaks each provider's API format natively
- **Whale alerts** — configurable MNT threshold for flagging large moves
- **Bring-your-own-key** — your AI API key stays in your browser (localStorage), never sent anywhere except the model provider

## Tech stack

- Vanilla JS single-page app (no build step)
- [ethers.js](https://docs.ethers.org/) for RPC calls
- Unified AI layer supporting both Anthropic and OpenAI-compatible APIs
- Deployed on Vercel

## Running locally

Just open `index.html` in a browser — no build, no dependencies to install.

To use the AI analyst, open ⚙️ **Settings** and paste your own API key (DeepSeek, Anthropic, or OpenAI).

## Screenshots

<!-- TODO: add a screenshot of the dashboard here -->
<!-- Drag an image into GitHub's editor, or put it in an /assets folder and link it -->

---

Built by [rusmoody](https://github.com/rusmoody) · onchain builder, Telegram bots · Web3 · LLM apps
