---
layout: default
title: "Chapter 11: Metrics and KPIs"
parent: "Part III: Governance"
nav_order: 11
permalink: /chapters/11-metrics-kpis/
---

# Chapter 11: Metrics and KPIs

## Learning Objectives

After completing this chapter, you will be able to:
- Define key performance indicators for portfolio management
- Establish meaningful metrics and targets
- Design portfolio dashboards and reports
- Implement benefits realization tracking
- Use metrics for continuous improvement

---

## Metrics Framework

### Metrics Hierarchy

```
┌─────────────────────────────────────────────────────────────────────┐
│                    STRATEGIC METRICS                                 │
│  Overall portfolio value, strategic alignment, business impact       │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    PORTFOLIO METRICS                                 │
│  Portfolio health, balance, performance                              │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    INITIATIVE METRICS                                │
│  Individual project/program performance                              │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    PROCESS METRICS                                   │
│  Portfolio management process efficiency                             │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Key Performance Indicators

### Strategic KPIs

| KPI | Definition | Target | Measurement |
|-----|------------|--------|-------------|
| **Strategic Alignment** | % of portfolio investment aligned to strategic objectives | ≥ 80% | Annual strategic mapping |
| **Business Value Delivered** | $ value delivered vs. planned | ≥ 85% | Benefits tracking |
| **Investment ROI** | Return on IT investment portfolio | > hurdle rate | Financial analysis |
| **Strategic Objective Coverage** | % of strategic objectives with funded initiatives | 100% | Strategy mapping |

### Portfolio KPIs

| KPI | Definition | Target | Measurement |
|-----|------------|--------|-------------|
| **Portfolio Health Score** | Weighted average of initiative health | ≥ 4.0/5.0 | Monthly assessment |
| **On-Time Delivery** | % of initiatives delivered on schedule | ≥ 85% | Project reporting |
| **On-Budget Delivery** | % of initiatives within budget | ≥ 90% | Financial tracking |
| **Category Balance** | Variance from target category allocation | ≤ 5% | Portfolio analysis |
| **Resource Utilization** | % of capacity utilized | 80-85% | Resource tracking |
| **Portfolio Churn** | % of portfolio cancelled or materially changed | ≤ 15% | Change tracking |

### Initiative KPIs

| KPI | Definition | Target | Measurement |
|-----|------------|--------|-------------|
| **Schedule Performance Index (SPI)** | Earned Value / Planned Value | ≥ 0.95 | Project management |
| **Cost Performance Index (CPI)** | Earned Value / Actual Cost | ≥ 0.95 | Project management |
| **Scope Delivery** | % of planned scope delivered | ≥ 95% | Project closure |
| **Stakeholder Satisfaction** | Sponsor satisfaction score | ≥ 4.0/5.0 | Survey |
| **Benefits Realization** | Actual benefits / Planned benefits | ≥ 85% | Benefits tracking |

### Process KPIs

| KPI | Definition | Target | Measurement |
|-----|------------|--------|-------------|
| **Intake Cycle Time** | Time from submission to decision | ≤ 4 weeks | Process tracking |
| **Gate Cycle Time** | Average time between gates | ≤ 2 weeks | Process tracking |
| **Business Case Quality** | % of business cases approved first time | ≥ 70% | Approval tracking |
| **Scoring Consistency** | Variance in scorer assessments | ≤ 20% | Scoring analysis |
| **Governance Attendance** | % attendance at governance meetings | ≥ 80% | Meeting records |

---

## Portfolio Health Metrics

### Portfolio Health Score Calculation

| Component | Weight | Scoring |
|-----------|--------|---------|
| **Schedule Health** | 25% | % Green + (0.5 × % Yellow) |
| **Budget Health** | 25% | % Green + (0.5 × % Yellow) |
| **Risk Health** | 20% | Inverse of high-risk % |
| **Resource Health** | 15% | Optimal utilization score |
| **Benefits Health** | 15% | Benefits on-track % |

### Health Status Distribution

| Status | Definition | Target |
|--------|------------|--------|
| **Green** | On track, no issues | ≥ 70% |
| **Yellow** | Minor issues, corrective action underway | ≤ 25% |
| **Red** | Significant issues, escalation needed | ≤ 5% |

### Health Trend Analysis

Track health trends over time:

| Period | Green | Yellow | Red | Trend |
|--------|-------|--------|-----|-------|
| Q1 | 65% | 28% | 7% | ↓ |
| Q2 | 70% | 24% | 6% | ↑ |
| Q3 | 72% | 23% | 5% | ↑ |
| Q4 | 75% | 20% | 5% | ↑ |

---

## Financial Metrics

### Investment Metrics

| Metric | Definition | Formula |
|--------|------------|---------|
| **Total Portfolio Value** | Sum of approved investments | Σ (Initiative Budget) |
| **Committed Spend** | Amounts contractually committed | Σ (Committed Costs) |
| **Actual Spend** | Amounts spent to date | Σ (Actual Costs) |
| **Remaining Budget** | Budget not yet spent | Total - Actual |
| **Forecast at Completion** | Expected final cost | Actual + Estimate to Complete |

### Return Metrics

| Metric | Definition | Formula |
|--------|------------|---------|
| **Net Present Value (NPV)** | Present value of future cash flows | Σ (Cash Flow / (1+r)^t) |
| **Return on Investment (ROI)** | Benefit relative to investment | (Benefits - Costs) / Costs |
| **Payback Period** | Time to recover investment | Investment / Annual Benefit |
| **Internal Rate of Return (IRR)** | Discount rate where NPV = 0 | Solve for r where NPV = 0 |

### Portfolio Return Summary

| Category | Investment | Expected Benefits | Expected ROI |
|----------|------------|-------------------|--------------|
| Transform | $5M | $12M | 140% |
| Grow | $6M | $10M | 67% |
| Run | $10M | $15M | 50% |
| Comply | $2M | Risk mitigation | N/A |
| **Total** | $23M | $37M+ | 61%+ |

---

## Benefits Metrics

### Benefits Realization KPIs

| KPI | Definition | Target |
|-----|------------|--------|
| **Benefits Tracking Rate** | % of initiatives with benefits tracked | 100% |
| **Benefits On-Track** | % of benefits on target | ≥ 85% |
| **Benefits Realization Rate** | Actual / Planned benefits | ≥ 85% |
| **Benefits Cycle Time** | Average time to realize benefits | Per plan |

### Benefits Status Distribution

| Status | Definition | Target |
|--------|------------|--------|
| **On Track** | Benefits achieving target | ≥ 70% |
| **At Risk** | Benefits below target, recoverable | ≤ 25% |
| **Off Track** | Benefits significantly below target | ≤ 5% |

### Benefits Realization Dashboard

| Initiative | Planned Benefits | Actual to Date | % Realized | Status |
|------------|-----------------|----------------|------------|--------|
| Project A | $2.0M | $1.8M | 90% | ✅ On Track |
| Project B | $1.5M | $1.0M | 67% | ⚠️ At Risk |
| Project C | $3.0M | $2.4M | 80% | ✅ On Track |
| Project D | $1.0M | $0.4M | 40% | ❌ Off Track |
| **Total** | $7.5M | $5.6M | 75% | ⚠️ At Risk |

---

## Capacity Metrics

### Resource Utilization

| Metric | Definition | Target |
|--------|------------|--------|
| **Overall Utilization** | Allocated / Available capacity | 80-85% |
| **Skill Utilization** | By skill category | 75-90% |
| **Contractor Ratio** | Contractor / Total resources | ≤ 30% |
| **Critical Resource Utilization** | Key person availability | ≤ 70% |

### Capacity Dashboard

| Resource Pool | Available | Allocated | Utilization | Status |
|--------------|-----------|-----------|-------------|--------|
| Business Analysts | 20 FTE | 17 FTE | 85% | ✅ Optimal |
| Developers | 50 FTE | 48 FTE | 96% | ⚠️ Over |
| QA/Testing | 15 FTE | 11 FTE | 73% | ✅ Good |
| Project Managers | 10 FTE | 9 FTE | 90% | ⚠️ High |
| **Total** | 95 FTE | 85 FTE | 89% | ⚠️ High |

---

## Dashboard Design

### Executive Dashboard Elements

| Element | Content | Frequency |
|---------|---------|-----------|
| **Health Summary** | Portfolio health score, trend | Real-time |
| **Category Mix** | Actual vs. target allocation | Monthly |
| **Top 10 Initiatives** | Status of major investments | Weekly |
| **At-Risk Initiatives** | Red/Yellow status items | Real-time |
| **Financial Summary** | Budget vs. actual | Monthly |
| **Benefits Summary** | Realization status | Quarterly |
| **Decisions Required** | Pending approvals | Real-time |

### Sample Executive Dashboard Layout

```
┌─────────────────────────────────────────────────────────────────────┐
│ PORTFOLIO EXECUTIVE DASHBOARD                   As of: [Date]       │
├──────────────────────┬──────────────────────────────────────────────┤
│ HEALTH SCORE         │ CATEGORY MIX                                 │
│ ████████░░ 4.2/5.0   │ Transform ████████░░░░░░░░░░ 18% (Target 20%)│
│ Trend: ↑ Improving   │ Grow      ██████████████░░░░ 26% (Target 25%)│
│                      │ Run       ████████████████████ 46% (Target 45%)│
│                      │ Comply    ██████░░░░░░░░░░░░ 10% (Target 10%)│
├──────────────────────┼──────────────────────────────────────────────┤
│ INITIATIVE STATUS    │ BUDGET STATUS                                │
│ Green:  72%          │ Allocated: $23.5M                            │
│ Yellow: 23%          │ Committed: $18.2M                            │
│ Red:     5%          │ Spent:     $12.1M                            │
│                      │ Remaining: $11.4M                            │
├──────────────────────┴──────────────────────────────────────────────┤
│ AT-RISK INITIATIVES                                                  │
│ Project X - Budget 15% over, corrective action underway             │
│ Project Y - Schedule slip 3 weeks, resource constraint              │
├─────────────────────────────────────────────────────────────────────┤
│ DECISIONS REQUIRED                                                   │
│ • Approve Project Z ($1.2M) - Due: [Date]                           │
│ • Cancel/Continue Project W - Due: [Date]                           │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Reporting Cadence

### Report Schedule

| Report | Audience | Frequency | Content |
|--------|----------|-----------|---------|
| **Portfolio Dashboard** | Executives | Weekly | Health, status, decisions |
| **Portfolio Health Report** | Steering Committee | Monthly | Detailed analysis |
| **Benefits Report** | Steering Committee | Quarterly | Realization status |
| **Portfolio Performance Report** | All stakeholders | Quarterly | Comprehensive review |
| **Annual Portfolio Report** | Board | Annual | Full year summary |

### Report Distribution

| Report | Distribution Method | Timing |
|--------|---------------------|--------|
| Executive Dashboard | Email + Portal | Monday AM |
| Health Report | Governance meeting | 2 days before meeting |
| Benefits Report | Email + Presentation | End of quarter |
| Annual Report | Board presentation | Q1 following year |

---

## Using Metrics for Improvement

### Metric Review Process

1. **Collect Data:** Gather metrics from source systems
2. **Analyze Trends:** Compare to targets and historical data
3. **Identify Issues:** Flag metrics outside tolerance
4. **Root Cause Analysis:** Understand why metrics are off target
5. **Recommend Actions:** Propose corrective actions
6. **Track Improvement:** Monitor impact of actions

### Continuous Improvement Cycle

| Phase | Activities | Outputs |
|-------|------------|---------|
| **Measure** | Collect and validate metrics | Accurate data |
| **Analyze** | Compare to targets, identify patterns | Insights |
| **Improve** | Implement corrective actions | Process changes |
| **Control** | Monitor results, sustain gains | Improved performance |

---

## Key Takeaways

- **Balanced metrics** cover strategic, portfolio, initiative, and process levels
- **Clear targets** provide objective performance standards
- **Dashboards** enable quick visibility into portfolio health
- **Benefits tracking** ensures value realization
- **Regular reporting** maintains stakeholder engagement
- **Metrics drive improvement** when actively used

---

## Summary

Effective portfolio management requires comprehensive metrics that span strategic, portfolio, initiative, and process levels. Key performance indicators with clear targets enable objective assessment of portfolio health and performance. Well-designed dashboards provide stakeholders with timely visibility, while benefits tracking ensures investments deliver promised value. Using metrics to drive continuous improvement completes the performance management cycle.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 10: Policies and Standards](/PortfolioManagementHandbook/chapters/10-policies-standards/) | [Chapter 12: Templates and Tools](/PortfolioManagementHandbook/chapters/12-templates-tools/) |
