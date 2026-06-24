# Hypothesis Test Notes

## Objective

Evaluate whether the Treatment group performs better than the Control group in terms of paid conversion.

---

## Primary Metric

Paid Conversion Rate

---

## Null Hypothesis (H0)

There is no statistically significant difference in the paid conversion rate between the Control group and the Treatment group.

---

## Alternative Hypothesis (H1)

The Treatment group has a statistically significant improvement in paid conversion rate compared to the Control group.

---

## Experiment Design

- Type: A/B Experiment
- Groups:
  - Control
  - Treatment
- Success Metric:
  - Paid Conversion Rate

---

## Guardrail Metrics

- Refund Rate
- Support Ticket Rate
- Engagement Score
- Days to Convert

---

## Statistical Test

Recommended Test:
- Two-Proportion Z-Test (for conversion rate)

Significance Level:
- α = 0.05

Decision Rule:
- p-value < 0.05 → Reject H0
- p-value ≥ 0.05 → Fail to Reject H0

---

## Interpretation

Compare the paid conversion rate of the Treatment group against the Control group.

If the Treatment group shows a statistically significant improvement without negatively affecting guardrail metrics, the Treatment should be recommended for rollout.

---

## Business Conclusion

The final rollout decision should consider both the primary success metric and guardrail metrics rather than conversion alone.