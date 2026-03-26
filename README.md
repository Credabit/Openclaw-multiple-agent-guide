# 🦞 OpenClaw — The Complete Guide

> **One document to rule them all.** Everything you need to go from "what is this lobster thing?" to running your own personal AI agent from WhatsApp, Telegram, Discord, iMessage — or wherever you already live.

---

## 🌐 View the Guide

**👉 [Read it live (GitHub Pages)](https://yourusername.github.io/openclaw-guide/)**
**📄 [Download the PDF](./openclaw-guide.pdf)**

---

## Why This Exists

If you've been anywhere near the AI/LLM space lately, you've probably seen people losing their minds over [OpenClaw](https://openclaw.ai). Things like:

> *"It's running my company."* — @therno

> *"Using OpenClaw for a week and it genuinely feels like early AGI."* — @tobi_bsf

> *"Everything Siri was supposed to be. And it goes so much further."* — @crossiBuilds

OpenClaw is an **open-source, self-hosted AI gateway** that connects your existing chat apps to any LLM you choose — Anthropic, OpenAI, Gemini, local Ollama models, you name it. It has persistent memory, cron jobs, browser control, a skills/plugin system, and it runs on your own hardware. It's the closest thing we have right now to a real personal AI agent you actually own.

The official docs are great — but they're spread across dozens of pages. This guide **pulls the entire thing into one place**: navigable, searchable, cross-linked, and formatted for humans who want to actually understand how it all fits together.

---

## 📚 What's Covered (20 Sections)

| # | Section | What you'll learn |
|---|---------|-------------------|
| 01 | **What is OpenClaw?** | The big picture — what it is, who it's for, why it's different |
| 02 | **Features** | The full feature matrix — channels, agents, media, tools, automation |
| 03 | **Installation** | Every install method: one-liner, npm, Docker, Nix, Podman, from source |
| 04 | **Onboarding** | CLI wizard and macOS app — get from zero to running in 5 minutes |
| 05 | **Quick Start** | The exact commands, in order, to get a working agent |
| 06 | **Gateway Architecture** | How the Gateway actually works under the hood — WebSocket protocol, hot reload, failure modes |
| 07 | **Channels** | All 22+ messaging integrations with config examples |
| 08 | **Memory & Sessions** | How the agent remembers things across conversations, vector search, compaction |
| 09 | **Multi-Agent Routing** | Running multiple agents, sub-agents, delegation patterns |
| 10 | **Built-in Tools** | Every tool the agent can use — exec, browser, file I/O, web search, image gen |
| 11 | **Skills System** | The SKILL.md system, ClawHub registry, creating and installing custom skills |
| 12 | **Plugins** | Extending OpenClaw with community and custom plugins |
| 13 | **Automation & Cron Jobs** | Scheduling, standing orders, webhooks, Gmail PubSub — making your agent proactive |
| 14 | **Model Providers** | All 35+ supported LLMs — Anthropic, OpenAI, Gemini, Ollama, Groq, Mistral, and more |
| 15 | **Platforms** | macOS, Linux, Windows, iOS, Android — what works where |
| 16 | **Hosting & Cloud** | 14 deployment options from Raspberry Pi to Kubernetes |
| 17 | **Configuration Reference** | The full openclaw.json with annotated examples |
| 18 | **Security & Sandboxing** | Pairing, allowlists, sandboxing, formal threat model |
| 19 | **Help & Troubleshooting** | Common problems, quick fixes, debugging commands |
| 20 | **Community & Resources** | Where to connect, what people have built, how to contribute |

---

## 🙌 Who This Is For

**You'll get the most out of this if you're...**

- 🤖 **An LLM tinkerer** who wants to go deeper than ChatGPT and actually own your AI stack
- 📱 **Someone who wants AI in their pocket** — messaging your agent from WhatsApp or Telegram like a real assistant
- 🏗️ **A builder** who wants to understand the Skills and Plugin system so you can extend OpenClaw for your own workflows
- 🔒 **Privacy-conscious** and done with handing your data to closed platforms — self-hosted all the way
- 🆕 **Brand new to OpenClaw** and not sure where to start
- ⚡ **Already running OpenClaw** and tired of hunting through 30 doc pages to find that one config option

---

## ✨ What Makes This Guide Useful

- **Single file, fully navigable** — sticky sidebar, smooth scroll, active section highlighting
- **Everything links out** — every topic links directly to the relevant official doc page
- **All 35+ model providers** listed with direct links — find your LLM, click, done
- **All 22+ channels** documented with setup notes and links
- **Real code examples** for every CLI command, config snippet, and cron schedule
- **Dark themed** — because you're probably reading this at midnight
- **PDF version included** — same content, printable, hyperlinks intact
- **Zero dependencies** — one HTML file, works offline, host anywhere

---

## 📦 Repo Contents

```
├── index.html          # The full interactive guide
├── openclaw-guide.pdf  # PDF version (same content)
└── README.md           # You're reading it
```

---

## 🚀 Host Your Own Copy

It's a single self-contained HTML file — no build step, no dependencies.

**GitHub Pages**
1. Fork this repo
2. Go to **Settings → Pages → Source → `main` branch**
3. Live at `https://yourusername.github.io/openclaw-guide/` in ~60 seconds

**Anywhere else** (Vercel, Netlify, Cloudflare Pages)
- Drop `index.html` in and deploy — that's it

**Locally**
```bash
open index.html   # macOS
# or just double-click the file
```

---

## 🔗 Official OpenClaw Links

| | |
|---|---|
| 🌐 Website | [openclaw.ai](https://openclaw.ai) |
| 📖 Official Docs | [docs.openclaw.ai](https://docs.openclaw.ai) |
| ⭐ GitHub | [github.com/openclaw/openclaw](https://github.com/openclaw/openclaw) |
| 💬 Discord | [discord.com/invite/clawd](https://discord.com/invite/clawd) |
| 🛒 ClawHub (Skills Registry) | [clawhub.ai](https://clawhub.ai) |
| 🔒 Trust | [trust.openclaw.ai](https://trust.openclaw.ai) |

---

## ⚠️ Heads Up

This is an **unofficial, community-created guide** — not affiliated with or endorsed by the OpenClaw project or Anthropic. All content is sourced from the official OpenClaw documentation. For the authoritative source, always check [docs.openclaw.ai](https://docs.openclaw.ai). Links throughout the guide point back to the official pages.

---

## 🤝 Contributing

Something outdated? Missing a section? PRs are welcome.

- Keep every new topic linked back to the official doc page
- Match the dark theme and formatting style
- The goal is clarity — one place, everything, no hunting

---

*🦞 Not affiliated with Anthropic. OpenClaw is MIT licensed and community-driven.*
*Built for people who believe the future of AI is personal, private, and self-hosted.*
