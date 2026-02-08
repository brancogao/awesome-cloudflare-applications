# Cloudflare Workers Chat Bot Starters

A comprehensive list of open-source starters and frameworks for building Discord and Telegram bots on Cloudflare Workers.

## 🤖 Discord Bots

Discord bots on Workers leverage the Discord Interactions API for zero-cold-start performance.

| Tool | Focus | Description |
| --- | --- | --- |
| **[cloudflare-sample-app](https://github.com/discord/cloudflare-sample-app)** | Official | The official Discord sample for Workers; handles signature verification and slash commands. |
| **[discord-hono](https://github.com/luudis/discord-hono)** | Robust | A lightweight Hono-based wrapper for the Discord API. |
| **[slshx](https://github.com/slshx/slshx)** | Framework | A framework-agnostic Discord Interactions handler. |

## ✈️ Telegram Bots

Workers can host Telegram bots efficiently using Webhooks mode.

| Tool | Focus | Description |
| --- | --- | --- |
| **[grammY](https://github.com/grammyjs/grammY)** | Recommended | Modern, type-safe framework with first-class support for Workers. |
| **[cloudflare-telegram-bot](https://github.com/m-sarabi/cloudflare-telegram-bot)** | Tutorial | A dedicated template for grammY on Workers with a setup guide. |
| **[cfworker-telegraf-template](https://github.com/Tsuk1ko/cfworker-telegraf-template)** | Classic | Provides Telegraf framework support for Cloudflare's edge. |

## 📚 Official Resources

*   **[Hosting grammY on Cloudflare Workers](https://grammy.dev/hosting/cloudflare-workers)**
*   **[Discord Tutorial for Cloudflare Workers](https://discord.com/developers/docs/tutorials/hosting-on-cloudflare-workers)**
