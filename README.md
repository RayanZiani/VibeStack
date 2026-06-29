# VibeStack

The ultimate, ultra-optimized AI-First Boilerplate designed specifically for **Vibecoding**. Turn your CLI LLM (Aider, Cline, Cursor, Claude etc.) into an elite web architect. 

Instead of letting your AI build from raw scratch leading to hallucinations, messy codebases, and massive token waste, **VibeStack** provides a pristine, high-performance foundation and guides the AI step-by-step through a root-level `AGENT.md` file.

---

## Key Features

- **AGENT.md Orchestrator:** A Markdown-based, step-by-step algorithmic prompt at the root that guides any LLM CLI to safely configure the project without breaking existing architecture.
- **Dual-Framework Power:** Pre-built, ultra-optimized starter kits for both **Next.js** (App Router) and **Astro** (Static/Hybrid).
- **Dynamic Theme Tokens:** Centralized CSS variables/Tailwind configurations allowing the AI to change styles, palettes, and typography instantly with zero risk of breaking layouts.
- **Production-Ready i18n:** Built-in localization architecture ready to be populated dynamically by the AI.
- **Built-In SEO & Speed:** Pre-configured with perfect meta tags, OpenGraph routing, automatic sitemaps, and strict asset optimization for a baseline 100/100 Lighthouse score.

---

## File Architecture

Here is the clean, modular structure designed to keep the AI's context footprint as small as possible:

```text
.
├── AGENT.md                 # Core AI Orchestrator & Interactive Setup Guide
├── README.md                # Project Overview & Usage Guide
├── ROADMAP.md               # Future Features & Milestones
├── scripts/
│   └── setup.js             # Lightweight script invoked by the Agent to swap/clean templates
└── templates/
    ├── astro/               # Ultra-Optimized Astro Template
    │   ├── src/
    │   │   ├── components/  # Atomic, clean UI blocks
    │   │   ├── layouts/     # SEO & Meta ready layout wraps
    │   │   └── pages/       # Content pages & routing
    │   ├── public/          # Optimized static assets
    │   ├── astro.config.mjs
    │   └── package.json
    └── next/                # Ultra-Optimized Next.js Template
        ├── src/
        │   ├── app/         # App Router with built-in layout/page structures
        │   ├── components/  # Strict modular UI components
        │   └── styles/      # Tailwind & Design tokens configuration
        ├── next.config.js
        └── package.json