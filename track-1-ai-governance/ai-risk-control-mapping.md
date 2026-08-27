# KP Vitals — AI Risk & Control Mapping

## Purpose

This artifact translates identified AI risks in the KP Vitals workflow into practical governance controls, human oversight requirements, and monitoring measures.

The goal is to connect:

**Risk → Potential Impact → Control → Human Oversight → Monitoring**

## Risk & Control Matrix

| Risk | Potential Impact | Governance Control | Human Oversight | Monitoring |
|---|---|---|---|---|
| Incorrect interpretation of vital signs | Patient condition may be incorrectly classified | Validation rules, confidence thresholds, defined clinical parameters | Human review for consequential decisions | Accuracy and human override rate |
| Failure to detect abnormal vitals | Delay in escalation | Exception rules and escalation thresholds | Clinical review for high-risk or uncertain cases | False-negative rate and escalation response time |
| False-positive escalation | Alert fatigue and unnecessary intervention | Threshold calibration and validation | Human confirmation before consequential action | False-positive rate |
| AI uncertainty | Unreliable recommendation or routing | Confidence threshold and fallback path | Route uncertain cases to human review | Low-confidence output rate |
| Inappropriate autonomous action | AI performs an action beyond approved authority | Defined autonomy boundaries and authorization controls | Human approval for high-consequence actions | Unauthorized-action attempts |
| Sensitive-data exposure | Privacy or compliance risk | Minimum-necessary data access, role-based access, logging | Human governance review of access policies | Access and audit logs |
| Workflow or integration failure | Vital information may not reach the correct destination | Error handling, retry limits and exception routing | Escalation to responsible staff when automation fails | Failure and retry rates |
| Excessive AI usage or retries | Unexpected operating cost | Per-run budget limits and retry caps | Governance review when thresholds are exceeded | Cost per run and cost per successful outcome |

## Human-in-the-Loop Principle

Human oversight should increase when:

- The consequence of an incorrect action is high
- The action is difficult to reverse
- AI confidence is low
- Patient safety may be affected
- The workflow encounters an exception or unexpected condition

## Governance Interpretation

Not every workflow step requires the same level of control.

Low-consequence, reversible administrative actions may be automated with monitoring.

High-consequence or difficult-to-reverse actions require stronger controls and may require explicit human authorization.

This creates **risk-based autonomy** rather than treating AI as either fully autonomous or fully human-controlled.

## Key Monitoring Indicators

The governance team should monitor:

- Human override rate
- False-positive rate
- False-negative rate
- Low-confidence output rate
- Workflow failure rate
- Retry frequency
- Escalation response time
- Cost per successful outcome
- Unauthorized-action attempts

These indicators provide early warning that the AI workflow may be operating outside its intended governance boundaries.

---

**Portfolio Disclaimer:** This risk and control mapping is a conceptual portfolio artifact. KP Vitals is not a deployed clinical system, and the controls described here are illustrative rather than clinical guidance.
