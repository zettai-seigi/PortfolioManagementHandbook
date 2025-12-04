---
layout: default
title: "Chapter 12: Templates and Tools"
parent: "Part IV: Implementation"
nav_order: 12
permalink: /chapters/12-templates-tools/
---

# Chapter 12: Templates and Tools

## Learning Objectives

After completing this chapter, you will be able to:
- Use standard business case templates
- Apply portfolio dashboard templates
- Understand scoring worksheets
- Select appropriate portfolio management tools
- Implement effective tracking mechanisms

---

## Business Case Template

### Executive Summary Section

| Field | Description |
|-------|-------------|
| **Initiative Name** | Clear, descriptive name |
| **Business Sponsor** | Name and title |
| **IT Sponsor** | Name and title |
| **Requested Investment** | Total $ amount |
| **Expected Benefits** | Annual $ value |
| **ROI** | Calculated return |
| **Payback Period** | Months to recover investment |
| **Strategic Alignment** | Strategic objectives supported |
| **Recommendation** | Approve/Defer/Reject |

### Problem/Opportunity Statement

| Field | Description |
|-------|-------------|
| **Business Problem** | What problem does this solve? |
| **Business Impact** | Impact if not addressed |
| **Root Cause** | Why does this problem exist? |
| **Opportunity** | What opportunity does this enable? |
| **Urgency** | Why now? |

### Proposed Solution

| Field | Description |
|-------|-------------|
| **Solution Description** | What will be delivered? |
| **Scope** | What's in scope and out of scope? |
| **Approach** | How will it be implemented? |
| **Technology** | Technologies involved |
| **Integration** | Systems affected |
| **Dependencies** | External dependencies |

### Alternatives Analysis

| Alternative | Description | Pros | Cons | Cost | Recommendation |
|-------------|-------------|------|------|------|----------------|
| Option 1 | [Description] | [List] | [List] | $X | Recommended |
| Option 2 | [Description] | [List] | [List] | $Y | Not recommended |
| Do Nothing | Status quo | No cost | Problem continues | $0 | Not recommended |

### Benefits Statement

| Benefit | Type | Annual Value | Measurement | Owner |
|---------|------|--------------|-------------|-------|
| Revenue increase | Revenue | $X | Sales data | [Name] |
| Cost reduction | Savings | $Y | Cost reports | [Name] |
| Productivity | FTE | Z FTE | Time studies | [Name] |
| Quality | Quality | X% improvement | Quality metrics | [Name] |

### Cost Estimate

| Cost Category | Year 1 | Year 2 | Year 3 | Total |
|---------------|--------|--------|--------|-------|
| **Capital Costs** |
| Hardware | $X | $0 | $0 | $X |
| Software | $X | $0 | $0 | $X |
| Implementation | $X | $0 | $0 | $X |
| Contingency | $X | $0 | $0 | $X |
| **Operating Costs** |
| Support/Maintenance | $X | $X | $X | $3X |
| Licenses | $X | $X | $X | $3X |
| Staff | $X | $X | $X | $3X |
| **Total** | $X | $X | $X | $X |

### Financial Analysis

| Metric | Value | Notes |
|--------|-------|-------|
| **Total Investment** | $X | Capital + Year 1 Operating |
| **Total Benefits (3 yr)** | $Y | Sum of annual benefits |
| **Net Benefit** | $Y - $X | Benefits minus costs |
| **NPV (10% discount)** | $Z | Present value calculation |
| **ROI** | X% | (Benefits - Costs) / Costs |
| **Payback Period** | X months | Investment / Monthly benefit |

### Risk Assessment

| Risk | Probability | Impact | Score | Mitigation |
|------|-------------|--------|-------|------------|
| Technical complexity | M | H | 6 | Proof of concept |
| Resource availability | H | M | 6 | Early commitment |
| User adoption | M | M | 4 | Change management |
| Vendor reliability | L | H | 3 | Contract terms |

### Implementation Timeline

| Phase | Activities | Duration | Start | End |
|-------|------------|----------|-------|-----|
| Planning | Detailed design, resource allocation | 4 weeks | [Date] | [Date] |
| Development | Build, configure, integrate | 12 weeks | [Date] | [Date] |
| Testing | QA, UAT, performance | 4 weeks | [Date] | [Date] |
| Deployment | Training, go-live, stabilization | 4 weeks | [Date] | [Date] |
| **Total** | | 24 weeks | [Date] | [Date] |

### Resource Requirements

| Role | FTE | Duration | Source |
|------|-----|----------|--------|
| Project Manager | 1.0 | 6 months | Internal |
| Business Analyst | 1.0 | 4 months | Internal |
| Developers | 3.0 | 4 months | Internal/Contract |
| QA | 1.0 | 2 months | Internal |
| Training | 0.5 | 1 month | Internal |

---

## Portfolio Dashboard Template

### Dashboard Header

```
┌─────────────────────────────────────────────────────────────────────┐
│ IT PORTFOLIO MANAGEMENT DASHBOARD                                    │
│ Report Date: [Date]    Report Period: [Month/Quarter]               │
│ Prepared by: [Name]    Approved by: [Name]                          │
└─────────────────────────────────────────────────────────────────────┘
```

### Key Metrics Section

| Metric | Current | Target | Trend | Status |
|--------|---------|--------|-------|--------|
| Portfolio Health Score | 4.2/5.0 | 4.0/5.0 | ↑ | ✅ |
| On-Time Delivery | 85% | 85% | → | ✅ |
| On-Budget Delivery | 88% | 90% | ↓ | ⚠️ |
| Benefits Realization | 82% | 85% | ↑ | ⚠️ |
| Resource Utilization | 84% | 80-85% | → | ✅ |

### Portfolio by Category

| Category | # Initiatives | Investment ($M) | % of Portfolio | Target % | Variance |
|----------|--------------|-----------------|----------------|----------|----------|
| Transform | 8 | $5.2 | 22% | 20% | +2% |
| Grow | 12 | $6.0 | 25% | 25% | 0% |
| Run | 18 | $10.3 | 43% | 45% | -2% |
| Comply | 5 | $2.5 | 10% | 10% | 0% |
| **Total** | **43** | **$24.0** | **100%** | **100%** | |

### Portfolio by Status

| Status | # Initiatives | Investment ($M) | Health Score |
|--------|--------------|-----------------|--------------|
| Proposed | 8 | $4.5 | - |
| In Planning | 5 | $2.8 | 4.3 |
| In Execution | 25 | $14.2 | 4.1 |
| In Closure | 3 | $1.5 | 4.5 |
| On Hold | 2 | $1.0 | - |
| **Total Active** | **35** | **$19.5** | **4.2** |

### Top 10 Initiatives

| Rank | Initiative | Category | Investment | Status | Health | Completion |
|------|------------|----------|------------|--------|--------|------------|
| 1 | Digital Platform | Transform | $3.2M | ✅ Green | 4.5 | Q3 |
| 2 | ERP Upgrade | Run | $2.8M | ⚠️ Yellow | 3.8 | Q4 |
| 3 | Customer Portal | Grow | $1.5M | ✅ Green | 4.2 | Q2 |
| 4 | Data Analytics | Transform | $1.2M | ✅ Green | 4.3 | Q3 |
| 5 | Security Upgrade | Comply | $1.0M | ✅ Green | 4.0 | Q2 |

### At-Risk Initiatives

| Initiative | Issue | Impact | Action | Owner | Due |
|------------|-------|--------|--------|-------|-----|
| ERP Upgrade | Vendor delay | 3 weeks slip | Escalate to vendor | [Name] | [Date] |
| Mobile App | Resource gap | Quality risk | Add contractor | [Name] | [Date] |

### Recent Completions (Last 90 Days)

| Initiative | Completion Date | Investment | Benefits | Status |
|------------|-----------------|------------|----------|--------|
| CRM Enhancement | [Date] | $0.8M | $1.2M/yr | Benefits tracking |
| Network Upgrade | [Date] | $1.2M | Availability | Closed |

### Decisions Required

| Item | Initiative | Decision | Due Date | Owner |
|------|------------|----------|----------|-------|
| Approval | Project X | Approve $1.2M investment | [Date] | Steering Committee |
| Continue/Cancel | Project Y | Review viability | [Date] | Investment Board |

---

## Scoring Worksheet Template

### Initiative Information

| Field | Value |
|-------|-------|
| Initiative Name | [Name] |
| Business Sponsor | [Name] |
| Scoring Date | [Date] |
| Scoring Committee | [Names] |

### Business Value Scoring

| Dimension | Weight | Score (0-5) | Weighted | Rationale |
|-----------|--------|-------------|----------|-----------|
| Strategic Alignment | 25% | [0-5] | [Calculate] | [Notes] |
| Financial Impact | 25% | [0-5] | [Calculate] | [Notes] |
| Customer Impact | 20% | [0-5] | [Calculate] | [Notes] |
| Operational Impact | 15% | [0-5] | [Calculate] | [Notes] |
| Competitive Impact | 15% | [0-5] | [Calculate] | [Notes] |
| **Business Value Score** | **100%** | | **[Total]** | |

### Risk Scoring

| Dimension | Weight | Score (0-5) | Weighted | Rationale |
|-----------|--------|-------------|----------|-----------|
| Technical Risk | 25% | [0-5] | [Calculate] | [Notes] |
| Delivery Risk | 25% | [0-5] | [Calculate] | [Notes] |
| Business Risk | 20% | [0-5] | [Calculate] | [Notes] |
| Organizational Risk | 15% | [0-5] | [Calculate] | [Notes] |
| External Risk | 15% | [0-5] | [Calculate] | [Notes] |
| **Risk Score** | **100%** | | **[Total]** | |

### Cost Scoring

| Dimension | Weight | Score (0-5) | Weighted | Rationale |
|-----------|--------|-------------|----------|-----------|
| Capital Cost | 30% | [0-5] | [Calculate] | [Notes] |
| Operating Cost | 25% | [0-5] | [Calculate] | [Notes] |
| Resource Cost | 25% | [0-5] | [Calculate] | [Notes] |
| TCO | 20% | [0-5] | [Calculate] | [Notes] |
| **Cost Score** | **100%** | | **[Total]** | |

### Priority Calculation

| Component | Score | Weight | Adjusted |
|-----------|-------|--------|----------|
| Business Value | [X.X] | 40% | [Calculate] |
| Risk (5 - Score) | [X.X] | 30% | [Calculate] |
| Cost (5 - Score) | [X.X] | 30% | [Calculate] |
| **Priority Score** | | | **[Total]** |

### Priority Classification

| Score | Classification |
|-------|----------------|
| > 5.0 | P1 - Critical |
| 3.5 - 5.0 | P2 - High |
| 2.0 - 3.5 | P3 - Medium |
| 0 - 2.0 | P4 - Low |
| < 0 | P5 - Do Not Fund |

**This Initiative:** [Priority Classification]

---

## Portfolio Management Tools

### Tool Categories

| Category | Purpose | Examples |
|----------|---------|----------|
| **Enterprise PPM** | Full portfolio management | Planview, ServiceNow ITBM, CA Clarity |
| **APM Tools** | Application portfolio | LeanIX, Alfabet, ServiceNow APM |
| **Project Management** | Initiative tracking | MS Project, Jira, Smartsheet |
| **Spreadsheet** | Basic tracking | Excel, Google Sheets |
| **BI/Analytics** | Reporting, dashboards | Power BI, Tableau |

### Tool Selection Criteria

| Criterion | Weight | Evaluation |
|-----------|--------|------------|
| Functionality fit | 30% | Does it meet requirements? |
| Integration | 20% | Does it integrate with existing systems? |
| Usability | 15% | Is it easy to use? |
| Scalability | 15% | Will it grow with the organization? |
| Cost | 10% | Is it affordable? |
| Vendor viability | 10% | Is the vendor stable? |

### Recommended Tool Stack

| Function | Small Org | Medium Org | Large Org |
|----------|-----------|------------|-----------|
| Portfolio tracking | Excel | Smartsheet/Monday | Planview/ServiceNow |
| Scoring | Excel | Custom tool | PPM tool |
| Reporting | Excel/Power BI | Power BI | PPM tool + Power BI |
| Benefits tracking | Excel | Smartsheet | PPM tool |
| Resource management | Excel | Resource Guru | PPM tool |

---

## Key Takeaways

- **Business case template** ensures consistent, complete investment justification
- **Dashboard template** provides standard portfolio visibility
- **Scoring worksheet** enables objective prioritization
- **Right tool selection** matches organizational needs and maturity

---

## Summary

Templates and tools are essential enablers for consistent, efficient portfolio management. Standard templates ensure all investments are evaluated using the same criteria and format. Portfolio dashboards provide stakeholders with timely visibility into portfolio health and performance. The right tools automate routine tasks and enable analysis at scale. Tool selection should match organizational size, maturity, and requirements.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 11: Metrics and KPIs](/PortfolioManagementHandbook/chapters/11-metrics-kpis/) | [Chapter 13: Implementation Examples](/PortfolioManagementHandbook/chapters/13-implementation-examples/) |
