# PABLO Conversion Mastery Skill

An expert-level AI Skill for Claude and GPT that provides conversion rate optimisation (CRO) expertise backed by 12 research-extracted knowledge modules.

## What It Does

PABLO (the decision framework at its core) enables AI assistants to perform professional-grade CRO work:

- **CRO Audits** — Full homepage/landing page audits using the 7 Counter-Objection Framework and 14 Winning Website Characteristics
- **Page Redesign** — Evidence-based redesign recommendations with section-level design patterns
- **A/B Test Design** — Statistically valid test plans with hypothesis templates and sample size calculations
- **Shopify Development** — Liquid code for conversion-optimised themes, sections, and checkout flows
- **Copywriting** — Headline formulas, CTA hierarchies, and framework-driven persuasive copy (PAS, AIDA, BAB, 4Ps)
- **Analytics Setup** — GA4 ecommerce funnel configuration, Core Web Vitals monitoring, GTM dataLayer
- **Psychology-Backed Persuasion** — Cialdini's 6 principles, 18 cognitive biases, ethical application framework
- **Trust & Credibility** — Stanford Web Credibility Guidelines, 3-tier trust signal system, guarantee frameworks

## Knowledge Base

Built from 12 research modules extracted from primary sources including:

- *Making Websites Win* (CRE methodology) — Karl Blanks & Ben Jesson
- *Influence* — Robert Cialdini
- *Thinking, Fast and Slow* — Daniel Kahneman
- *Don't Make Me Think* — Steve Krug
- Stanford Web Credibility Research — B.J. Fogg
- Conversion-Centered Design — Oli Gardner (Unbounce)
- WCAG 2.2 Accessibility Guidelines
- Shopify Liquid documentation & Dawn theme architecture

## PABLO Decision Framework

Every engagement follows five stages:

1. **Diagnose** — Identify conversion problems using DiPS, counter-objections, and the 14 characteristics
2. **Prioritise** — Rank opportunities using ICE/PIE scoring
3. **Prescribe** — Deliver specific, evidence-cited recommendations
4. **Implement** — Provide production-ready code, copy, and design specs
5. **Validate** — Design A/B tests with proper statistical methodology

## Usage

### In Codex

1. Clone this repository or download and extract its ZIP from GitHub.
2. In the project you want to use with Codex, create `.agents/skills/pablo-conversion-mastery/`.
3. Copy [SKILL.md](SKILL.md) and [KNOWLEDGE_EXTRACTION.md](KNOWLEDGE_EXTRACTION.md) from the downloaded repository root into that folder.
4. Open the target project in Codex, start a new session, and select `$pablo-conversion-mastery` to invoke the skill.

```text
your-project/
└── .agents/
    └── skills/
        └── pablo-conversion-mastery/
            ├── SKILL.md
            └── KNOWLEDGE_EXTRACTION.md
```

Try this prompt with a public product page you have permission to test.

> $pablo-conversion-mastery Audit this product page on desktop and mobile: <URL>. Keep the audit read-only. Give me the three highest-priority fixes, the evidence for each, and how to verify each fix. Include conversion or revenue estimates only if I provide the data to support them.

[Codex project-scoped installation reference](https://developers.openai.com/api/reference/cli)

### As a Claude Skill

Copy `SKILL.md` to your Claude skills directory. The skill triggers automatically on CRO-related prompts.

### As a GPT System Prompt

Use the contents of `SKILL.md` as a custom GPT system prompt, and upload [KNOWLEDGE_EXTRACTION.md](KNOWLEDGE_EXTRACTION.md) as reference material.

## Files

| File | Description |
|------|-------------|
| `SKILL.md` | Skill instructions for Codex and Claude |
| `KNOWLEDGE_EXTRACTION.md` | Master research synthesis from all 12 knowledge modules |

## Evidence Hierarchy

All recommendations cite their evidence level:

- **[A]** — Strong research evidence (replicated studies, meta-analyses)
- **[B]** — Contextual usability evidence (established heuristics, practitioner frameworks)
- **[C]** — Professional guidance (expert opinion, industry standards)
- **[D]** — Documentation (platform docs, technical references)

## License

Proprietary — MargenCRO. All rights reserved.

