# Claude Project Context: best-of-algorithmic-trading

This file provides context for the **best-of-algorithmic-trading** repository, used as part of an AI trading-knowledge project.

## Project Overview
* **Name**: best-of-algorithmic-trading
* **Type**: Auto-generated, ranked "best-of" list (part of the `best-of-lists` ecosystem)
* **Purpose**: A weekly-updated, quality-ranked catalog of ~100+ open-source algorithmic trading projects — libraries, bots, backtesting tools, data feed clients — grouped into categories with star counts, contributor counts, open-issue ratios, and a computed "project-quality score."
* **License**: list content under CC0/MIT-style license (per `best-of-lists` template); individual listed projects have their own licenses

## Core System Boundaries
* **Generated from config**: the human-edited source of truth is typically `projects.yaml` (or similar config file) — the `README.md` is auto-generated from it via the `best-of-generator` tool.
* **Ranking metaphor**: projects are tagged with medal emojis (🥇🥈🥉) and a numeric score reflecting GitHub stars, forks, contributors, recent commit activity, and issue resolution rate — higher score ≈ more actively maintained/healthier project.
* **"Show hidden projects"**: many archived/less-active projects are collapsed under expandable sections — still useful as historical reference but lower priority for new work.

## Repository Structure & Key Directories
* `/README.md` - Auto-generated ranked list, organized into categories (e.g. General Frameworks, Trading Bots, Exchange APIs, Technical Analysis, Backtesting, Data Sources)
* `/projects.yaml` (if present) - Machine-readable source list of all tracked projects (name, repo URL, category, labels)
* `/.github/workflows/` - Automation that regenerates the README on a schedule

## Standard Operational Commands
* N/A — reference document only. If the user wants to regenerate or add a project, that involves the separate `best-of-generator` tool operating on `projects.yaml`.

## AI Assistant Guidelines for this Project
1. **Quality signal first**: when choosing between multiple candidate libraries for the same task, prefer ones ranked higher (🥇 over 🥈/🥉) and flag any marked as archived/dead (often shown with a skull or "Show hidden projects" marker) as higher-risk for new projects.
2. **Category-based lookup**: map the user's need (e.g. "crypto exchange connectivity," "backtesting," "technical indicators") to the matching category in this list before suggesting a tool.
3. **Cross-reference with other knowledge files**: several top-ranked entries here (freqtrade, ccxt, FinRL, nautilus_trader, backtrader, ta-lib-python, QuantLib, zipline, quantstats) have their own dedicated CLAUDE.md files in this project — prefer those for implementation details, and use this list mainly for *discovering alternatives* or *comparing options*.
4. **Freshness check**: scores and star counts are point-in-time snapshots from when the repo was forked — if precise current numbers matter, verify on GitHub directly rather than trusting this file's exact figures.
