# KP Vitals — AI Governance Assessment

## 1. Use Case Overview

KP Vitals is a portfolio healthcare workflow designed to explore how AI and agentic automation could support the processing, interpretation, and routing of patient vital-sign information.

The purpose of this assessment is not to evaluate a deployed clinical AI system. It demonstrates how AI governance principles can be applied during the design of an AI-enabled healthcare workflow.

## 2. Governance Objective

The governance objective is to determine:

- What decisions may be automated
- What decisions require human oversight
- Where patient-safety and operational risks exist
- What controls should be implemented
- How AI actions should be monitored and audited
- How performance, cost, and value should be measured

## 3. Governance Framework

The assessment uses the NIST AI Risk Management Framework as the primary organizing framework:

**GOVERN → MAP → MEASURE → MANAGE**

Supporting concepts will also be drawn from:

- NIST AI 600-1
- ISO/IEC 42001
- OWASP Top 10 for LLM Applications
- Human-in-the-Loop control principles

## 4. GOVERN — Establish Accountability

Key governance questions include:

- Who owns the AI-enabled workflow?
- Who is accountable for clinical decisions?
- Which AI actions require human authorization?
- What actions must be logged?
- What escalation procedures apply when the AI system fails or produces uncertain results?

The workflow should maintain clear human accountability even when portions of the process operate autonomously.

## 5. MAP — Understand Context and Risk

The workflow may process patient vital-sign information and therefore operates in a potentially high-consequence healthcare context.

Key risks include:

- Incorrect interpretation of vital signs
- Failure to recognize an abnormal condition
- Incorrect escalation or routing
- Inappropriate autonomous action
- Privacy or sensitive-data exposure
- Over-reliance on AI recommendations

The consequences of an AI error must be considered when deciding where human review is required.

## 6. MEASURE — Evaluate Performance and Risk

Potential measures include:

- AI output accuracy
- Human override rate
- False-positive escalation rate
- False-negative escalation rate
- Workflow failure rate
- Escalation response time
- Cost per successful workflow outcome

These measures provide evidence for determining whether the workflow is operating within acceptable risk and performance boundaries.

## 7. MANAGE — Apply Controls

Potential controls include:

- Human review before consequential clinical actions
- Confidence thresholds
- Role-based access
- Audit logging
- Exception routing
- Escalation procedures
- Run-budget and cost thresholds
- Monitoring of AI performance and human overrides

Higher-consequence or difficult-to-reverse actions should receive stronger controls and human oversight.

## 8. Governance Principle

The central design principle for KP Vitals is:

> Greater consequence + lower reversibility + greater uncertainty = stronger human oversight.

The objective is not maximum AI autonomy. The objective is **appropriate autonomy within defined governance boundaries**.

## 9. Portfolio Outcome

This assessment demonstrates how an AI transformation professional can translate governance frameworks into workflow-level decisions involving risk, accountability, human oversight, measurement, and operational controls.

---

**Portfolio Disclaimer:** KP Vitals is a conceptual portfolio use case created for learning and professional demonstration. It is not a deployed clinical system and does not represent proprietary healthcare organization architecture or clinical guidance.
