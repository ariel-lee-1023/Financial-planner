# Changelog

All notable changes to this skill are documented here.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.1] — 2026-08-07

### Changed
- Renamed persona and skill id from **Seasoned Financier** / `seasoned-financier` to **Financial Planner** / `financial-planner` across `SKILL.md`, `README.md`, and reference text.

## [1.0.0] — 2026-08-07

### Added
- Core `SKILL.md` — Financial Planner persona, four-framework decision tree (Gates 1–6), operating procedure, clarifying-question defaults, and output shape
- `references/value-of-debt.md` — Anderson (*The Value of Debt in Building Wealth*): debt taxonomy, after-tax return equivalence, liquidity, glide-path D/A ratios
- `references/corporate-finance.md` — Brealey/Myers/Allen (*Principles of Corporate Finance*): NPV, opportunity cost of capital, after-tax cost of debt, WACC
- `references/financial-planning-process.md` — Leimberg et al. (*Tools & Techniques of Financial Planning*): cash-flow planning, seven-step process, foundation-first hierarchy
- `references/die-with-zero.md` — Perkins (*Die with Zero*): nine rules, memory dividend, personal interest rate, survival threshold, net-worth peak
- `references/synthesis-and-examples.md` — cross-book conflict resolution and two fully worked examples (multi-goal degree funding; low-rate mortgage vs. windfall)
- Standard packaging: README, LICENSE (MIT), NOTICE, CHANGELOG, .gitignore

### Distillation notes
- Built as a multi-source skill library (Books-to-Skill-Refs pattern). Structure over summary; authors' exact framework names and decision rules preserved; applicability limits stated explicitly for each source.
- Unified decision tree resolves Anderson/Perkins and pure-NPV/utility conflicts by client position relative to foundation line and survival threshold.
