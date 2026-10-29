# gstack Skills Reference for Attendance-Tracker

This project has been configured with [gstack](https://github.com/garrytan/gstack) skills located in `.agents/skills/`.

## How to Invoke Skills

In Antigravity, skills can be triggered naturally by prompt intent or by slash command:

- `/gstack` — Router skill: routes any workflow question to the right specialist
- `/gstack-office-hours` — Reframes product thinking, scope, and technical direction
- `/gstack-plan-ceo-review` — CEO-level review: challenges assumptions and refines requirements
- `/gstack-plan-eng-review` — Engineering review: architecture, edge cases, state management, and tests
- `/gstack-plan-design-review` — Design review: audits visual hierarchy, spacing, typography, and polish
- `/gstack-autoplan` — Multi-phase pipeline: CEO review → Design review → Eng review
- `/gstack-review` — Rigorous pre-landing PR review for correctness, edge cases, security, and bugs
- `/gstack-qa` — Autonomous end-to-end quality assurance (browser, API, CLI, webhooks)
- `/gstack-investigate` — Systematic root-cause debugging without speculative fixes
- `/gstack-ship` — Tests, reviews, gate checks, commit, and PR creation

---

## Complete Catalog of Installed Skills (58)

| Skill | Purpose |
| :--- | :--- |
| `gstack` | Master router for the gstack skill suite |
| `gstack-office-hours` | Product interrogation and problem reframing |
| `gstack-plan-ceo-review` | Strategic high-level product and feature review |
| `gstack-plan-eng-review` | Technical architecture, data flow, error states, and testing plan |
| `gstack-plan-design-review` | UX/UI critique and design grading |
| `gstack-plan-devex-review` | Developer experience, time-to-hello-world, API ergonomics |
| `gstack-plan-tune` | Interactive question sensitivity tuning |
| `gstack-autoplan` | Automated chain: CEO → Design → DevEx → Engineering |
| `gstack-spec` | Converts intent into an executable 5-phase specification |
| `gstack-design-consultation` | Design system generation and token foundation |
| `gstack-design-html` | High-fidelity, clean HTML/CSS generation |
| `gstack-design-review` | Visual design inspection, responsiveness, layout audit |
| `gstack-design-shotgun` | Multi-variant design ideation and evaluation |
| `gstack-devex-review` | Developer flow audit and DX friction point analysis |
| `gstack-deslop-shared-libs` | Identifies worthwhile abstraction/refactor targets |
| `gstack-review` | Pre-merge pull request review for production defects |
| `gstack-qa` | Surface-aware testing for web UI, APIs, workers, and webhooks |
| `gstack-qa-only` | Report-only QA audit without touching source code |
| `gstack-test-audit` | Audits test suite quality, flake risks, and test coverage |
| `gstack-investigate` | Hypothesis-driven root-cause debugging |
| `gstack-ship` | Verification, automated testing, branch prep, and PR push |
| `gstack-land-and-deploy` | Merge, CI verification, and release deployment |
| `gstack-canary` | Post-deployment monitoring and health checks |
| `gstack-landing-report` | Release and PR queue status dashboard |
| `gstack-document-release` | Documentation updates and release note synchronization |
| `gstack-document-generate` | Diataxis technical documentation generation |
| `gstack-setup-deploy` | Deployment configuration detection |
| `gstack-cso` | Chief Security Officer audit (OWASP, secrets, trust boundaries) |
| `gstack-careful` | Safe execution guardrails for sensitive operations |
| `gstack-guard` | Workspace guardrails against destructive operations |
| `gstack-freeze` / `gstack-unfreeze` | Code freeze lock / unlock |
| `gstack-health` | Environment and health diagnostics |
| `gstack-retro` | Engineering sprint / ship retrospective |
| `gstack-learn` | Team learnings and operational playbook capture |
| `gstack-scrape` | Structured web data extraction |
| `gstack-skillify` | Turns repetitive workflows into custom skills |
| `gstack-diagram` | Mermaid / architecture diagram generation |
| `gstack-make-pdf` | Document and report rendering |
| `gstack-browse` | Headless browser execution and verification |
| `gstack-open-gstack-browser` | Interactive browser launcher |
| `gstack-setup-browser-cookies` | Browser session cookie management |
| `gstack-codex` | Secondary review or consulting via OpenAI Codex |
| `gstack-claude-code` | Secondary review or consulting via Claude Code |
| `gstack-pair-agent` | Specialist pair-programming coordination |
| `gstack-benchmark` / `gstack-benchmark-models` | LLM eval benchmarking |
| `gstack-eval-plan` | Benchmark plan evaluation |
| `gstack-context-save` / `gstack-context-restore` | Session context persistence |
| `gstack-setup-gbrain` / `gstack-sync-gbrain` | Cross-session memory sync |
| `gstack-ios-clean` / `gstack-ios-fix` / `gstack-ios-qa` / `gstack-ios-sync` / `gstack-ios-design-review` | Mobile iOS workflows |
| `gstack-upgrade` | Upgrade installed gstack skills to latest upstream version |
