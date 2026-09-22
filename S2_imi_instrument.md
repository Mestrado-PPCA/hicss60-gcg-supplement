# S2 — Adapted Intrinsic Motivation Inventory (IMI)

## Instrument

The questionnaire is based on the 22-item short version of the Intrinsic Motivation Inventory as catalogued by McAuley, Duncan and Tammen (1989). Item wording was contextualized to the target activity: every occurrence of *"the activity"* was replaced, in the fielded (Portuguese) version, with *"reduzir débitos técnicos e melhorar a qualidade do código"* ("reducing technical debt and improving code quality"). The questionnaire was administered through Microsoft Forms on the corporate intranet of Banco do Brasil.

**Response scale.** Each item was answered on a **5-point Likert scale** (1 = *not at all true* … 5 = *very true*). Note that this adapts the response format of the original IMI (7-point); the 5-point format was used in the fielded form. Reverse-scored items, marked (R), are inverted (score′ = 6 − score) before subscale means are computed. Subscale scores are the arithmetic means of their constituent items.

## Items (canonical wording; (R) = reverse-scored)

**Interest / Enjoyment (7 items):** 1. I enjoyed doing the activity very much. · 2. The activity was fun to do. · 3. I thought the activity was boring. (R) · 4. The activity did not hold my attention at all. (R) · 5. I would describe the activity as very interesting. · 6. I thought the activity was quite enjoyable. · 7. While doing the activity, I was thinking about how much I enjoyed it.

**Perceived Competence (5 items):** 8. I think I am pretty good at the activity. · 9. I think I did pretty well at the activity, compared to other people. · 10. After working at the activity for a while, I felt pretty competent. · 11. I am satisfied with my performance at the activity. · 12. I was pretty skilled at the activity.

**Perceived Choice (5 items):** 13. I believe I had some choice about doing the activity. · 14. I felt like it was not my own choice to do the activity. (R) · 15. I did not really have a choice about doing the activity. (R) · 16. I felt like I had to do the activity. (R) · 17. I did the activity because I had no choice. (R)

**Pressure / Tension (5 items):** 18. I did not feel nervous at all while doing the activity. (R) · 19. I felt very tense while doing the activity. · 20. I was very relaxed in doing the activity. (R) · 21. I was anxious while doing the activity. · 22. I felt pressured while doing the activity.

## Fielded item order and per-item means

The fielded form presented the items in shuffled order (P1–P22). Mapping of fielded positions to subscales, with per-item means as recorded in the analysis workbook (reverse-scored items inverted prior to aggregation):

| Subscale | Fielded items (mean) | Subscale mean |
|---|---|---|
| Interest / Enjoyment | P1 (3.521), P5 (3.854), P8 (2.896), P10 (3.104), P14 (3.667), P17 (3.396), P20 (2.958) | 3.342 |
| Perceived Competence | P4 (3.542), P7 (3.458), P12 (3.875), P16 (3.625), P22 (3.667) | 3.633* |
| Perceived Choice | P3 (3.167), P11 (2.917), P15 (3.125), P19 (2.458), P21 (3.292) | 2.992 |
| Pressure / Tension | P2 (2.750), P6 (2.562), P9 (3.271), P13 (2.667), P18 (2.625) | 2.775 |

\* The manuscript reports 3.63 for Perceived Competence, recomputed from the per-item means above. The original analysis records reported 3.585 (rounded 3.59 in the submitted version); because the respondent-level export was not retained, that figure could not be re-verified, and the recomputable value is reported instead.

## Sampling plan and fielding summary

| Parameter | Value |
|---|---|
| Population (active low-platform developers, Nov 2023 – Apr 2024) | 2,563 |
| Sample-size formula | Krejcie & Morgan (1970), p = 0.9, e = 0.07, Z = 1.645 (90% confidence) |
| Minimum required responses | 49 |
| Teams invited (low-platform) | 10 teams, 117 developers (4.6% of the population; 18.25% of the deployments in the reference period) |
| Distribution channel | Microsoft Forms via corporate intranet |
| Field period | 11 days |
| Valid responses | 53 (45.3% of invited developers; ≈2% of the population) |
| Reliability (adapted instrument, all 22 items) | Cronbach's α = 0.692 |

Participation was voluntary and anonymous; no incentives were offered; respondents were informed in the form of the study's purpose and the research use of the data. The respondent-level export (53 × 22) was not retained, so per-subscale reliability coefficients cannot be reported; the instrument-level Cronbach's alpha (0.692) is reported in the manuscript.
