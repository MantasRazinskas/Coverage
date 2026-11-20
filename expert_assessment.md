# Expert assessment

Expert assessments of the case study "Eliciting Requirements from Heterogeneous Sources Using LLMs: A Case Study" (M. Ražinskas, L. Čeponienė), reported for each expert.

## Coverage

Four experts assessed every generated set independently, without seeing the model names. Tables IV to VII of the paper report the means of the four experts.

### Project 1: awards initiative website (35 reference stories)

| Model | Generated | Expert | Covered | Not covered | Additional | Recall |
|---|---|---|---|---|---|---|
| Claude Opus 4.8 | 38 | 1 | 33 | 2 | 5 | 0.943 |
|  |  | 2 | 32 | 3 | 6 | 0.914 |
|  |  | 3 | 32 | 3 | 6 | 0.914 |
|  |  | 4 | 32 | 3 | 6 | 0.914 |
| | | **Mean** | **32.25** | **2.75** | **5.75** | **0.921** |
| Claude Sonnet 4.6 | 46 | 1 | 31 | 4 | 15 | 0.886 |
|  |  | 2 | 31 | 4 | 15 | 0.886 |
|  |  | 3 | 30 | 5 | 16 | 0.857 |
|  |  | 4 | 30 | 5 | 16 | 0.857 |
| | | **Mean** | **30.50** | **4.50** | **15.50** | **0.871** |
| Gemini 2.5 Flash | 39 | 1 | 29 | 6 | 10 | 0.829 |
|  |  | 2 | 28 | 7 | 11 | 0.800 |
|  |  | 3 | 28 | 7 | 11 | 0.800 |
|  |  | 4 | 27 | 8 | 12 | 0.771 |
| | | **Mean** | **28.00** | **7.00** | **11.00** | **0.800** |
| GPT-5 | 40 | 1 | 31 | 4 | 9 | 0.886 |
|  |  | 2 | 30 | 5 | 10 | 0.857 |
|  |  | 3 | 30 | 5 | 10 | 0.857 |
|  |  | 4 | 30 | 5 | 10 | 0.857 |
| | | **Mean** | **30.25** | **4.75** | **9.75** | **0.864** |
| GPT-4o | 45 | 1 | 28 | 7 | 17 | 0.800 |
|  |  | 2 | 26 | 9 | 19 | 0.743 |
|  |  | 3 | 26 | 9 | 19 | 0.743 |
|  |  | 4 | 24 | 11 | 21 | 0.686 |
| | | **Mean** | **26.00** | **9.00** | **19.00** | **0.743** |

Agreement between the experts on the reference-story decisions (covered or not covered):

| Model | Same decision by all four experts | Mean agreement of a pair of experts | Recall range |
|---|---|---|---|
| Claude Opus 4.8 | 34 of 35 (97.1%) | 98.6% | 0.914–0.943 |
| Claude Sonnet 4.6 | 30 of 35 (85.7%) | 92.4% | 0.857–0.886 |
| Gemini 2.5 Flash | 29 of 35 (82.9%) | 91.4% | 0.771–0.829 |
| GPT-5 | 30 of 35 (85.7%) | 92.9% | 0.857–0.886 |
| GPT-4o | 23 of 35 (65.7%) | 82.9% | 0.686–0.800 |

### Project 2: shooting range reservation and club management system (67 reference stories)

| Model | Generated | Expert | Covered | Not covered | Additional | Recall |
|---|---|---|---|---|---|---|
| Claude Opus 4.8 | 88 | 1 | 64 | 3 | 24 | 0.955 |
|  |  | 2 | 64 | 3 | 24 | 0.955 |
|  |  | 3 | 64 | 3 | 24 | 0.955 |
|  |  | 4 | 63 | 4 | 25 | 0.940 |
| | | **Mean** | **63.75** | **3.25** | **24.25** | **0.951** |
| Claude Sonnet 4.6 | 84 | 1 | 58 | 9 | 26 | 0.866 |
|  |  | 2 | 57 | 10 | 27 | 0.851 |
|  |  | 3 | 57 | 10 | 27 | 0.851 |
|  |  | 4 | 56 | 11 | 28 | 0.836 |
| | | **Mean** | **57.00** | **10.00** | **27.00** | **0.851** |
| Gemini 2.5 Flash | 72 | 1 | 54 | 13 | 18 | 0.806 |
|  |  | 2 | 51 | 16 | 21 | 0.761 |
|  |  | 3 | 51 | 16 | 21 | 0.761 |
|  |  | 4 | 48 | 19 | 24 | 0.716 |
| | | **Mean** | **51.00** | **16.00** | **21.00** | **0.761** |
| GPT-5 | 130 | 1 | 58 | 9 | 72 | 0.866 |
|  |  | 2 | 56 | 11 | 74 | 0.836 |
|  |  | 3 | 56 | 11 | 74 | 0.836 |
|  |  | 4 | 55 | 12 | 75 | 0.821 |
| | | **Mean** | **56.25** | **10.75** | **73.75** | **0.840** |
| GPT-4o | 81 | 1 | 50 | 17 | 31 | 0.746 |
|  |  | 2 | 47 | 20 | 34 | 0.701 |
|  |  | 3 | 46 | 21 | 35 | 0.687 |
|  |  | 4 | 43 | 24 | 38 | 0.642 |
| | | **Mean** | **46.50** | **20.50** | **34.50** | **0.694** |

Agreement between the experts on the reference-story decisions (covered or not covered):

| Model | Same decision by all four experts | Mean agreement of a pair of experts | Recall range |
|---|---|---|---|
| Claude Opus 4.8 | 66 of 67 (98.5%) | 99.3% | 0.940–0.955 |
| Claude Sonnet 4.6 | 61 of 67 (91.0%) | 95.5% | 0.836–0.866 |
| Gemini 2.5 Flash | 45 of 67 (67.2%) | 83.6% | 0.716–0.806 |
| GPT-5 | 56 of 67 (83.6%) | 91.8% | 0.821–0.866 |
| GPT-4o | 40 of 67 (59.7%) | 79.6% | 0.642–0.746 |

Precision of a set is (generated − additional) / generated and F1 the harmonic mean of recall and precision, both computed from the mean counts (Tables VI and VII of the paper).

## Additional stories of the selected set

The additional stories of the Claude Opus 4.8 sets were classified independently by two authors (A1, A2) as useful or not useful; the disagreements were then discussed and an agreed classification recorded.

| Group | Meaning |
|---|---|
| Useful | Absent from the reference set and worth adding to the backlog, reworded if needed |
| Not useful | Restates or bundles content already covered, or is not needed by the project |

| Group | P1 A1 | P1 A2 | P1 agreed | P2 A1 | P2 A2 | P2 agreed | Total agreed |
|---|---|---|---|---|---|---|---|
| Useful | 4 | 4 | 4 | 6 | 3 | 4 | 8 |
| Not useful | 2 | 2 | 2 | 18 | 21 | 20 | 22 |
| Total | 6 | 6 | 6 | 24 | 24 | 24 | 30 |

| Agreement of A1 and A2 | Project 1 | Project 2 | Both |
|---|---|---|---|
| Same classification | 6 of 6 | 21 of 24 | 27 of 30 (90%) |

A1 and A2 give the independent classifications made before the discussion; Agreed gives the classification recorded after it.

Per story:

| Project | Story | A1 | A2 | Agreed |
|---|---|---|---|---|
| 1 | 1 | Useful | Useful | Useful |
| 1 | 2 | Useful | Useful | Useful |
| 1 | 3 | Not useful | Not useful | Not useful |
| 1 | 4 | Useful | Useful | Useful |
| 1 | 5 | Useful | Useful | Useful |
| 1 | 6 | Not useful | Not useful | Not useful |
| 2 | 1 | Useful | Useful | Useful |
| 2 | 2 | Useful | Useful | Useful |
| 2 | 3 | Not useful | Not useful | Not useful |
| 2 | 4 | Not useful | Not useful | Not useful |
| 2 | 5 | Not useful | Not useful | Not useful |
| 2 | 6 | Not useful | Not useful | Not useful |
| 2 | 7 | Not useful | Not useful | Not useful |
| 2 | 8 | Not useful | Not useful | Not useful |
| 2 | 9 | Not useful | Not useful | Not useful |
| 2 | 10 | Not useful | Not useful | Not useful |
| 2 | 11 | Useful | Useful | Useful |
| 2 | 12 | Not useful | Not useful | Not useful |
| 2 | 13 | Not useful | Not useful | Not useful |
| 2 | 14 | Not useful | Not useful | Not useful |
| 2 | 15 | Not useful | Not useful | Not useful |
| 2 | 16 | Useful | Not useful | Not useful |
| 2 | 17 | Not useful | Not useful | Not useful |
| 2 | 18 | Not useful | Not useful | Not useful |
| 2 | 19 | Useful | Not useful | Useful |
| 2 | 20 | Not useful | Not useful | Not useful |
| 2 | 21 | Not useful | Not useful | Not useful |
| 2 | 22 | Not useful | Not useful | Not useful |
| 2 | 23 | Useful | Not useful | Not useful |
| 2 | 24 | Not useful | Not useful | Not useful |
