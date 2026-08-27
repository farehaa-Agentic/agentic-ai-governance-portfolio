# KP Vitals — Human-in-the-Loop Decision Framework

## Purpose

This framework determines where AI-supported workflow actions may proceed automatically and where human review or authorization should be required.

The objective is not to place a human checkpoint after every AI action. Human oversight should be proportional to risk.

## Decision Factors

Four factors determine the appropriate level of autonomy:

1. **Consequence** — What happens if the decision is wrong?
2. **Reversibility** — Can the action easily be undone?
3. **Confidence** — How certain is the system?
4. **Exception Status** — Is the workflow operating within expected conditions?

## Decision Framework

| Situation | AI Role | Human Role |
|---|---|---|
| Low-risk, routine, reversible action | Automate | Monitor |
| Normal workflow classification | Recommend / route | Periodic oversight |
| Low-confidence result | Stop or route | Review |
| Workflow exception | Escalate | Resolve |
| Abnormal or potentially consequential result | Analyze and recommend | Validate |
| High-consequence action | Support decision | Authorize |

## KP Vitals Application

For KP Vitals, AI may support:

- Initial interpretation
- Classification
- Routing
- Pattern identification
- Escalation recommendations

Human oversight becomes stronger when patient safety may be affected, system confidence falls, or an action becomes difficult to reverse.

## Governance Rule

**Higher consequence + lower reversibility + lower confidence = stronger human oversight.**

This creates risk-based autonomy rather than unrestricted autonomy.

## Monitoring

Human-in-the-loop effectiveness should be monitored using:

- Human override rate
- AI/human disagreement rate
- Low-confidence escalation rate
- Review turnaround time
- Exception frequency

A rising override rate may indicate model, workflow, threshold, or governance problems.

---

**Portfolio Disclaimer:** KP Vitals is a conceptual portfolio use case. This framework demonstrates governance design and does not constitute clinical guidance.
