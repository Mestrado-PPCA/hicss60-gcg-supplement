# S4 — Structured Interview Script (Formative Evaluation)

English translation of the fielded script (originally administered in Portuguese). Structured interviews with guided demonstration; design-stage formative evaluation (plausibility and artifact fit, not effectiveness).

## Sampling and logistics

- **Sampling:** purposive, from the 10 low-platform teams that participated in the diagnostic survey, targeting coverage of roles (developers, tech leads, managers), stacks (Java, JavaScript/TypeScript, Python), and high/low issue-inventory teams. Target of ~12 interviews within the thematic-saturation range for homogeneous populations (Guest, Bunce & Johnson 2006; Hennink & Kaiser 2022), with a stopping rule of three consecutive interviews without new themes after the ninth. Eleven valid interviews were obtained; no new themes emerged in the final interviews.
- **Duration:** 35–45 minutes; individual; remote or in person; audio recorded only upon consent.
- **Materials:** working demonstration of Launch Center (Cosmos, mission list, Hangar, Constellations panel, Shield Mode, Radio Frequency).

## Consent preamble (read at the start of every interview)

The interviewer explained: (i) the purpose of the evaluation; (ii) the data collected and their use (research); (iii) the **complete decoupling of all research data from any performance appraisal**; (iv) anonymity; (v) the right to stop at any moment without consequence.

## Block 0 — Profile (~5 min)

1. How long have you worked in software development? Main stack (Java / JS-TS / Python)?
2. What is your role in the team (developer, tech lead, manager)?
3. In one sentence: how would you describe your team's current relationship with code quality?

## Block 1 — Current context (~5 min)

4. How does your team currently handle SonarQube issues that do **not** block a release (Info/Minor/Major)? Are they addressed? When?
5. How does the release-governance engine influence (or not) quality effort during the sprint?
6. What typically makes a team **postpone** non-blocking quality work?

*After Block 1, the guided demonstration (~5 min): the mission loop generated from the SonarQube backlog, the three orbits, Stellars/Hangar, the Cosmos panel (team view and cooperative cross-station view), Campaigns, Certifications, Constellations, and the protection mechanisms (Shield Mode, Radio Frequency, Anomaly Radar). The separation from the release engine is reaffirmed.*

## Block 2 — Constructs (anchor question + probes; 1–5 perception rating per construct)

**C1. Perceived usefulness of the engagement loop.** 7. Would the loop "mission → pipeline-verified action → recognition in the Cosmos" help your team address non-blocking debt earlier? Why?
*Probes:* Do backlog-generated missions look actionable and relevant? Do the three effort-based orbits make sense versus severity alone? What would make a mission "good"? — **Rating (1–5)**

**C2. Autonomy and credibility of the appraisal separation.** 8. Launch Center is declared **decoupled** from the release engine and from performance appraisal. How credible is that to you? What would increase that trust?
*Probes:* Do voluntary participation and Shield Mode preserve team autonomy? Do purely symbolic rewards (no monetary value, no release effect) affect your willingness? — **Rating (1–5)**

**C3. Fairness of team-level visibility.** 9. The artifact avoids individual rankings and uses **team-level** visibility. Does that seem fair given how quality work happens in your team?
*Probes:* The cross-station view in the Cosmos is cooperative and non-ranked — does that avoid unfair comparison between teams? Do Constellations (3–5 stations cooperating) help or create pressure? — **Rating (1–5)**

**C4. Surveillance concerns.** 10. Could anything in Launch Center be perceived as **monitoring/surveillance**? What?
*Probes:* Anomaly Radar flags gaming patterns and its flags are **reviewed with the team itself**, not above it — does that change your perception? Who should see the team's data? — **Rating (1–5)**

**C5. Adoption willingness and workflow fit.** 11. Would your team adopt Launch Center in the sprint routine? What would be a barrier or a facilitator?
*Probes:* Does the space-exploration narrative feel **meaningful** or **childish** in a professional context? Does Radio Frequency (Silent/Daily/Live, informational non-coercive language) solve notification overload? — **Rating (1–5)**

## Block 3 — Closing (~5 min)

12. If you could **change one thing** in Launch Center before a pilot, what would it be?
13. Which mechanism is the **most valuable**, and which is the **riskiest**, for your context?
14. Anything important we did not ask?

## Construct → mechanism → SLR risk map (analysis aid)

| Construct | Mechanisms probed | Failure mode from the SLR |
|---|---|---|
| C1 Usefulness | Missions (3 orbits), Cosmos, Campaigns | Late-stage gate without continuous engagement |
| C2 Autonomy/separation | Optional participation, Shield Mode, symbolic rewards | Coercion; gamification as managerial pressure |
| C3 Fairness | Team-level visibility, non-ranked Cosmos, Constellations | Unfair individual comparison; inter-team inequality |
| C4 Surveillance | Anomaly Radar (team-routed flags), data use | Perceived surveillance |
| C5 Adoption | Narrative, Radio Frequency, sprint fit | Novelty decay; notification fatigue |
