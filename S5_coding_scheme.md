# S5 — Thematic-Analysis Coding Scheme (Formative Interviews)

Analysis approach: transcription followed by thematic analysis with a **hybrid coding scheme** — deductive codes for the five evaluation constructs, plus inductive codes for emergent themes. Interview themes were cross-referenced with the expert-walkthrough findings to distinguish design issues confirmed by intended users from those raised only by inspection. Quantitative 1–5 perceptions are reported descriptively (see `S6_statistics.md`); n = 11 (developers, one tech lead, one product owner; Java, JS/TS, Python stacks; 4–30 years of experience).

## Deductive codes (constructs)

| Code | Definition |
|---|---|
| C1 Usefulness | Perceived usefulness of the mission-based engagement loop for addressing non-blocking debt earlier |
| C2 Autonomy / separation credibility | Perceived autonomy; credibility of the decoupling from release authorization and performance appraisal |
| C3 Fairness | Perceived fairness of team-level (rather than individual) visibility |
| C4 Surveillance | Concerns that the layer enables monitoring of individuals or teams |
| C5 Adoption | Willingness to adopt within the existing sprint workflow; barriers and facilitators |

## Inductive codes (emergent themes)

| Code | Theme (evidence summary) |
|---|---|
| I1 Business-owned backlog | The business controls the backlog, limiting the team's authority to act on quality work ("why focus if I gain nothing?") |
| I2 Deferred non-blocking debt | Non-blocking issues are postponed or ignored until a production bug, a release-score need, or a dedicated initiative |
| I3 AI-era guardrail | The layer is valued as a guardrail amid AI-assisted ("vibe-coded") delivery |
| I4 Purpose paradox | The appraisal separation prompts "if it does not feed evaluation, what is it for?" |
| I5 Hidden-use suspicion | Suspicion that engagement data could later be used for other purposes; requests for explicit, repeated communication and an auditable read-only codebase as proof |
| I6 Inter-team comparison / size asymmetry | Cross-team comparison and team-size asymmetry perceived as unfair (larger teams accumulate more points; lone specialists penalized) |
| I7 Passive monitoring / re-identification | Team-level data could allow passive monitoring or re-identification of individuals; monitoring point-generating actions is itself surveillance |
| I8 Not worse than the gate | Perception that the layer is no more invasive than the existing release-governance engine |
| I9 Team-routed flags mitigate | Sharing anomaly flags with the team itself reduces the sense of surveillance |
| I10 Seamless integration | Adoption hinges on frictionless integration into the development cycle; no release blocking |
| I11 Time / learning-curve barrier | "One more process/tool"; effort and learning curve as adoption barriers |
| I12 Mainframe exclusion | Teams partly working on Cobol/Natural feel excluded from the low-platform scope |
| I13 Symbolic-reward skepticism | Doubt about the motivational pull of purely symbolic rewards |
| I14 Sandbagging vector | Gaming vector: submitting poor code first to harvest remediation points later (requires baseline + revert detection) |

## Finding → revision traceability

| Revision (manuscript §7.3) | Grounding evidence (codes) | Status |
|---|---|---|
| R1 — Cross-station Cosmos views explicitly cooperative and non-ranked | I6; C3/C4 concerns | Confirmed in design |
| R2 — Radio Frequency uses informational, non-controlling language | C5 probes; notification irritation noted "even when informational" (Silent option retained) | Maintained |
| R3 — Anomaly Radar flags routed to the team, not up the hierarchy | I9; C4 | Confirmed in design |
| R4 — Appraisal separation made auditable and explicitly communicated (onboarding briefing; documented, inspectable data boundary; peer-auditable read-only codebase proposed by a participant) | I4, I5 | Added from interviews |
| R5 — Anti-sandbagging baseline (net improvement per station; reverted-fix flags) | I14 | Added from interviews |
| Scope note — coverage beyond low platform (Cobol/Natural) | I12 | Acknowledged as limitation |
| Rollout note — simple, fractioned MVP; seamless integration | I10, I11 | Recommendation for the pilot |

Transcripts are not shared to protect participant confidentiality within an employment relationship; quotations in the manuscript are anonymized and translated.
