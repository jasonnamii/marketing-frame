# marketing-frame-engine

> 🇰🇷 [한국어 README](./README.ko.md)

**Marketing frame router with 140+ frameworks DB × 3-axis routing (time·customer·execution) × 2 modes (plan·diagnose) × dual output (.md + .html bento). Industry-specific 6-frame recipes auto-recommended.**

## Prerequisites

- **Claude Cowork or Claude Code** environment
- Optional: Obsidian Vault for `.md` master output persistence

## Goal

Marketing planning and diagnosis often suffer from "framework overload" — knowing 4P, STP, AARRR, JTBD, Cynefin, Wardley separately, but not which combination fits the current situation. This skill solves that by routing input across three axes (time scope · customer funnel · execution phase) and selecting 3–6 MECE-checked frameworks from a 140+ DB, then filling a 10-slot bento canvas with industry-specific recipes.

## When & How to Use

Trigger when starting a marketing plan, diagnosing a stalled campaign, preparing an IR section, or asking "which framework lens should we use here?" Frame router only — copywriting, pitch decks, financial models, UI design, and IMC execution are delegated to specialist skills.

## Use Cases

| Scenario | Prompt | What Happens |
|---|---|---|
| SaaS series A prep, 18% retention | `"시리즈 A 직전 SaaS 성장 전략 짜줘"` | PLAN mode → SaaS B2B recipe → Strategy Diamond + AARRR + NSM+Counter + Reverse Trial |
| D2C beauty stagnation | `"광고비 늘어도 CAC만 오름. 진단해줘"` | DIAGNOSE mode → D2C recipe → HEAVY-LIGHT + Four Realms + Cohort + RFM |
| Campaign post-mortem | `"지난 캠페인 벤토로 복기"` | DIAGNOSE → 10-slot bento (.md + .html) with backward One Promise |

## Key Features

- **140+ frameworks** across 6 categories: classic consulting, digital growth, brand creative, psychology, B2B/platform, meta·emerging
- **3-axis routing**: Cynefin time scope × funnel customer stage × execution phase
- **Dual mode**: PLAN (forward, hypothesis) vs DIAGNOSE (backward, evidence)
- **Industry recipes**: 8 domains × 6 frameworks auto-matched (SaaS B2B, D2C, media, finance, retail, startup, platform, brand campaign)
- **Bento output**: 10 slots (Strategic Q · Routing · Frames · Pain · AS-IS/TO-BE · Issues · FAQ Gap · Counter-Metric · One Promise · Confidence)
- **Dual format**: Obsidian `.md` master + Apple-style `.html` bento (A4 print + 1080p deck)
- **Counter-Metric guard**: prevents NSM single-metric over-optimization

## Works With

- **[copywriting-engine](https://github.com/jasonnamii/copywriting-engine)** — for copy generation after frame selection
- **[bp-guide](https://github.com/jasonnamii/bp-guide)** — for pitch deck after marketing strategy
- **[financial-model](https://github.com/jasonnamii/financial-model)** — for revenue scenarios after frame routing
- **[ui-action-designer](https://github.com/jasonnamii/ui-action-designer)** — for landing page UI after copy
- **[brand-campaign](https://github.com/jasonnamii/brand-campaign)** — for IMC campaign execution after strategy
- **[ads-playbook](https://github.com/jasonnamii/ads-playbook)** — for ad ops tuning after media plan

## Installation

```bash
git clone https://github.com/jasonnamii/marketing-frame-engine.git ~/.claude/skills/marketing-frame-engine
```

## Update

```bash
cd ~/.claude/skills/marketing-frame-engine && git pull
```

Skills placed in `~/.claude/skills/` are automatically available in Claude Code and Cowork sessions.

## Part of Cowork Skills

This is one of 25+ custom skills. See the full catalog: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## License

MIT License — feel free to use, modify, and share.
