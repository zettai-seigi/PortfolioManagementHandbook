---
layout: default
title: "Chapter 8: Governance Structure"
parent: "Part III: Governance"
nav_order: 8
permalink: /chapters/08-governance-structure/
---

# Chapter 8: Governance Structure

## Learning Objectives

After completing this chapter, you will be able to:
- Design an effective portfolio governance structure
- Establish appropriate governance bodies and their responsibilities
- Define decision rights and authority levels
- Implement governance cadence and meetings
- Integrate portfolio governance with enterprise governance

---

## Governance Framework Overview

### Purpose of Portfolio Governance

Portfolio governance provides the structure for:
- **Decision Making:** Who decides what, when, and how
- **Accountability:** Clear ownership of outcomes
- **Transparency:** Visibility into portfolio status and decisions
- **Control:** Appropriate oversight without bureaucracy
- **Alignment:** Ensuring portfolio serves organizational goals

### Governance Principles

| Principle | Description |
|-----------|-------------|
| **Right Level** | Decisions made at appropriate level |
| **Clear Authority** | Decision rights well-defined |
| **Transparency** | Decisions and rationale visible |
| **Accountability** | Single owner for each decision |
| **Efficiency** | Balance control with speed |
| **Consistency** | Same criteria applied uniformly |

---

## Governance Bodies

### Three-Tier Governance Model

```
┌─────────────────────────────────────────────────────────────────────┐
│                 PORTFOLIO STEERING COMMITTEE                         │
│  Strategic Direction | Major Approvals | Escalations                │
│  Frequency: Monthly                                                  │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                 INVESTMENT REVIEW BOARD                              │
│  Investment Review | Scoring | Recommendations                       │
│  Frequency: Bi-weekly                                                │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                 PORTFOLIO MANAGEMENT OFFICE                          │
│  Day-to-Day Operations | Analysis | Reporting                        │
│  Frequency: Continuous                                               │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Portfolio Steering Committee

### Purpose
Provide strategic direction and oversight for the IT portfolio, making key investment decisions and resolving escalations.

### Membership

| Role | Responsibility |
|------|----------------|
| **CIO/CTO (Chair)** | Overall portfolio direction, final decisions |
| **CFO or Finance VP** | Financial oversight, budget alignment |
| **Business Unit VPs (2-3)** | Business priority input, sponsor perspective |
| **Enterprise Architect** | Architecture alignment, technical strategy |
| **Portfolio Manager** | Portfolio status, recommendations |

### Authority

| Decision Type | Authority |
|---------------|-----------|
| Portfolio strategy and targets | Approve |
| Investments > $1M | Approve |
| Portfolio rebalancing | Approve |
| Initiative cancellation > $500K | Approve |
| Major escalations | Resolve |
| Policy exceptions | Approve |

### Meeting Cadence

| Frequency | Focus |
|-----------|-------|
| **Monthly** | Portfolio health review, major decisions |
| **Quarterly** | Strategic review, rebalancing |
| **Annual** | Strategic portfolio planning |
| **Ad-hoc** | Urgent escalations |

### Agenda (Monthly)

| Item | Duration | Owner |
|------|----------|-------|
| Previous action items | 5 min | Chair |
| Portfolio health dashboard | 15 min | Portfolio Manager |
| At-risk initiatives | 15 min | Portfolio Manager |
| Investment decisions | 20 min | Investment Board Chair |
| Escalations | 15 min | Various |
| Strategic topics | 20 min | Various |
| Action items and close | 10 min | Chair |

---

## Investment Review Board

### Purpose
Evaluate investment proposals, apply scoring criteria, and make funding recommendations to the Steering Committee.

### Membership

| Role | Responsibility |
|------|----------------|
| **Portfolio Manager (Chair)** | Facilitate reviews, ensure consistency |
| **Business Analysts (2-3)** | Business value assessment |
| **Finance Representative** | Financial analysis |
| **Enterprise Architect** | Technical assessment |
| **Security Representative** | Risk and compliance |
| **Resource Manager** | Capacity assessment |

### Authority

| Decision Type | Authority |
|---------------|-----------|
| Investments < $100K | Approve |
| Investments $100K - $1M | Recommend |
| Investments > $1M | Recommend to Steering Committee |
| Scoring and prioritization | Execute |
| Fast-track approvals | Approve (within criteria) |

### Meeting Cadence

| Frequency | Focus |
|-----------|-------|
| **Bi-weekly** | Investment reviews, scoring sessions |
| **Weekly** | Urgent reviews (if needed) |

### Agenda (Bi-weekly)

| Item | Duration | Owner |
|------|----------|-------|
| Pipeline review | 10 min | Portfolio Analyst |
| Investment presentations (3-4) | 60 min | Sponsors |
| Scoring and discussion | 30 min | Board |
| Recommendations | 15 min | Chair |
| Action items | 5 min | Chair |

---

## Portfolio Management Office (PMO)

### Purpose
Provide day-to-day portfolio management operations, analysis, and support.

### Staffing

| Role | Count | Responsibility |
|------|-------|----------------|
| **Portfolio Manager** | 1 | Lead PMO, facilitate governance |
| **Portfolio Analysts** | 2-3 | Analysis, reporting, data management |
| **Business Analysts** | 2-3 | Business case support, benefits tracking |

### Responsibilities

| Area | Activities |
|------|------------|
| **Demand Management** | Intake, qualification, initial assessment |
| **Analysis** | Scoring support, scenario modeling, metrics |
| **Reporting** | Dashboards, health reports, executive reporting |
| **Governance Support** | Meeting prep, documentation, follow-up |
| **Process** | Process design, improvement, training |
| **Tools** | Portfolio management system administration |

### Services

| Service | Description |
|---------|-------------|
| Investment intake | Process and qualify investment proposals |
| Business case coaching | Help sponsors develop strong business cases |
| Scoring facilitation | Support scoring sessions and calibration |
| Portfolio reporting | Produce dashboards and reports |
| Benefits tracking | Monitor and report benefits realization |
| Process guidance | Advise on portfolio processes |

---

## Decision Rights Matrix

### Investment Decisions

| Decision | PMO | Investment Board | Steering Committee |
|----------|-----|------------------|-------------------|
| Intake qualification | A/R | C | I |
| Fast-track approval (<$100K) | R | A | I |
| Standard approval ($100K-$1M) | R | R | A |
| Major approval (>$1M) | R | R | A |
| Priority scoring | R | A | I |
| Portfolio rebalancing | R | R | A |

### Operational Decisions

| Decision | PMO | Investment Board | Steering Committee |
|----------|-----|------------------|-------------------|
| Status reporting | A/R | I | I |
| Risk escalation | R | A | I/A (if major) |
| Process changes | R | C | A |
| Tool changes | R | C | A |
| Resource conflicts | R | A | A (if major) |

**Legend:** R=Responsible, A=Accountable, C=Consulted, I=Informed

---

## Governance Integration

### Enterprise Governance Alignment

```
┌─────────────────────────────────────────────────────────────────────┐
│                    BOARD OF DIRECTORS                               │
│  Strategic Direction | Major Investments | Risk Oversight           │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    EXECUTIVE COMMITTEE                               │
│  Enterprise Strategy | Budget Allocation | Cross-functional         │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
        ┌───────────────────────┼───────────────────────┐
        │                       │                       │
        ▼                       ▼                       ▼
┌───────────────┐     ┌───────────────┐     ┌───────────────┐
│ IT Portfolio  │     │   Finance     │     │   Business    │
│  Governance   │     │   Committee   │     │   Planning    │
└───────────────┘     └───────────────┘     └───────────────┘
```

### Integration Points

| Enterprise Body | Portfolio Integration |
|-----------------|----------------------|
| Board of Directors | Major investment approvals, risk reporting |
| Executive Committee | Strategic alignment, budget allocation |
| Finance Committee | Investment ROI, benefits realization |
| Risk Committee | Portfolio risk reporting |
| Audit Committee | Governance compliance, controls |

---

## Governance Effectiveness

### Success Metrics

| Metric | Target | Measurement |
|--------|--------|-------------|
| Decision cycle time | < 2 weeks | Time from submission to decision |
| Meeting effectiveness | > 80% | Attendee satisfaction survey |
| Decision adherence | > 95% | % decisions followed through |
| Escalation rate | < 10% | % decisions requiring escalation |
| Stakeholder satisfaction | > 4.0/5.0 | Annual governance survey |

### Governance Health Check

| Area | Assessment Questions |
|------|---------------------|
| **Clarity** | Are roles and responsibilities clear? |
| **Efficiency** | Are decisions made in appropriate time? |
| **Consistency** | Are criteria applied uniformly? |
| **Transparency** | Are decisions and rationale communicated? |
| **Engagement** | Are right people involved? |
| **Value** | Does governance add value vs. overhead? |

---

## Implementation Guidance

### Governance Design Steps

1. **Assess Current State**
   - Document existing governance
   - Identify gaps and pain points
   - Understand decision flow

2. **Design Future State**
   - Define governance bodies
   - Establish decision rights
   - Set meeting cadence
   - Create charters

3. **Implement Governance**
   - Communicate new structure
   - Train participants
   - Launch governance meetings
   - Monitor and adjust

### Common Governance Pitfalls

| Pitfall | Impact | Mitigation |
|---------|--------|------------|
| Too many bodies | Decision delays, confusion | Consolidate, clarify authority |
| Unclear authority | Duplicate decisions, gaps | Decision rights matrix |
| Wrong participants | Poor decisions, delays | Review and adjust membership |
| Meeting overload | Fatigue, low attendance | Right frequency, efficient agendas |
| Rubber stamping | False governance | Meaningful review, real decisions |

---

## Key Takeaways

- **Three-tier governance** provides appropriate oversight at each level
- **Clear decision rights** prevent confusion and delays
- **Right membership** ensures quality decisions
- **Regular cadence** maintains portfolio discipline
- **Enterprise integration** aligns portfolio with organizational governance
- **Governance effectiveness** should be measured and improved

---

## Summary

Effective portfolio governance requires clear structure, defined authority, and appropriate cadence. The three-tier model of Steering Committee, Investment Review Board, and PMO provides escalation paths and separation of concerns. Decision rights matrices clarify who decides what. Integration with enterprise governance ensures portfolio decisions align with organizational direction. Regular assessment of governance effectiveness enables continuous improvement.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 7: Portfolio Balancing](/PortfolioManagementHandbook/chapters/07-portfolio-balancing/) | [Chapter 9: Roles and Responsibilities](/PortfolioManagementHandbook/chapters/09-roles-responsibilities/) |
