# Project Roadmap: VibeStack 🗺️

This roadmap outlines the multi-stage evolution of VibeStack from a local developer utility into an industry-grade framework for AI-assisted development (Vibecoding).

---

## Phase 1: Foundation & Core Architecture (MVP)
*Goal: Build the base templates and validate the interactive AGENT.md execution.*

- [ ] **Repository Setup:** Initialize the template repository structure and implement a root-level script execution strategy.
- [ ] **Agnostic Boilerplates:**
  - Build the **Astro Template** with clean routing, asset compression, and modern best practices.
  - Build the **Next.js Template** utilizing the App Router, strict TypeScript (optional/switchable), and optimal caching rules.
- [ ] **Design Token System:** Implement unified Tailwind CSS / standard CSS variable mappings so the AI can safely execute theme changes without altering actual component logic.
- [ ] **AGENT.md v1.0:** Author the master algorithmic prompt instructing LLMs to sequentially onboard users, explain tradeoffs between Next.js & Astro, and execute basic setup commands.

---

## Phase 2: Built-in Optimization (SEO & i18n)
*Goal: Guarantee production-ready outputs immediately after AI initialization.*

- [ ] **Perfect SEO Injection:** Build automated SEO component shells containing predefined open-graph schemas, structural JSON-LD data metadata, `sitemap.xml` automation, and `robots.txt`.
- [ ] **Localization Matrix (i18n):** Create standardized JSON/dictionary structure paths. Ensure the `AGENT.md` can prompt the user for target languages and instruct the AI to generate the corresponding translation trees instantly.
- [ ] **Lighthouse 100 Baseline:** Hardcode advanced asset optimization rules (lazy-loading, font swapping, modern image formats) to prevent the AI from degrading performance scores during expansion.

---

## Phase 3: AI Intelligence, Benchmarking & Cost Efficiency
*Goal: Provide developers with exact metrics regarding token usage and financial cost per project.*

- [ ] **Model Recommendation Engine:** Map specific development workflows to appropriate LLMs inside the documentation:
  - *Architecture & Logic:* Claude 4.6 Sonnet / GPT-5.
  - *Content, Assets & Translations:* GPT-5-mini / Claude 4.5 Haiku.
- [ ] **Context-Window Sanitization:** Implement a secondary `content/AGENT.md` to hand off instructions. Once the site framework is generated, the AI is instructed to clear its active context window to minimize recurring token usage.
- [ ] **Cost Matrix Calculation:** Provide a benchmark table analyzing typical token expenditure:
  - **Initial Configuration:** ~50k–100k tokens ($0.15 - $0.30 via modern cost-efficient models).
  - **Feature Expansion:** ~30k tokens per complex UI feature.

---

## Phase 4: Launch, Documentation & Ecosystem
*Goal: Community scaling, multi-language support, backend integration.*

- [ ] **GitHub Template Tagging:** Properly expose the repository using GitHub’s native Template feature to enable instant code scaffolding.
- [ ] **Support More Languages:** Support for angular, vue and more.
- [ ] **Backend Integration:** Integration for FastAPI, Go and Rust backend structures.