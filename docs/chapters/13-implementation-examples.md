---
layout: default
title: "Chapter 13: Implementation Examples"
parent: "Part IV: Implementation"
nav_order: 13
permalink: /chapters/13-implementation-examples/
---

# Chapter 13: Implementation Examples

## Learning Objectives

After completing this chapter, you will be able to:
- Apply portfolio prioritization in real-world scenarios
- Execute portfolio rationalization exercises
- Implement application portfolio management
- Learn from practical case studies
- Avoid common implementation pitfalls

---

## Case Study 1: Portfolio Prioritization

### Scenario

**Organization:** Mid-sized company (5,000 employees, $50M annual IT budget)

**Situation:**
- 45 active initiatives, 20 new proposals
- Too many projects for available capacity
- No clear prioritization criteria
- Budget overrun: 108% of planned
- Resource utilization: 95% (unsustainable)
- High-value strategic initiatives under-funded

### Current State Analysis

**Portfolio Imbalance:**

| Category | Current # | Current $ | Current % | Target % | Gap |
|----------|-----------|-----------|-----------|----------|-----|
| Transform | 5 | $5M | 10% | 20% | -$5M |
| Grow | 8 | $8M | 16% | 25% | -$4.5M |
| Run | 28 | $32M | 64% | 45% | +$9.5M |
| Comply | 4 | $5M | 10% | 10% | On target |
| **Total** | **45** | **$50M** | **100%** | **100%** | |

**Key Findings:**
- Over-invested in "Run" activities (64% vs. target 45%)
- Under-invested in strategic "Transform" and "Grow" (26% vs. target 45%)
- Many "Run" initiatives are low-value technical debt
- High-value strategic initiatives waiting for funding

### Implementation Approach

**Phase 1: Define Scoring Model (Weeks 1-2)**

Scoring Committee:
- CIO (Chair)
- CFO representative
- Business Unit VPs (3)
- Portfolio Manager
- Enterprise Architect

Customized criteria:
- Strategic alignment weighted at 30% (higher than standard 25%)
- Added "Time to Value" factor (5% weight)
- Cost ranges adjusted to organization's scale

Priority thresholds:
- P1 (Critical): Score > 5.0 - Fund immediately
- P2 (High): Score 3.5-5.0 - Fund this year
- P3 (Medium): Score 2.0-3.5 - Consider next year
- P4 (Low): Score < 2.0 - Defer

**Phase 2: Score All Initiatives (Weeks 3-6)**

Process:
- 2-hour scoring sessions per initiative
- Business sponsor presents business case
- IT sponsor presents technical assessment
- Committee scores independently, then discusses
- Average scores determine final rating

Results:

| Priority | Active | Proposed | Total | Budget | % of Total |
|----------|--------|----------|-------|--------|------------|
| P1 | 8 | 3 | 11 | $18M | 36% |
| P2 | 12 | 5 | 17 | $15M | 30% |
| P3 | 15 | 4 | 19 | $12M | 24% |
| P4 | 10 | 3 | 13 | $5M | 10% |
| **Total** | **45** | **15** | **60** | **$50M** | **100%** |

**Phase 3: Portfolio Rationalization (Weeks 7-8)**

Decisions:

| Action | Count | Budget | Rationale |
|--------|-------|--------|-----------|
| **Continue** | 26 | $38M | P1 + P2 + P3 (>50% complete) |
| **Cancel/Hold** | 19 | $12M | P4 + P3 (<30% complete) |
| **Fund New** | 8 | $12M | Top proposals from recovered budget |

**Final Portfolio (34 initiatives - $50M):**

| Category | # | Investment | % | vs. Target |
|----------|---|------------|---|------------|
| Transform | 12 | $10M | 20% | ✅ On target |
| Grow | 10 | $13M | 26% | ✅ On target |
| Run | 10 | $22M | 44% | ✅ On target |
| Comply | 2 | $5M | 10% | ✅ On target |
| **Total** | **34** | **$50M** | **100%** | |

**Phase 4: Communication and Transition (Weeks 9-10)**

- Executive presentation of rationalized portfolio
- Individual meetings with sponsors of cancelled initiatives
- Formal project closures
- Resource reallocation to high-priority initiatives
- New initiative kickoffs

### Results After 6 Months

| Metric | Before | After | Improvement |
|--------|--------|-------|-------------|
| Active initiatives | 45 | 34 | 24% reduction |
| Strategic investment | 26% | 46% | +20% |
| Resource utilization | 95% | 82% | Sustainable |
| Budget utilization | 108% | 97% | Within target |
| On-time delivery | 65% | 83% | +18% |

**Lessons Learned:**
- Initial scoring took longer than planned (6 weeks vs. 4 weeks)
- Resistance from sponsors of cancelled initiatives (mitigated with clear communication)
- Scoring model required minor adjustments after first month
- Quarterly re-scoring needed to maintain portfolio health
- Executive support critical for cancellation decisions

---

## Case Study 2: Application Portfolio Rationalization

### Scenario

**Organization:** Large enterprise (15,000 employees)

**Situation:**
- 450 business applications
- 35% redundancy across applications
- 120 applications on unsupported platforms
- Annual application costs: $85M
- Limited visibility into application value
- No decommissioning process

### Current State Analysis

| Category | # Apps | % | Annual Cost | Avg Age | Technical Debt |
|----------|--------|---|-------------|---------|----------------|
| Unknown | 180 | 40% | $15M | Unknown | Unknown |
| Support | 150 | 33% | $35M | 12 years | High |
| Core | 90 | 20% | $30M | 8 years | Medium |
| Strategic | 30 | 7% | $5M | 3 years | Low |
| **Total** | **450** | **100%** | **$85M** | **9 years** | |

**Goals:**
- Reduce applications by 30%
- Save $17M annually
- Eliminate unsupported platforms
- Improve portfolio value

### Implementation Approach

**Phase 1: Discovery and Inventory (Months 1-2)**

Discovery methods:
- Automated discovery tools
- License reconciliation
- Server/database inventory
- Business unit surveys
- IT team interviews

Results:
- Cataloged all 450 applications
- Identified 180 previously unknown apps
- Flagged 120 on unsupported platforms
- Found 80 "zombie" apps (no active users)

**Phase 2: Application Assessment (Months 3-5)**

Assessment dimensions (each scored 1-5):
1. Business Value
2. Business Fit
3. Technical Quality
4. Cost Efficiency
5. Functional Fit
6. Risk (inverse)

Assessment results:

| Quadrant | Description | Count | Action |
|----------|-------------|-------|--------|
| High Value / High Quality | Strategic | 65 | **Invest** |
| High Value / Low Quality | Critical but aging | 95 | **Fix** |
| Low Value / High Quality | Over-engineered | 110 | **Rationalize** |
| Low Value / Low Quality | Retirement candidates | 180 | **Retire** |

**Phase 3: Rationalization Strategy (Month 6)**

| Action | Apps | From → To | Savings | Investment |
|--------|------|-----------|---------|------------|
| **Retire** | 150 | 150 → 0 | $25M/yr | $0 |
| **Consolidate** | 75 → 20 | 75 → 20 | $8M/yr | $5M |
| **Replace** | 55 | 55 → 55 (new) | $5M/yr | $15M |
| **Invest** | 35 | Enhance | - | $8M |
| **Maintain** | 135 | As-is | - | - |

Target end state: 300 applications

**Phase 4: Execution (Months 7-24)**

Quick Wins (Months 7-9):
- Retire 80 zombie apps ($12M savings)
- Consolidate email tools 30 → 1 ($3M savings)

Medium-Term (Months 10-18):
- Replace 20 critical aging apps
- Consolidate reporting tools 25 → 3
- Retire 45 redundant apps

Long-Term (Months 19-24):
- Replace unsupported platform apps
- Final cleanup

### Results After 24 Months

| Metric | Before | After | Change |
|--------|--------|-------|--------|
| # Applications | 450 | 310 | -31% |
| Annual Cost | $85M | $70M | -$15M (-18%) |
| Strategic Apps | 30 (7%) | 48 (15%) | +60% |
| Unsupported Platforms | 120 | 15 | -88% |
| Avg Application Age | 9 years | 6 years | -3 years |
| Redundancy | 35% | 8% | -27% |

**Benefits Achieved:**
- $15M annual recurring savings
- 31% fewer applications to manage
- 88% reduction in unsupported platforms
- Simplified compliance management
- Better resource allocation

**Lessons Learned:**
- Discovery took longer than expected
- Stakeholder resistance to retirements
- Data migration more complex than anticipated
- Some "zombie" apps had hidden dependencies
- Executive sponsorship essential

---

## Case Study 3: Benefits Realization Implementation

### Scenario

**Organization:** Healthcare company implementing patient portal

**Investment:** $2.5M over 18 months

### Benefits Definition (Business Case)

| Benefit | Type | Baseline | Target | Measurement |
|---------|------|----------|--------|-------------|
| Call center volume | Savings | 50,000/month | 35,000/month | Call logs |
| Staff productivity | FTE | 45 FTE | 35 FTE | Time studies |
| Patient satisfaction | Quality | 72% | 85% | Surveys |
| No-show rate | Efficiency | 18% | 10% | Appointment data |

**Expected annual benefits:** $1.8M

### Benefits Tracking

| Milestone | Timing | Activities |
|-----------|--------|------------|
| Baseline | Before project | Measure all current state metrics |
| 3 months | Post go-live | First measurement |
| 6 months | Post go-live | Progress review |
| 12 months | Post go-live | Full assessment |

### Results

| Benefit | Target | 3 Mo | 6 Mo | 12 Mo | Status |
|---------|--------|------|------|-------|--------|
| Call reduction | 30% | 15% | 22% | 28% | 🟡 93% |
| FTE savings | 10 FTE | 4 FTE | 7 FTE | 9 FTE | 🟡 90% |
| Patient satisfaction | +13% | +5% | +10% | +14% | ✅ 108% |
| No-show reduction | -8% | -3% | -5% | -7% | 🟡 88% |

**Overall: 95% of expected benefits realized**

### Key Success Factors

1. Clear benefit definitions at project start
2. Named benefit owners
3. Baseline measurements before implementation
4. Regular tracking and reporting
5. Corrective actions when off-track

---

## Key Takeaways

- **Portfolio prioritization** requires clear criteria and executive support
- **Application rationalization** delivers significant cost savings
- **Benefits tracking** ensures investments deliver promised value
- **Communication** is critical throughout implementation
- **Lessons learned** improve future implementations

---

## Summary

Real-world implementation examples demonstrate the practical application of portfolio management concepts. Portfolio prioritization enables organizations to focus resources on highest-value initiatives. Application portfolio rationalization reduces costs and complexity. Benefits tracking ensures investments deliver expected returns. Each implementation requires careful planning, stakeholder engagement, and continuous monitoring.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 12: Templates and Tools](/PortfolioManagementHandbook/chapters/12-templates-tools/) | [Chapter 14: Best Practices](/PortfolioManagementHandbook/chapters/14-best-practices/) |
