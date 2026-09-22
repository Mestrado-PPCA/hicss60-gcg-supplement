# S6 — Supplementary Statistics

Original analyses were conducted in RStudio; the values below were verified/recomputed for this package (Python 3, exact formulas noted). n = 53 for the survey; n = 11 for the interviews.

## 1. IMI subscale correlation matrix (Pearson, n = 53)

Significance from t = r·√(n−2)/√(1−r²), df = 51, two-tailed; 95% CIs via Fisher z-transformation. These p-values and intervals are computed from the reported correlation coefficients and n = 53 alone; they do not require the respondent-level export (which was not retained).

| Pair | r | t(51) | p | 95% CI |
|---|---|---|---|---|
| Interest × Choice | +0.660 | +6.27 | < .001 | [+0.47, +0.79] |
| Interest × Competence | +0.374 | +2.88 | .006 | [+0.12, +0.59] |
| Choice × Competence | +0.363 | +2.78 | .008 | [+0.10, +0.58] |
| Pressure × Competence | −0.337 | −2.56 | .014 | [−0.56, −0.07] |
| Pressure × Interest | −0.430 | −3.40 | .001 | [−0.63, −0.18] |
| Pressure × Choice | −0.528 | −4.44 | < .001 | [−0.70, −0.30] |

Full matrix form:

| | Competence | Interest | Choice | Pressure |
|---|---|---|---|---|
| Competence | 1 | | | |
| Interest | 0.374 | 1 | | |
| Choice | 0.363 | 0.660 | 1 | |
| Pressure | −0.337 | −0.430 | −0.528 | 1 |

The three positive subscales are mutually positively correlated while pressure/tension correlates negatively with all three — the pattern that motivated the design decision to avoid pressure-based mechanics.

**Reliability.** Cronbach's α (all 22 items) = 0.692. The respondent-level export (53 × 22) was not retained, so per-subscale coefficients cannot be computed.

## 2. Interview perception scales (n = 11, 1–5), with dispersion

| Construct | Mean | Median | SD |
|---|---|---|---|
| Fairness of team-level visibility | 4.18 | 5 | 1.40 |
| Perceived usefulness (engagement loop) | 3.82 | 4 | 1.08 |
| Appraisal-separation credibility | 3.55 | 4 | 0.93 |
| Adoption willingness | 3.55 | 4 | 1.04 |
| Absence of surveillance | 3.45 | 3 | 1.29 |

Rating distributions (value × count): fairness 5×7, 4×2, 2×1, 1×1 · usefulness 5×3, 4×5, 3×1, 2×2 · separation credibility 5×1, 4×6, 3×2, 2×2 · adoption 5×2, 4×4, 3×3, 2×2 · absence of surveillance 5×3, 4×2, 3×4, 2×1, 1×1. SDs are sample standard deviations (n−1). No inferential claim is made at this sample size.

## 3. Octalysis per-drive means and dispersion (scale 1–5)

| Core drive | Mean | SD | Entries (n) |
|---|---|---|---|
| Development & Accomplishment | 3.19 | 1.36 | 64 |
| Empowerment of Creativity & Feedback | 2.95 | 1.22 | 44 |
| Epic Meaning & Calling | 2.88 | 1.34 | 32 |
| Social Influence & Relatedness | 2.73 | 1.25 | 52 |
| Unpredictability & Curiosity | 2.57 | 1.48 | 44 |
| Scarcity & Impatience | 2.22 | 1.20 | 36 |
| Loss & Avoidance | 2.10 | 1.28 | 40 |
| Ownership & Possession | 1.95 | 1.29 | 44 |

Means recomputed from the consolidated judges' workbook and matching the manuscript's reported values exactly; SDs computed over the recorded rating entries. Inter-rater agreement statistics are **not computable** for this assessment (rater-aligned disaggregation was not preserved) and are not claimed — see `S3_octalysis_procedure.md` for the full transparency statement.

## 4. Documented correction

- Perceived Competence subscale mean: the manuscript reports **3.63**, recomputed from the per-item means in `S2_imi_instrument.md`. The original analysis records reported 3.585 (the value in the submitted version); because the respondent-level export was not retained, that figure could not be re-verified, and the recomputable value is reported instead.
