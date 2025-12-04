---
layout: default
title: "Chapter 5: Investment Lifecycle"
parent: "Part II: Framework"
nav_order: 5
permalink: /chapters/05-investment-lifecycle/
---

# Chapter 5: Investment Lifecycle

## Learning Objectives

After completing this chapter, you will be able to:
- Understand the stage-gate investment process
- Apply consistent criteria at each stage gate
- Navigate the investment approval process
- Manage investments through their lifecycle
- Track benefits from initiation through realization

---

## Stage-Gate Investment Process

### Overview

The stage-gate investment process provides disciplined governance for IT investments. Each gate represents a decision point where investments are evaluated against defined criteria before proceeding to the next stage.

```
┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐   ┌─────────┐
│  IDEA   │──▶│ BUSINESS│──▶│ DETAILED│──▶│EXECUTION│──▶│ GO-LIVE │──▶│ PROJECT │──▶│BENEFITS │
│         │   │  CASE   │   │ PLANNING│   │ APPROVAL│   │ APPROVAL│   │ CLOSURE │   │REALIZED │
│ Gate 1  │   │ Gate 2  │   │ Gate 3  │   │ Gate 4  │   │ Gate 5  │   │ Gate 6  │   │ Gate 7  │
└─────────┘   └─────────┘   └─────────┘   └─────────┘   └─────────┘   └─────────┘   └─────────┘
     │             │             │             │             │             │             │
     ▼             ▼             ▼             ▼             ▼             ▼             ▼
   Reject       Reject        Reject        Delay        Delay         Hold        Remediate
   or Defer     or Defer      or Cancel     or Cancel    or Cancel     Benefits    Benefits
```

---

## Gate 1: Idea Submission

### Purpose
Screen and qualify new investment ideas for further evaluation.

### Entry Criteria
- Investment idea submitted
- Business need identified
- Initial sponsor identified

### Required Deliverables

| Deliverable | Description |
|-------------|-------------|
| **Concept Paper** | 1-2 page summary of idea |
| **Business Problem** | Description of problem/opportunity |
| **Proposed Solution** | High-level solution approach |
| **Initial Estimate** | Rough order of magnitude (ROM) |
| **Strategic Alignment** | Link to strategic objectives |

### Gate Review

| Criterion | Pass/Fail |
|-----------|-----------|
| Aligned to strategy | Required |
| Clear business need | Required |
| Viable solution approach | Required |
| Within investment parameters | Required |
| Sponsor commitment | Required |

### Decision Options
- **Advance to Gate 2:** Develop business case
- **Defer:** Hold for future consideration
- **Reject:** Not aligned, not viable

---

## Gate 2: Business Case Development

### Purpose
Evaluate detailed business case to approve planning investment.

### Entry Criteria
- Gate 1 approval
- Business sponsor assigned
- Project manager assigned

### Required Deliverables

| Deliverable | Description |
|-------------|-------------|
| **Full Business Case** | Comprehensive justification |
| **Financial Analysis** | NPV, ROI, payback period |
| **Benefits Statement** | Defined and measurable benefits |
| **Risk Assessment** | Key risks and mitigations |
| **Alternative Analysis** | Options considered |
| **High-Level Plan** | Timeline and major milestones |
| **Resource Estimate** | Budget and resource requirements |

### Financial Analysis Requirements

| Metric | Required | Threshold |
|--------|----------|-----------|
| **Net Present Value (NPV)** | Yes | > $0 |
| **Return on Investment (ROI)** | Yes | > hurdle rate |
| **Payback Period** | Yes | < 3 years |
| **Internal Rate of Return (IRR)** | Recommended | > cost of capital |

### Scoring

Apply standard scoring criteria:
- Business Value Score (0-5)
- Risk Score (0-5)
- Cost Score (0-5)
- Calculate Priority Score

### Decision Options
- **Approve for Planning:** Allocate planning resources
- **Defer:** Hold for next planning cycle
- **Reject:** Business case not justified

---

## Gate 3: Detailed Planning

### Purpose
Approve detailed plan and authorize execution budget.

### Entry Criteria
- Gate 2 approval
- Business case approved
- Planning resources allocated

### Required Deliverables

| Deliverable | Description |
|-------------|-------------|
| **Detailed Project Plan** | Work breakdown, schedule, milestones |
| **Detailed Budget** | Line-item budget with contingency |
| **Resource Plan** | Named resources, skills, timing |
| **Risk Mitigation Plan** | Detailed risk responses |
| **Benefits Realization Plan** | How benefits will be tracked |
| **Change Management Plan** | Organizational change approach |
| **Communication Plan** | Stakeholder communication |

### Plan Quality Criteria

| Criterion | Requirement |
|-----------|-------------|
| Schedule confidence | ≥80% probability of success |
| Budget accuracy | ±10% of final estimate |
| Resource confirmed | Named resources or commitments |
| Risks managed | Top 10 risks with mitigations |
| Dependencies documented | All external dependencies identified |

### Decision Options
- **Approve to Execute:** Authorize full budget and resources
- **Revise Plan:** Address gaps before approval
- **Cancel:** Terminate initiative

---

## Gate 4: Execution Approval

### Purpose
Final readiness check before starting execution.

### Entry Criteria
- Gate 3 approval
- Detailed plan approved
- Budget allocated

### Readiness Checklist

| Item | Status |
|------|--------|
| Budget confirmed and available | ✓ |
| Resources assigned and available | ✓ |
| Contracts executed (if needed) | ✓ |
| Risks managed, no blockers | ✓ |
| Kickoff scheduled | ✓ |
| Stakeholders informed | ✓ |
| Governance established | ✓ |

### Decision Options
- **Start Execution:** Begin project work
- **Delay:** Address readiness gaps
- **Cancel:** Circumstances changed

---

## Gate 5: Go-Live Approval

### Purpose
Authorize deployment to production.

### Entry Criteria
- Development complete
- Testing complete
- Deployment plan approved

### Go-Live Checklist

| Category | Items |
|----------|-------|
| **Quality** | Testing complete, defects resolved |
| **Readiness** | Training complete, support ready |
| **Risk** | Go-live risks acceptable |
| **Approval** | Business sign-off obtained |
| **Support** | Operations ready to support |
| **Rollback** | Rollback plan tested |

### Decision Options
- **Deploy:** Proceed with go-live
- **Delay:** Address readiness issues
- **Cancel:** Project terminated

---

## Gate 6: Project Closure

### Purpose
Formally close the project and transition to operations.

### Entry Criteria
- Deployment complete
- Stabilization period passed
- Operations handover complete

### Closure Deliverables

| Deliverable | Description |
|-------------|-------------|
| **Final Project Report** | Summary of outcomes vs. plan |
| **Lessons Learned** | Document successes and failures |
| **Documentation** | Complete technical and operational docs |
| **Operations Handover** | Formal handover to operations |
| **Benefits Baseline** | Initial benefits measurement |
| **Archive** | Project artifacts archived |

### Closure Criteria

| Criterion | Requirement |
|-----------|-------------|
| Deliverables complete | All scope delivered or change approved |
| Documentation complete | Meets organizational standards |
| Handover accepted | Operations accepts support responsibility |
| Financials closed | Budget reconciled, POs closed |
| Resources released | Team members transitioned |
| Lessons learned captured | Document shared with PMO |

### Decision Options
- **Close Project:** Project formally closed
- **Extend:** Additional work needed before closure

---

## Gate 7: Benefits Realization

### Purpose
Verify that expected benefits are being realized.

### Entry Criteria
- Project closed
- Benefits tracking period elapsed (typically 6-12 months)
- Benefits data collected

### Benefits Review

| Benefit | Baseline | Target | Actual | Variance |
|---------|----------|--------|--------|----------|
| Revenue increase | $X | $Y | $Z | ±% |
| Cost savings | $X | $Y | $Z | ±% |
| Productivity | X FTE | Y FTE | Z FTE | ±% |
| Quality | X% | Y% | Z% | ±% |

### Benefits Assessment

| Outcome | Criteria | Action |
|---------|----------|--------|
| **Benefits Realized** | Actual ≥ 85% of target | Close benefits tracking |
| **Partial Benefits** | Actual 50-85% of target | Remediation plan |
| **Benefits Shortfall** | Actual < 50% of target | Root cause analysis, escalate |

### Decision Options
- **Benefits Realized:** Close benefits tracking
- **Remediate:** Implement corrective actions
- **Write Off:** Benefits unattainable, document lessons

---

## Fast-Track Process

### When to Fast-Track

| Criteria | Threshold |
|----------|-----------|
| Total investment | < $100K |
| Duration | < 3 months |
| Risk level | Low |
| Strategic alignment | Confirmed |
| Sponsor pre-approved | Yes |

### Fast-Track Process

Combine Gates 1-3 into single review:
1. Submit combined concept and business case
2. Investment Review Board review
3. Approval to execute or reject
4. Gates 4-7 still apply

---

## Lifecycle Metrics

### Stage-Gate Metrics

| Metric | Target | Description |
|--------|--------|-------------|
| Gate cycle time | < 2 weeks | Time between gates |
| Pass rate | > 70% | % advancing through gate |
| Rework rate | < 20% | % sent back for revision |
| Benefits realization | ≥ 85% | Actual vs. planned benefits |

### Investment Performance

| Metric | Target | Description |
|--------|--------|-------------|
| On-time delivery | ≥ 85% | Delivered on schedule |
| On-budget delivery | ≥ 90% | Within approved budget |
| Scope delivery | ≥ 95% | Planned scope delivered |
| Stakeholder satisfaction | ≥ 4.0/5.0 | Sponsor satisfaction |

---

## Key Takeaways

- **Stage-gate process** provides disciplined investment governance
- **Each gate** has specific criteria and required deliverables
- **Business case** is the foundation for investment decisions
- **Benefits tracking** extends beyond project closure
- **Fast-track** is available for small, low-risk investments
- **Consistent criteria** ensures objective decision-making

---

## Summary

The stage-gate investment lifecycle provides a structured approach to managing IT investments from idea through benefits realization. Each gate serves as a decision point with specific criteria that must be met before proceeding. This disciplined approach ensures investments are properly justified, planned, executed, and delivering expected value. Benefits tracking beyond project closure completes the investment lifecycle and enables continuous improvement.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 4: Process Overview](/PortfolioManagementHandbook/chapters/04-process-overview/) | [Chapter 6: Prioritization and Scoring](/PortfolioManagementHandbook/chapters/06-prioritization-scoring/) |
