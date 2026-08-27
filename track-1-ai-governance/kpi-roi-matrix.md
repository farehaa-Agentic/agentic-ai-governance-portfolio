# KP Vitals — KPI & ROI Measurement Framework

## Purpose

AI transformation should be measured by business and operational outcomes, not simply by whether the AI system functions technically.

This framework defines KPIs for evaluating the performance, governance, cost, adoption, and value of the KP Vitals agentic AI workflow.

## KPI Framework

KPIs are divided into five dimensions:

1. Safety & Quality
2. Operational Performance
3. Human Oversight
4. Cost Efficiency
5. Business Value

## KPI Matrix

| Dimension | KPI | What It Measures | Why It Matters |
|---|---|---|---|
| Safety & Quality | False-negative rate | Abnormal cases incorrectly classified as normal | Identifies potential safety risk |
| Safety & Quality | False-positive rate | Normal cases unnecessarily escalated | Measures alert burden and efficiency |
| Operational | Escalation response time | Time from abnormal finding to appropriate escalation | Measures workflow responsiveness |
| Operational | Successful workflow completion rate | Percentage of runs completed correctly | Measures reliability |
| Human Oversight | Human override rate | Percentage of AI outputs changed by reviewers | Indicates trust, accuracy, and governance health |
| Human Oversight | AI-human disagreement rate | Frequency of disagreement between AI recommendation and reviewer | Helps identify areas requiring improvement |
| Cost | Cost per run | Average cost of one workflow execution | Measures operating efficiency |
| Cost | Cost per successful outcome | Total workflow cost relative to successful outcomes | Connects spending to value |
| Cost | Retry rate | Frequency of repeated workflow/model attempts | Identifies inefficiency |
| Adoption | Human review turnaround time | Time required for required human review | Identifies adoption or workflow bottlenecks |
| Value | Time saved per case | Reduction in manual processing time | Measures productivity benefit |
| Value | Cost avoided / efficiency gain | Operational value created by the workflow | Supports ROI evaluation |

## Leading vs. Lagging Indicators

### Leading Indicators

Leading indicators provide early warning before larger problems appear.

Examples:

- Human override rate
- AI-human disagreement rate
- Retry rate
- Low-confidence output rate
- Cost variance
- Exception frequency

### Lagging Indicators

Lagging indicators show the eventual outcome of workflow performance.

Examples:

- Successful workflow completion rate
- Average processing time
- Cost per successful outcome
- Operational savings
- Quality outcomes
- ROI

## ROI Framework

A conceptual ROI calculation can be expressed as:

**ROI = (Value Generated − Total AI Workflow Cost) / Total AI Workflow Cost × 100**

Value generated may include:

- Staff time saved
- Reduced manual processing
- Reduced rework
- Faster routing and escalation
- Improved workflow capacity
- Avoided operational costs

Total workflow cost should include:

- AI/model usage
- Infrastructure and integrations
- Human review
- Monitoring and governance
- Maintenance
- Exception handling

## Value Principle

A successful AI implementation is not defined by maximum automation.

It is defined by whether the workflow produces measurable value while remaining reliable, governed, cost-conscious, and appropriately supervised.

Therefore, KPI and ROI should be evaluated together with risk and governance metrics.

## Executive View

The key management question is not:

**"How much are we spending on AI?"**

It is:

**"What measurable outcome are we achieving for that spend, at what level of risk?"**

---

**Portfolio Disclaimer:** KP Vitals is a conceptual portfolio use case. Metrics and ROI categories are illustrative and do not represent actual healthcare organization performance or financial data.
