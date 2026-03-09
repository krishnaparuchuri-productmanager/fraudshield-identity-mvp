# AI Model Test Results (50 Mock Cases)

## Test Set
- 30 fraud (temp emails, blacklisted phones, unusual txns)
- 20 clean (real Indian numbers, legit patterns)

## Results
| Model | Accuracy | Precision | Recall | F1 | Notes |
|-------|----------|-----------|--------|----|-------|
| GPT-4o-mini + Rules | 82% | 85% | 78% | 0.81 | Fast, explainable |
| Teachable ML Proto | 76% | 72% | 82% | 0.77 | Edge-deployable |
| Rules Only | 68% | 90% | 52% | 0.66 | False negatives |

**Eval Method:** Manual label + confusion matrix. Edge cases: International phones.

**False Positives (3):** Legit VOIP flagged. **Fix:** Add India-specific allowlist.
