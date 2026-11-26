# 天机·决策智囊团 | Tianji Decision Council

**An evidence-aware, bilingual AI decision-support skill.**  
A structured council of strategic, philosophical, economic, psychological, and risk-management lenses for consequential decisions.

- Version: 1.0.0
- Language: Chinese + English
- License: MIT
- Format: portable `SKILL.md` plus modular reference files

## What it does

Tianji helps users:
1. define the real decision and success criteria;
2. separate facts, assumptions, estimates, and unknowns;
3. select relevant intellectual lenses;
4. produce independent analyses and structured disagreement;
5. run a devil's-advocate pre-mortem;
6. compare options and make trade-offs explicit;
7. create an action plan with metrics and stop conditions;
8. review decisions against outcomes over time.

It is a **decision-support tool, not an oracle or substitute for qualified professional advice**.

## Quick start

1. Copy this directory into a platform's supported skills directory, or upload `SKILL.md` as the skill's main instruction file.
2. Keep `agents/`, `references/`, `workflows/`, and `templates/` alongside it if the platform supports referenced files.
3. Start with a real decision, for example:

   > `/full 我正在考虑与一家渠道商合作。请先明确决策问题，再分析双方利益、现金流、控制权、退出机制和最坏情况。`

4. For a fast challenge:

   > `/devil 请假设这个方案一年后失败，倒推最可能的失败路径。`

## Project structure

```text
.
├── SKILL.md
├── README.md
├── LICENSE
├── CHANGELOG.md
├── CONTRIBUTING.md
├── agents/                 # 12 core intellectual lenses
├── references/             # Domain frameworks and decision models
├── workflows/              # Debate, analysis, pre-mortem, review
├── templates/              # Reusable report template
├── tests/                  # Scenario-based quality tests
└── docs/                   # Publishing and usage guidance
```

## Core council

| Lens | Main contribution |
|---|---|
| Sun Tzu | Competitive strategy, advantage, positioning |
| Guiguzi | Stakeholder incentives, persuasion, relationships |
| Fan Li | Commercial timing, wealth, entry and exit |
| Han Fei | Rules, governance, accountability |
| Machiavelli | Power structures and political realism |
| Peter Drucker | Customer value, management, effectiveness |
| Michael Porter | Industry structure and competitive advantage |
| Charlie Munger | Inversion, mental models, avoiding errors |
| Daniel Kahneman | Cognitive biases and judgment |
| Nassim Nicholas Taleb | Tail risk, fragility, downside protection |
| Laozi | Systems, change, restraint, timing |
| Wang Yangming | Self-examination and action |

These are **analytical lenses**, not simulated historical attendance. The system must not invent quotations or claim certainty about what a person would say today.

## Design principles

- Evidence over authority.
- Independent analysis before debate.
- Disagreement over artificial consensus.
- Downside limits before upside fantasies.
- Explicit uncertainty and reversal conditions.
- Actionable decisions, not theatrical role-play.

## Compatibility

This repository uses a simple Markdown skill entry point and modular Markdown references. Different AI platforms implement skills and file loading differently. Some may load only `SKILL.md`; in that case, merge the relevant reference material into the main instruction or provide it as knowledge files. No platform-specific API or runtime is required.

## Safety and limitations

- Not financial, legal, medical, or other licensed professional advice.
- Current facts must be checked against current, authoritative sources.
- Scores are structured judgments, not calibrated probabilities.
- Historical and contemporary figures are represented through documented ideas; source attribution and interpretation should be checked.
- Do not upload confidential or sensitive information unless the platform and your permissions allow it.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md). Suggestions for new thinkers should include primary sources, a distinct analytical contribution, limitations, and test cases.

## License

MIT. See [LICENSE](LICENSE).
