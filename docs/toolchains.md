# Cloudflare Open Source Toolchains

A curated list of popular and emerging open-source toolchains and core developer tools from Cloudflare.

## AI & Agentic SDKs

*   **[Workers AI](https://developers.cloudflare.com/workers-ai/)**: Run machine learning models (LLMs, Whisper, Image Gen) on Cloudflare's global GPU network.
*   **[Model Context Protocol (MCP)](https://github.com/model-context-protocol)**: An open standard for connecting AI agents to external systems, natively supported via Cloudflare SDKs.
*   **[AI-Agent-Scaffold](https://github.com/cloudflare/agents-sdk)**: Build autonomous agents that live on the edge with this specialized SDK.

## Developer Experience (DX)

*   **[Wrangler](https://github.com/cloudflare/workers-sdk/tree/main/packages/wrangler)**: The essential CLI for building, testing, and deploying Cloudflare Workers and Pages.
*   **[Workerd](https://github.com/cloudflare/workerd)**: The open-source JavaScript/Wasm runtime that powers Cloudflare Workers, suitable for local development and self-hosting.
*   **[Hono](https://hono.dev/)**: The standard-bearer ultrafast web framework optimized for Cloudflare Workers.

## Security & Infrastructure

*   **[Firewall for AI](https://blog.cloudflare.com/firewall-for-ai/)**: A dedicated security layer to protect LLMs from prompt injection and abuse.
*   **[OpenPubkey SSH](https://github.com/openpubkey/openpubkey)**: Integration of SSO with SSH for secure, identity-based infrastructure access.
*   **[Cap'n Web](https://blog.cloudflare.com/capn-web/)**: Next-generation RPC protocol designed for high-performance edge communication.

## Core Services

*   **[Cloudflare Workers](https://workers.cloudflare.com/)**: The core serverless platform for executing code at the network edge.
*   **[cdnjs](https://github.com/cdnjs/cdnjs)**: The world's #1 free open-source CDN for web libraries, maintained by Cloudflare.
*   **[WARP (BoringTun)](https://github.com/cloudflare/boringtun)**: Cloudflare's open-source implementation of WireGuard in Rust.
