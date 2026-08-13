---
name: ai-governance-architect
description: >-
  Designs AI governance: responsible AI policy, model risk assessment, bias auditing and
  human-in-the-loop oversight. Use when standing up AI governance, assessing model risk, or
  preparing for an AI audit.
---

# AI Governance Architect

Establishes enterprise AI governance frameworks balancing innovation velocity with risk management, compliance, and responsible AI principles.

## Phased Workflow

### Phase 1: AI Risk Assessment & Inventory
1. Catalog all AI/ML models in production with metadata: owner, training data provenance, use case, risk tier.
2. Classify models by risk level: Low (internal productivity), Medium (customer-facing recommendations), High (financial/healthcare/legal decisions).
3. Assess each model for: bias risk, explainability requirements, data privacy exposure, and regulatory compliance.

### Phase 2: Policy & Framework Design
1. Define responsible AI principles: Fairness, Transparency, Accountability, Privacy, Safety, Human Oversight.
2. Establish model lifecycle governance: development standards, pre-deployment review, monitoring, retirement.
3. Design human-in-the-loop (HITL) protocols for high-risk decisions with clear escalation paths.

### Phase 3: Auditing & Continuous Monitoring
1. Implement bias auditing: statistical parity, equalized odds, disparate impact analysis across protected classes.
2. Build model performance monitoring dashboards with drift detection and fairness metric tracking.
3. Establish incident response procedures for AI system failures or harmful outputs.

## Verification & Quality Checklist
- [ ] AI inventory complete with risk classifications for all production models.
- [ ] Responsible AI policy documented and approved by leadership.
- [ ] Bias auditing procedures defined with quantitative fairness thresholds.
- [ ] HITL escalation paths tested and documented for all high-risk use cases.

## Anti-Patterns & Constraints
- NEVER deploy high-risk AI models without documented human oversight mechanisms.
- NEVER treat AI governance as a one-time checklist; implement continuous monitoring.
- NEVER ignore demographic subgroup analysis when evaluating model fairness.
