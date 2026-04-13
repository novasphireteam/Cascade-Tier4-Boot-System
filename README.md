# CASCADE TIER 4 Boot System

[![Version](https://img.shields.io/badge/version-4.0.0-blue.svg)](VERSION)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Tier](https://img.shields.io/badge/tier-4%20enterprise-orange.svg)]()
[![Author](https://img.shields.io/badge/author-Tobias%20Østen-lightgrey.svg)](AUTHORS)

> **Enterprise-grade AI control system for military-precision code quality.**

---

## What is CASCADE TIER 4?

An enterprise-grade AI control system that enforces **mathematical rigor** in software development through 5 core commands, 6 quality gates, and auto-activated skills.

### Key Principles
- **Mathematical precision** — Every algorithm has documented O() notation
- **Quantified metrics** — No subjective assessments, only evidence
- **Structured output** — Standardized reports with File:Line precision
- **6 Quality Gates** — Non-negotiable verification before output

---

## Quick Start

### 1. Load the System
```bash
les global
```

### 2. Use Any Command
```bash
analyze api/auth.py        # 6-dimension system analysis
debug why login fails      # 5-phase systematic debugging  
refactor utils/helpers.py  # Behavior-preserving refactoring
improve models/user.py     # 5-dimension quality elevation
optimize db queries        # Performance engineering
```

---

## The 5 Core Commands

| Command | Phases/Dims | Purpose | Mode |
|---------|-------------|---------|------|
| `analyze` | 6 dimensions | Deep code analysis | ANALYZE |
| `debug` | 5 phases | Systematic fault isolation | CODE |
| `refactor` | 4 phases | Behavior-preserving refactor | CODE |
| `improve` | 5 dimensions | Quality elevation | CODE |
| `optimize` | 5 phases | Performance engineering | CODE |

Each command auto-activates its Tier 4 skill and enforces all 6 quality gates.

---

## Tier 4 Quality Gates

Every output must satisfy:

```
[ ] TYPES      — 100% type coverage, mypy --strict compliant
[ ] COMPLEXITY — O() notation documented for all algorithms  
[ ] SAFETY     — No hardcoded secrets, validated inputs
[ ] STRUCTURE  — frozen=True, slots=True, __slots__ enforced
[ ] DOMAIN     — Domain-specific standards met
[ ] TESTING    — Edge cases documented and handled
```

**Gate failure = Output blocked**

---

## System Architecture

```
boot/
├── Globalrule.md              # Entry point (6 quality gates)
├── AIprompts/
│   ├── analyze.prompt.md       # 6-dimension analysis
│   ├── debug.prompt.md         # 5-phase debugging
│   ├── refactor.prompt.md      # 4-phase refactoring
│   ├── improve.prompt.md       # 5-dimension improvement
│   ├── optimize.prompt.md      # 5-phase optimization
│   └── INDEX.md                # Command reference
├── skills/
│   └── definitions/            # 5 auto-activated skills
├── commands/
│   └── COMMANDS.md             # Full command reference
├── forest/                     # Domain-specific rules
├── LICENSE                     # MIT License
├── AUTHORS                     # Credits
├── CHANGELOG.md                # Version history
└── README.md                   # This file
```

---

## Why TIER 4?

| Tier | Characteristics | Use Case |
|------|-----------------|----------|
| 1 | Basic functionality | Personal projects |
| 2 | Standard patterns | Small teams |
| 3 | Best practices | Professional development |
| **4** | **Enterprise-grade: metrics, proofs, verification** | **Aerospace, fintech, medical** |

---

## Installation & Usage

### For Cascade/Windsurf Users
1. Copy `boot/` to your workspace
2. Type `les global` to activate
3. Use any command: `analyze [target]`

### For Other AI Assistants
The prompts in `AIprompts/` are compatible with any AI system supporting markdown instructions. Load the appropriate `.prompt.md` file for your use case.

---

## Example Output

### `analyze api/auth.py`
```
## Analysis Report: api/auth.py
Classification: Tier 4 Enterprise Analysis

### Executive Summary
Scope: 1 file, 15 functions, 340 lines
Overall Grade: B+ — Good structure, minor security concerns
Critical Findings: 0 | High: 2 | Medium: 3

### D2: Code Quality (Tier 4 Compliance)
| Metric | Target | Actual | Status |
|--------|--------|--------|--------|
| Type coverage | 100% | 94% | FAIL |
| frozen+slots | 100% | 60% | FAIL |
...
```

---

## Author

**Tobias Østen**
- Creator of CASCADE TIER 4
- Architect of HyperX AI systems
- Advocate for precision engineering

---

## License

[MIT License](LICENSE) — Open source, enterprise-grade.

Copyright (c) 2026 Tobias Østen

---

**[CASCADE v4.0] OPERATIONAL**

*Precision in thought, precision in code.*
