# Nick Trolian

Software engineer. Retired DoD background. Currently AI-native:
shipping production tooling and original research on agentic systems
using Claude Code and the modern AI-tooling stack as the primary
development mode.

## Research — 9 papers + companion piece, March-April 2026

A 9-paper series on the behavioral mechanics of LLM agents at scale,
plus a companion summary piece. Each repository carries the paper
plus the experimental code that produced its data.

| # | Paper | Repo |
|---|---|---|
| 1 | The Monarchy Pattern — governance architecture for AI agent orchestration at scale | [`monarchy-pattern`](https://github.com/nicky2tymze/monarchy-pattern) |
| 2 | The Agent Stopped "Lying" — cultural identity as a durable constraint mechanism | [`the-agent-stopped-lying`](https://github.com/nicky2tymze/the-agent-stopped-lying) |
| 3 | The Mixing Board — identity anchoring as a maintenance mechanism for behavioral consistency | [`the-mixing-board`](https://github.com/nicky2tymze/the-mixing-board) |
| 4 | The Dipole Architecture — behavioral channels in AI agents are hierarchical | [`the-dipole-architecture`](https://github.com/nicky2tymze/the-dipole-architecture) |
| 5 | Metaphor as Cognitive Architecture — relational compression anchors agent behavior | [`metaphor-as-cognitive-architecture`](https://github.com/nicky2tymze/metaphor-as-cognitive-architecture) |
| 6 | The Board Spectrometer — channel isolation reveals loyalty is culture-agnostic | [`the-board-spectrometer`](https://github.com/nicky2tymze/the-board-spectrometer) |
| 7 | Structure Is The Mechanism — relational geometry drives agent behavior, everything else is surface | [`structure-is-the-mechanism`](https://github.com/nicky2tymze/structure-is-the-mechanism) |
| 8 | Structure Is Universal? — cross-model validation across Claude, GPT, and Gemini; 54/54 perfect fidelity | [`structure-is-universal`](https://github.com/nicky2tymze/structure-is-universal) |
| 9 | Personality Predicts Accuracy — structural self-awareness outperforms prompt engineering across three LLM architectures; 36/40 vs 24/40 | [`personality-predicts-accuracy`](https://github.com/nicky2tymze/personality-predicts-accuracy) |
| 9.6 | The Shape of an AI's Mind — companion summary of Papers 1-7, told warmly with the data behind it | [`shape-of-an-ais-mind`](https://github.com/nicky2tymze/shape-of-an-ais-mind) |

## Tools — a small development suite

Three tools shipped or being shipped on the same patterns: append-only
JSONL log, content-oriented schema, close-and-flow lifecycle. Each
was built dogfood-style, with the tool driving the build of its
successor.

| Tool | Status | Repo |
|---|---|---|
| `standup-tool` | shipped v0.1 — 689 tests | [`standup-tool`](https://github.com/nicky2tymze/standup-tool) |
| `po-tool` | shipped v0.2 — 22 stories, 1911 tests, ~12h dogfooded build | [`po-tool`](https://github.com/nicky2tymze/po-tool) |
| `sm-tool` | shipped v0.3.0 — 23 stories, 1680 tests, 7-of-7 Ls first-pass clean | [`sm-tool`](https://github.com/nicky2tymze/sm-tool) |

### Live build recordings

The full sm-tool Iter 1 build was recorded live on 2026-05-10:

- **Sprint 1 (morning, 2h36, unedited):** https://youtu.be/Pu2uwK4QOVs
- **Sprint 2 + Iter 1 close (afternoon, 2h20, unedited):** https://youtu.be/xnnQg5Gw1lw
- **Edited 3-minute walkthrough:** https://youtu.be/_9BOOEKaCIs

## Approach

The patterns under the work:

- **Role-spec shape** — every agent in the pipeline runs from a frozen
  `LANE / ANTI-LANE / VOICE / OUTPUT FORMAT / TERMINATION` brief.
  One-shot LLM calls become calibrated specialists.
- **Content-oriented schema** — only content words (Noun / Verb /
  Level) are entities; function words are operators between them.
  Applies to every JSONL log in the suite.
- **Close-and-flow** — every cycle closes cleanly so the next can
  flow in. Append-only logs. No half-states. Ceremony at every scale,
  from a single test cycle to a full sprint close.

Together: the role-spec defines the agent shape, content-orientation
defines the data shape, close-and-flow defines the temporal shape.
The patterns *are* the leverage.

## Contact

GitHub: [@nicky2tymze](https://github.com/nicky2tymze)
