# ValueAI SPA

Landing page for the **ValueAI** platform — a unified marketing site that bridges the **AI Spend Audit** tool and the **ValueAI optimization dashboard**.

## Overview

This is a single-page application (SPA) built with React 18 (via Babel standalone) and Tailwind CSS (via CDN). It serves as the front door for two products:

- **[AI Spend Audit](https://ai-spend-audit-taupe.vercel.app/)** — A free tool that audits your AI tool subscriptions (Cursor, ChatGPT, Claude, etc.) and identifies savings opportunities.
- **[ValueAI Dashboard](https://value-ai-ten.vercel.app/)** — A full-stack platform for real-time monitoring, cost normalization, and plan optimization across 15+ AI providers.

## Features

- Hero section with animated gradient backgrounds and scroll-triggered reveals
- Infinite marquee showcasing 15 supported AI providers (OpenAI, Anthropic, Google, Mistral, etc.)
- Problem/solution positioning with interactive cards
- 4-step "How It Works" process flow
- Product analysis section highlighting the audit engine
- Detailed provider directory with models and pricing
- Feature grid covering analytics, cost prediction, team allocation, security, alerts, and regional pricing
- Comparison table (Direct vs. ValueAI)
- Testimonials carousel
- FAQ accordion
- Call-to-action linking to the audit tool

## Tech Stack

- **UI:** React 18 (UMD), Tailwind CSS (CDN), Babel standalone
- **Build:** None — zero-bundle, served directly as a static HTML file
- **Deployment:** Compatible with any static host (Vercel, Netlify, GitHub Pages, etc.)

## Usage

Simply open `index.html` in a browser or deploy the directory to any static file server:

```bash
# Local preview (via VS Code Live Server, npx serve, etc.)
npx serve .
```

## Structure

```
value-ai-spa/
├── index.html    # Complete SPA (all markup, styles, and components inline)
└── README.md     # This file
```

All React components — `Navbar`, `Hero`, `Marquee`, `Problem`, `Steps`, `ToolSection`, `Providers`, `Features`, `Comparison`, `Testimonials`, `FAQ`, `CTA`, `Footer` — are defined within the single `index.html` using `type="text/babel"` scripts.

## Related Repositories

- [value-ai](https://github.com/Kartikeyongit/value-ai) — Full-stack AI infrastructure cost optimization platform
- [ai-spend-audit](https://github.com/Kartikeyongit/ai-spend-audit) — AI subscription audit tool
