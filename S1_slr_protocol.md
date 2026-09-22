# S1 — Systematic Literature Review Protocol

Protocol of the SLR used as evidence stream 1 (Section 3 of the manuscript). Method reference: Kitchenham et al., *Evidence-Based Software Engineering and Systematic Reviews* (2015) — the operational elaboration of the Kitchenham–Charters guideline lineage cited in the manuscript; reporting follows PRISMA 2020 (Page et al., 2021). Selection and extraction were managed in the Parsifal platform. **Coverage period: January 2014 – January 2025** (studies published before 2014 excluded by criterion EC0); most recent search execution: 28 January 2025. Review team: the first author as primary reviewer; the second author as supervising reviewer and arbitrator of borderline decisions.

## 1. PICOC

| Element | Definition |
|---|---|
| Population | Software engineers, developers, and software-development teams. Studies whose population consists exclusively of students are retained for RQ1 but flagged as out-of-population for RQ4–RQ5 |
| Intervention | Gamification (Deterding et al., 2011) applied to activities of the software-development life cycle |
| Comparison | Control/comparison group in the same setting not using gamification |
| Outcome | Code-quality indicators (e.g., static-analysis findings) |
| Context | Industrial software development |

## 2. Research questions

- RQ1: Which gamification techniques have been applied to software-development activities?
- RQ2: Which code-quality and lead-time indicators have been used to evaluate them?
- RQ3: How were code-quality indicators turned into motivational signals (instrumentation patterns)?
- RQ4: What effect did gamification have on code-quality indicators?
- RQ5: What effect did gamification have on software-development lead time?

## 3. Search string

The canonical query is composed of six blocks; synonyms within a block are joined by OR, blocks are combined conjunctively.

| Block | Synonyms (OR) |
|---|---|
| B1 — Intervention | "gamification" OR "game elements" OR "gamification techniques" OR "rewards system" |
| B2 — Population | "software engineer" OR "software engineers" OR developer OR developers OR "development team" OR "development teams" OR engineer OR engineers |
| B3 — Outcome (quality) | "software quality" OR "code quality" OR "quality metrics" OR reliability OR "quality assurance" OR "software metrics" OR maintainability OR "software performance" |
| B4 — Methodological | "metrics" OR "indicators" OR measure OR measurement |
| B5 — Comparison | "control group" OR "unmodified system" OR "baseline group" OR "comparison group" OR "conventional method" OR "existing system" OR "reference group" |
| B6 — Lead time | "lead time" OR "development time" OR "delivery time" |

The query was operated as a cumulative lattice of nine levels (Q1 = B1; Q2 = B1∧B2; Q3 = B1∧B3; Q4 = B1∧B3∧B4; Q5 = B1∧B2∧B3; Q6 = B1∧B2∧B3∧B4; Q7 = +B5; Q8 = B1∧B3∧B6; Q9 = all blocks), executed against every base so that a per-base recall/precision decision could be made.

**Per-base export decisions:** ACM Digital Library exported at Q7 (658 records; full-text default search inflates lower levels); EBSCO at Q6 (with Q8/Q9 as lead-time auxiliary subsets); Scopus at Q3–Q6 cumulatively, wrapped in `TITLE-ABS-KEY()`; IEEE Xplore at Q3 (lower-case `and` per IEEE syntax); Ei Compendex at Q4. Periódicos CAPES, Inspec, ScienceDirect, and SpringerLink were used for cross-validation only.

## 4. Selection flow (PRISMA 2020)

| Stage | n |
|---|---|
| Records identified from databases | **1,324** (ACM 658; Scopus 345; IEEE Xplore 190; Ei Compendex 111; EBSCO 20) |
| Duplicates removed before screening | 93 |
| Records screened (title/abstract) | 1,231 |
| Excluded at title/abstract | 1,149 |
| Reports sought for retrieval | 82 (1 not retrieved) |
| Reports assessed at full text | 81 |
| Excluded at full text, with reasons | 30 (E1 not gamification in SE context: 24; E4 duplicate: 2; E2 no software/code quality: 1; empty extraction: 1; other E3/E5–E7: 2) |
| **Included in synthesis** | **51** |

The E-labels above are the categories recorded at full-text screening (as in the PRISMA figure of the underlying review); they aggregate the protocol criteria of §5 as follows: E1 ≈ EC2/EC3, E2 ≈ EC7, E4 = the duplicate/prior-version rule, empty extraction ≈ EC4, and E3/E5–E7 map to the remaining criteria. Per-study reason assignments were not preserved in the final selection log; the aggregate counts are reported as recorded.

## 5. Inclusion and exclusion criteria

**Inclusion:** (i) gamification applied specifically in software-development processes/software engineering; (ii) software engineers, developers, or development teams as primary participants or target audience.

**Exclusion:** EC0 published before 2014; EC1 secondary study; EC2 not software-engineering context; EC3 no gamification intervention; EC4 no empirical data (purely conceptual); EC5 tool paper without evaluation; EC6 educational context without professional relevance; EC7 no software-quality metrics. Duplicates and prior versions of the same study were removed. Languages: English, Portuguese, Spanish.

## 6. Quality assessment (Yes / Partially / No)

- QA1 Conclusion adequately answers the research questions (RQ4)
- QA2 Gamification techniques clearly defined (RQ1)
- QA3 Implementation described in replicable detail (RQ1)
- QA4 Gamification addressed within SE context (all RQs)
- QA5 Control or comparison group present (RQ2–4)
- QA6 Relevant quality metrics explicitly measured and reported (RQ2–3)
- QA7 Impact on development lead time explicitly evaluated (RQ5)
- QA8 Quantitative evidence of lead-time improvement (RQ5)

Aggregate QA tiers over the 51 included studies: 9 high, 29 medium, 13 low/other (see `S1b_studies.md`).

## 7. Data-extraction form (fields)

Bibliographic (citation key, title, authors, year, venue, DOI); study overview (study type, goals, whether conclusions answer RQs); RQ1 (techniques applied, frameworks applied, implementation description); RQ2 (quality metrics measured, metric list, measurement method); RQ3 (gamification-specific process metrics, individual-impact metrics, instrumentation); RQ4 (impact on code quality, measurement, statistical evidence); RQ5 (impact on lead time, lead-time metrics, sustainability discussion); general (control group presence and description, notes).
