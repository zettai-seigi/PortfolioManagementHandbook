---
layout: default
title: "Chapter 10: Policies and Standards"
parent: "Part III: Governance"
nav_order: 3
permalink: /chapters/10-policies-standards/
---

# Chapter 10: Policies and Standards

## Learning Objectives

After completing this chapter, you will be able to:
- Understand the role of policies in portfolio governance
- Develop comprehensive portfolio management policies
- Establish investment standards and thresholds
- Define consistent scoring and prioritization standards
- Create business case and benefits management standards
- Implement compliance and audit requirements
- Manage policy exceptions appropriately

---

## Introduction: The Foundation of Governance

In the complex landscape of IT portfolio management, policies and standards serve as the bedrock upon which effective governance is built. While processes define what must be done and procedures explain how to do it, policies establish the fundamental principles, boundaries, and mandatory requirements that govern all portfolio activities. Without clear, well-communicated policies, even the most sophisticated portfolio management framework becomes little more than a collection of optional guidelines that vary in application across the organization.

The importance of robust policies cannot be overstated. They provide the authoritative basis for decision-making, establish accountability, ensure consistency, and create transparency in how investment decisions are made. When executives approve a major IT initiative, they do so within the context of established policies that define thresholds, approval authorities, and required justifications. When project managers submit business cases, they follow standards that ensure all necessary information is provided in a consistent format. When benefits owners track value realization, they adhere to standards that enable meaningful comparisons across the portfolio.

This chapter explores the comprehensive policy framework required for effective IT portfolio governance. We examine how policies cascade from enterprise-level governance principles through portfolio-specific requirements to detailed operational standards. We investigate investment thresholds and business case requirements that ensure appropriate scrutiny based on investment size and risk. We detail scoring standards that enable objective prioritization and project standards that maintain consistent oversight throughout the initiative lifecycle. Finally, we address the critical aspects of compliance, audit, and exception management that maintain policy integrity while providing necessary flexibility.

The policies and standards presented here represent industry best practices drawn from ITIL 4, COBIT 2019, PMI portfolio management standards, and real-world implementations across numerous organizations. They should be tailored to your organization's specific context, culture, and maturity level, but the fundamental principles remain universally applicable.

---

## Policy Framework: Understanding the Hierarchy

Effective policy frameworks are hierarchical, with each level providing increasing specificity while maintaining alignment with higher-level principles. Understanding this hierarchy is essential for developing coherent, integrated governance that serves the organization without creating unnecessary bureaucracy.

### The Policy Hierarchy Explained

At the apex of the policy hierarchy sit enterprise-level governance policies that apply to the entire organization. These typically address corporate governance, financial controls, risk management, regulatory compliance, and ethical business conduct. For publicly traded companies, many of these policies derive from legal and regulatory requirements such as Sarbanes-Oxley, GDPR, or industry-specific regulations. Enterprise policies are typically owned by the board of directors, executive leadership, or corporate governance functions.

```
┌─────────────────────────────────────────────────────────────────────┐
│                    ENTERPRISE POLICIES                               │
│  Corporate governance, financial controls, risk management           │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                 IT PORTFOLIO MANAGEMENT POLICY                       │
│  Overall portfolio governance, authority, scope                      │
└───────────────────────────────┬─────────────────────────────────────┘
                                │
        ┌───────────────────────┼───────────────────────┐
        │                       │                       │
        ▼                       ▼                       ▼
┌───────────────┐     ┌───────────────┐     ┌───────────────┐
│  Investment   │     │   Project     │     │   Benefits    │
│   Standards   │     │   Standards   │     │   Standards   │
└───────────────┘     └───────────────┘     └───────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                        PROCEDURES                                    │
│  Detailed how-to guidance for executing processes                    │
└─────────────────────────────────────────────────────────────────────┘
```

The IT Portfolio Management Policy sits beneath enterprise policies and translates them into the specific context of IT investment management. This policy establishes the overall governance framework for how IT investments are identified, evaluated, approved, executed, and measured. It defines the scope of portfolio management, establishes governance bodies and their authorities, articulates fundamental principles, and mandates key requirements that all IT investments must satisfy.

Below the portfolio management policy sit various domain-specific standards that provide detailed requirements for specific aspects of portfolio management. Investment standards define thresholds, approval authorities, and business case requirements. Project standards establish gate requirements, reporting expectations, and performance tolerances. Benefits standards specify how value must be defined, measured, and tracked. Each standard translates policy principles into specific, measurable requirements.

At the base of the hierarchy sit procedures—detailed, step-by-step instructions for executing specific portfolio management activities. While policies and standards define what must be done and to what level, procedures explain precisely how to do it. For example, the investment standard might require financial analysis including NPV, ROI, and payback period, while the financial analysis procedure would provide step-by-step instructions for calculating these metrics, including assumptions to use, discount rates to apply, and templates to complete.

This hierarchical structure ensures consistency while providing appropriate levels of detail for different audiences. Executives need to understand and endorse policies and high-level standards. Portfolio managers and PMO staff need detailed standards and procedures to execute their responsibilities consistently. Project managers and business case authors need clear procedures to follow in preparing submissions.

---

## Portfolio Management Policy: Establishing the Foundation

The IT Portfolio Management Policy is the cornerstone document that establishes governance authority, defines scope, and articulates fundamental principles. This policy should be formally approved by executive leadership and reviewed annually to ensure continued relevance.

### Policy Statement: The Governing Principle

The policy statement is a clear, concise declaration of the organization's intent regarding IT portfolio management. It should be authoritative, unambiguous, and action-oriented. A typical policy statement might read:

*"All IT investments exceeding the defined thresholds shall be managed through the IT Portfolio Management process to ensure strategic alignment, optimize resource utilization, maximize business value, and maintain appropriate governance and oversight. Business sponsors are accountable for benefits realization, and executive leadership is responsible for portfolio-level optimization and strategic alignment."*

This statement accomplishes several critical objectives. First, it establishes mandatory compliance—"shall be managed" leaves no room for optional participation. Second, it defines the purpose—strategic alignment, optimization, and value maximization. Third, it establishes accountability—business sponsors own benefits, executives own portfolio optimization. Fourth, it implies consequences—investments that bypass the process are non-compliant with policy.

The policy statement should be prominently featured in all portfolio governance documentation, included in new initiative kickoff materials, and referenced in business case templates as a constant reminder of the governing authority.

### Policy Scope: Defining Boundaries

Clear scope definition prevents confusion about what does and does not fall under portfolio management governance. Scope boundaries should be explicit, with both inclusions and exclusions clearly stated.

| In Scope | Out of Scope |
|----------|--------------|
| IT projects and programs exceeding threshold | Individual operational tasks and work orders |
| New application development and purchases | Software license renewals under existing contracts |
| Major infrastructure investments | Hardware replacements in normal refresh cycle |
| Service improvement initiatives | Routine maintenance activities |
| Business-facing applications and platforms | Personal productivity tools and desktop software |
| IT-enabled business transformation | Emergency fixes and critical patches |
| Vendor selection for major contracts | Vendor management of existing relationships |

These boundaries should align with the organization's governance philosophy and investment thresholds. Some organizations may choose to include all IT spending above a certain threshold, while others may focus on discretionary investments that require business justification. The key is clarity—project managers and business sponsors should be able to quickly determine whether their initiative requires portfolio governance.

Scope decisions have significant implications. Broader scope provides more comprehensive portfolio visibility and optimization opportunities but increases governance overhead. Narrower scope reduces administrative burden but may miss optimization opportunities and create blind spots in portfolio visibility. Most organizations find the optimal balance by using threshold-based scope definitions combined with discretionary inclusion for strategically significant initiatives regardless of size.

### Policy Principles: Guiding Values

Policy principles articulate the fundamental values and philosophies that guide portfolio management decisions and activities. These principles provide guidance when specific situations are not explicitly addressed by standards or procedures.

| Principle | Statement | Implications |
|-----------|-----------|--------------|
| **Strategic Alignment** | All investments must demonstrate clear alignment to organizational strategy | Business cases must map to strategic objectives; unaligned initiatives are rejected |
| **Business Justification** | All investments must have approved business cases demonstrating expected value | Benefits must be quantified and justified; cost alone is insufficient |
| **Transparent Prioritization** | Investments shall be prioritized using consistent, objective criteria applied uniformly | All proposals are scored using the same framework; scoring is documented |
| **Disciplined Governance** | Investments shall follow established governance processes and gate reviews | Gate requirements are mandatory; no shortcuts allowed |
| **Radical Transparency** | Portfolio information shall be visible to all stakeholders | Dashboards and reports are openly shared; no hidden projects |
| **Business Accountability** | Business sponsors are accountable for benefits realization and initiative success | IT delivers capability; business delivers value |
| **Active Optimization** | The portfolio shall be actively managed to maximize value and strategic impact | Portfolio is regularly reviewed and rebalanced; underperforming initiatives are stopped |
| **Continuous Improvement** | Portfolio management processes shall be continuously evaluated and improved | Lessons learned are captured; process metrics drive improvement |

These principles serve multiple purposes. They guide decision-making when situations arise that are not explicitly covered by standards. They communicate organizational values to all stakeholders. They provide criteria for evaluating proposed changes to policies and standards. They establish the cultural expectations around portfolio management.

For example, the "Business Accountability" principle fundamentally shifts the traditional IT-centric view of project success. IT's responsibility is delivering the technical capability on time, within budget, and with appropriate quality. The business sponsor's responsibility is deploying that capability in ways that generate the promised benefits. This principle has profound implications for how benefits are defined, tracked, and reported.

---

## Investment Standards: Ensuring Appropriate Rigor

Investment standards define the requirements that initiatives must satisfy to enter and progress through the portfolio. These standards ensure that the level of scrutiny, analysis, and governance is commensurate with the investment size, complexity, and risk.

### Investment Thresholds: Right-Sizing Governance

Investment thresholds establish different levels of governance rigor based on investment size. This tiered approach prevents over-governance of small initiatives while ensuring major investments receive appropriate scrutiny.

| Threshold | Amount | Approval Authority | Business Case Requirements | Review Process |
|-----------|--------|-------------------|---------------------------|----------------|
| **Minor** | < $50K | PMO Director | Brief justification (1-2 pages) | Administrative review |
| **Small** | $50K - $100K | Investment Review Board | Simplified business case | Single review cycle |
| **Medium** | $100K - $500K | Investment Review Board | Full business case | Detailed review |
| **Large** | $500K - $1M | Steering Committee | Full business case + risk assessment | Multi-stage review |
| **Major** | > $1M | Steering Committee + Executive | Full business case + independent validation | Executive presentation required |

These thresholds should be calibrated to your organization's scale and context. A Fortune 500 company might set the major threshold at $10M, while a mid-market company might use $500K. The principle remains constant: governance rigor scales with investment significance.

The approval authority escalation reflects increasing organizational impact and risk as investment size grows. Minor investments are approved by portfolio management staff who verify basic requirements. Small investments go to the Investment Review Board—a working-level governance body. Medium investments receive the same governance but trigger more detailed review. Large investments escalate to the Steering Committee, which includes senior business and IT leadership. Major investments add an executive approval layer, ensuring CEO and CFO visibility into the largest commitments.

### Business Case Requirements: Scaling with Complexity

Business case requirements similarly scale with investment size. This graduated approach ensures that all investments are justified while avoiding unnecessary documentation burden on smaller initiatives.

For **minor investments** ($0-$50K), the requirements are minimal: a clear problem statement, proposed solution, rough cost estimate, and expected benefits. This might be captured in a simple 1-2 page memo or form. The emphasis is on speed and simplicity while maintaining basic justification.

**Small investments** ($50K-$100K) require a simplified business case that includes problem definition, solution description, benefit estimates with basic quantification, cost estimates broken down by category, high-level risks, and a rough implementation timeline. This might be 3-5 pages and take a few hours to prepare.

**Medium investments** ($100K-$500K) require a full business case using the standard template. This includes executive summary, detailed problem statement, solution description, alternatives analysis, quantified benefits with measurement plans, detailed cost breakdown, financial analysis (NPV, ROI, payback), risk assessment, implementation approach, resource requirements, assumptions, and decision request. This represents a significant effort—typically 10-20 pages requiring several days to prepare with input from multiple stakeholders.

**Large investments** ($500K-$1M) require everything in the medium business case plus a detailed project plan, comprehensive risk assessment with mitigation strategies, resource plan including specific individuals or roles, change management plan, and integration plan showing how the initiative fits with other portfolio components. Supporting documentation might include vendor proposals, technical assessments, or feasibility studies.

**Major investments** (>$1M) add requirements for independent validation. This might include external review by consultants or internal audit, detailed sensitivity analysis showing impact of key assumption changes, executive presentation materials, and board briefing packages. These business cases are substantial documents that may take weeks to prepare and involve cross-functional teams.

### Financial Analysis Standards: Ensuring Economic Justification

Financial analysis standards specify the techniques that must be applied to evaluate investment economics and the thresholds that must be satisfied for approval.

| Metric | Calculation Required For | Acceptance Threshold | Purpose |
|--------|-------------------------|---------------------|---------|
| **Net Present Value (NPV)** | All investments > $100K | NPV > $0 | Ensures benefits exceed costs in present value terms |
| **Return on Investment (ROI)** | All investments > $100K | ROI > organizational hurdle rate | Ensures adequate return relative to investment |
| **Payback Period** | All investments > $100K | Payback < 3 years | Ensures reasonable time to recover investment |
| **Internal Rate of Return (IRR)** | Recommended for > $500K | IRR > cost of capital | Provides rate-of-return perspective |
| **Sensitivity Analysis** | Required for > $1M | Document key assumption impacts | Reveals risk in financial projections |

These metrics serve different purposes in investment evaluation. NPV provides an absolute measure of value creation in present value dollars. ROI expresses return relative to investment, enabling comparison across different-sized investments. Payback period indicates how long the organization's capital is at risk. IRR provides the discount rate at which the investment breaks even, useful for comparing against capital costs.

The organizational hurdle rate is typically set above the cost of capital to account for execution risk and opportunity cost. For example, if the organization's cost of capital is 8%, the hurdle rate might be set at 12% or 15%. This ensures that investments must clear a meaningful bar to be approved.

Sensitivity analysis is particularly important for large investments. It involves varying key assumptions to understand their impact on financial outcomes. For example, a customer relationship management (CRM) system business case might assume 15% improvement in sales productivity. Sensitivity analysis would show financial outcomes if the improvement is only 10% or reaches 20%. This reveals which assumptions are most critical and how much cushion exists in the projections.

---

## Scoring Standards: Enabling Objective Prioritization

Scoring standards ensure that all initiatives are evaluated consistently using the same criteria, applied by qualified evaluators following a disciplined process. Objective, transparent scoring is fundamental to stakeholder confidence in the prioritization process.

### Scoring Criteria and Weights

The scoring framework should reflect organizational priorities while providing balanced evaluation across multiple dimensions.

| Dimension | Weight | Scale | Scoring Criteria |
|-----------|--------|-------|------------------|
| **Strategic Value** | 40% | 0-5 | Alignment to strategic objectives, strategic importance, long-term impact |
| **Business Value** | 30% | 0-5 | Financial return, benefits quantification, value realization confidence |
| **Risk** | 30% | 0-5 | Technical risk, organizational risk, execution risk (inverse scoring) |

Strategic value captures how well the initiative supports organizational strategy. A score of 5 indicates direct, substantial support for top-priority strategic objectives. A score of 0 indicates no strategic alignment. Specific criteria should reference your organization's strategic objectives. For example, if digital transformation is a key strategy, initiatives that enable digital capabilities score higher on strategic value.

Business value assesses expected financial and operational benefits. A score of 5 indicates exceptional financial returns with high confidence in realization. A score of 0 indicates minimal or unquantifiable benefits. This dimension emphasizes quantifiable, measurable value over subjective claims.

Risk evaluates the probability of successful execution considering technical complexity, organizational change, dependencies, and resource requirements. Risk uses inverse scoring—higher risk receives a lower score. A score of 5 indicates very low risk with proven approaches. A score of 0 indicates extremely high risk with substantial challenges.

The weights reflect typical organizational priorities but should be calibrated to your context. Some organizations place higher weight on strategic value (up to 50%), while others emphasize financial returns more heavily. The key is explicit, documented weighting that remains consistent across all evaluations.

### Scoring Process Standards

Process standards ensure scoring integrity and consistency.

| Standard | Requirement | Rationale |
|----------|-------------|-----------|
| **Independent Scoring** | Scorers complete individual scores before group discussion | Prevents groupthink and anchoring bias |
| **Documentation** | Scoring rationale documented for each dimension | Enables understanding and audit trail |
| **Calibration** | Annual scoring calibration session with case studies | Ensures consistent interpretation across scorers |
| **Conflict of Interest** | Scorers with conflicts must recuse themselves | Maintains objectivity and credibility |
| **Quorum** | Minimum 5 scorers required for valid scoring | Provides statistical reliability |
| **Diversity** | Scorers represent business and IT perspectives | Balances technical and business viewpoints |

Independent scoring is particularly important. Research shows that when scorers see others' scores before recording their own, they anchor on those scores, reducing diversity of perspective. By requiring independent scoring before discussion, the full range of viewpoints is captured.

Documentation of scoring rationale is essential for several reasons. It helps scorers articulate their thinking, forces them to justify their scores, creates an audit trail, and enables future scorers to understand how similar initiatives were evaluated. A simple template asking "Why did you give this score?" for each dimension suffices.

Annual calibration addresses scorer drift over time. Calibration involves having all scorers independently evaluate the same set of case studies, then discussing differences in interpretation. This reveals where scorers interpret criteria differently and enables alignment on standards.

### Priority Classification

Priority classification translates composite scores into actionable categories.

| Priority | Score Range | Definition | Funding Decision |
|----------|-------------|------------|------------------|
| **P1 - Critical** | > 4.5 | Must-do initiatives, critical strategic value | Fund immediately, fast-track approval |
| **P2 - High** | 3.5 - 4.5 | Strong value proposition, should fund | Fund in current cycle if budget available |
| **P3 - Medium** | 2.5 - 3.5 | Positive value, competitive for funding | Consider for current or next cycle |
| **P4 - Low** | 1.5 - 2.5 | Marginal value, defer unless conditions change | Defer to future cycle |
| **P5 - Reject** | < 1.5 | Insufficient value or excessive risk | Do not fund |

These classifications provide clear guidance while maintaining some discretion. Not all P2 initiatives may be funded if budget constraints exist, and compelling circumstances might lead to funding a high-scoring P3 initiative. However, the classifications create a strong presumption that should only be overridden with explicit justification.

---

## Project Standards: Maintaining Consistent Oversight

Project standards establish requirements for how initiatives are managed, monitored, and reported throughout their lifecycle. These standards ensure consistent oversight while enabling portfolio-level visibility and control.

### Gate Standards

Stage-gate standards define the checkpoints through which initiatives must pass, the deliverables required at each gate, and the approval authority.

| Gate | Purpose | Required Deliverables | Approval Authority | Exit Criteria |
|------|---------|----------------------|-------------------|---------------|
| **Gate 0: Ideation** | Capture concept | Concept paper, rough estimate | PMO screening | Sufficient value potential to warrant business case |
| **Gate 1: Business Case** | Justify investment | Full business case, financial analysis | Investment Board | Positive financial return, strategic fit, acceptable risk |
| **Gate 2: Planning** | Validate approach | Detailed plan, budget, resources | Steering Committee (>$500K) | Feasible plan, resources committed, risks managed |
| **Gate 3: Execution** | Authorize work | Readiness checklist, kickoff plan | Project governance | Team ready, resources available, dependencies clear |
| **Gate 4: Deployment** | Approve go-live | Go-live checklist, business sign-off | Project governance + sponsor | System ready, business ready, risks mitigated |
| **Gate 5: Closure** | Close project | Final report, lessons learned | PMO | Deliverables complete, documentation archived |

Each gate has specific entry and exit criteria that must be satisfied. Gate reviews are decision points—the initiative cannot proceed to the next stage without gate approval. This provides natural checkpoints where investments can be stopped if circumstances change or performance falters.

### Project Reporting Standards

Consistent reporting standards enable portfolio-level visibility and aggregation.

| Report | Frequency | Content Requirements | Distribution | Purpose |
|--------|-----------|---------------------|--------------|---------|
| **Status Report** | Weekly | RAG status, accomplishments, plans, issues, risks | Project governance, PMO | Enable timely issue resolution |
| **Monthly Summary** | Monthly | Progress vs. plan, burn rate, milestone status | Steering Committee | Portfolio-level visibility |
| **Benefits Report** | Quarterly | Benefits tracking, realization status | Steering Committee, sponsors | Track value realization |
| **Final Report** | At closure | Outcomes, budget variance, lessons learned | PMO, governance | Close project, capture learning |

Standardized reporting templates ensure consistent information capture across all initiatives. This enables portfolio dashboards that aggregate information from individual projects, providing portfolio-level views of health, progress, and issues.

### Status Indicator Standards

Clear status definitions ensure consistent interpretation of health indicators.

**Green Status** indicates the initiative is on track across all key dimensions. Specifically:
- Schedule: On time or ahead of schedule within approved baseline
- Budget: On budget or under budget, no overrun projected
- Scope: All planned scope remains achievable
- Risks: No high-severity risks, all risks have mitigation plans
- Issues: No blocking issues, minor issues being resolved

**Yellow Status** indicates the initiative is at risk but recoverable with corrective action:
- Schedule: Minor delay (< 10%) or risk of delay exists
- Budget: Minor overrun (< 10%) or overrun risk exists
- Scope: Minor scope reduction being considered
- Risks: High-severity risks exist with mitigation in place
- Issues: Significant issues exist with resolution plans

**Red Status** indicates the initiative is off track and requires escalation:
- Schedule: Major delay (> 10%) or critical path impacted
- Budget: Significant overrun (> 10%) or funding inadequate
- Scope: Major scope reductions required
- Risks: High-severity risks without adequate mitigation
- Issues: Blocking issues without clear resolution path

These definitions reduce ambiguity. Project managers sometimes hesitate to declare red status, fearing negative repercussions. Clear definitions make status determination more objective and reduce the stigma of red status—it simply indicates that executive intervention is needed.

### Tolerance Standards

Tolerance standards define acceptable variance from plan before escalation is required.

| Metric | Green Tolerance | Yellow Tolerance | Red Threshold |
|--------|----------------|------------------|---------------|
| **Schedule Variance** | ± 1 week or 2% | 2-4 weeks or 3-10% | > 4 weeks or > 10% |
| **Budget Variance** | ± 5% | 6-10% | > 10% |
| **Scope Variance** | -0% to +5% | -5% to -10% | > -10% |

These tolerances should be calibrated to initiative size and context. A one-week delay on a two-month project is more significant than a one-week delay on a two-year program. Some organizations use percentage-based tolerances exclusively, while others use absolute thresholds for smaller initiatives.

---

## Benefits Standards: Ensuring Value Realization

Benefits standards define how expected value must be articulated, measured, tracked, and reported. These standards ensure that benefits claims are concrete and measurable rather than vague aspirations.

### Benefits Definition Standards

Clear benefits definition is fundamental to accountability and measurement.

| Element | Requirement | Example |
|---------|-------------|---------|
| **Benefit Statement** | Clear, specific, measurable description | "Reduce order processing time by 30%" |
| **Category** | Type of benefit (revenue, cost savings, etc.) | Cost savings (productivity improvement) |
| **Baseline** | Current state measured quantitatively | Current average: 45 minutes per order |
| **Target** | Expected future state quantified | Target average: 31 minutes per order |
| **Measurement Method** | How benefit will be measured | Time study of 50 sample orders monthly |
| **Measurement Frequency** | How often measured | Monthly for 12 months post-implementation |
| **Benefit Owner** | Named individual accountable | Sarah Johnson, VP Order Management |
| **Realization Timeline** | When benefit expected | 3 months post-go-live for full benefit |
| **Assumptions** | Key assumptions underlying benefit | Assumes order volumes remain constant |

This structured approach eliminates vague benefit claims like "improve efficiency" or "increase customer satisfaction." Every benefit must be specific enough to measure and verify.

### Benefits Categories

Standardized benefit categories enable portfolio-level aggregation and analysis.

| Category | Definition | Examples | Measurement Approach |
|----------|------------|----------|---------------------|
| **Revenue Generation** | New revenue or revenue increase | New product sales, increased sales volume | Incremental revenue measured in $ |
| **Cost Reduction** | Direct cost savings | Reduced labor, lower operating costs | Cost before/after in $ |
| **Cost Avoidance** | Prevented future costs | Avoided system upgrades, prevented hiring | Projected cost that didn't occur in $ |
| **Productivity Improvement** | Same output with less effort | FTE savings, time savings | Hours or FTE saved |
| **Quality Improvement** | Error reduction, defect reduction | Reduced errors, fewer returns | Error rate reduction in % |
| **Risk Reduction** | Reduced risk exposure | Compliance risk reduction, security improvement | Risk score or probability reduction |
| **Strategic Enablement** | Capability enablement | New capability that enables future value | Qualitative assessment + future benefits |

Hard benefits (revenue generation, cost reduction, cost avoidance) should be quantified in financial terms. Soft benefits (productivity, quality, risk) should be quantified in operational terms (hours, error rates, risk scores) with financial translation where possible. Strategic benefits may be primarily qualitative but should still have measurable success indicators.

### Benefits Tracking Standards

Structured tracking milestones ensure benefits are monitored throughout realization.

| Milestone | Timing | Required Activities | Documentation |
|-----------|--------|---------------------|---------------|
| **Baseline Measurement** | Before project start | Measure current state for all claimed benefits | Baseline report with measurements |
| **Initial Measurement** | 3 months post-deployment | First measurement of actual performance | Initial realization report |
| **Interim Assessment** | 6 months post-deployment | Progress assessment, issues identification | Interim benefits report |
| **Final Measurement** | 12 months post-deployment | Full realization assessment | Final benefits report |
| **Closure** | 18 months post-deployment | Close benefits tracking, final documentation | Benefits closure report |

This timeline reflects typical benefit realization patterns where full benefits emerge over 6-12 months as users adapt and processes stabilize. Some benefits realize immediately, while others take longer. The tracking timeline should be tailored to each initiative's benefit profile.

---

## Documentation Standards: Ensuring Consistency

Documentation standards define required templates, formats, and content for key portfolio artifacts. Standardization enables efficient review, comparison, and portfolio-level analysis.

### Business Case Template

The business case template should include these standard sections:

1. **Executive Summary** (1 page maximum): Problem, solution, benefits, costs, financial metrics, recommendation
2. **Problem Statement**: Business problem or opportunity with supporting evidence
3. **Proposed Solution**: Recommended approach with justification
4. **Alternatives Analysis**: Options considered and why this solution was selected
5. **Benefits**: Detailed benefits using benefits definition standards
6. **Costs**: Investment costs and ongoing operating costs
7. **Financial Analysis**: NPV, ROI, payback period calculations with assumptions
8. **Risk Assessment**: Key risks with probability, impact, mitigation strategies
9. **Implementation Approach**: High-level plan with major phases and timeline
10. **Resource Requirements**: Staff, skills, and other resources needed
11. **Assumptions**: Key assumptions underlying the business case
12. **Recommendation**: Requested decision with alternatives

This structure ensures all business cases address the same questions in the same order, enabling efficient review and comparison.

### Portfolio Dashboard Standards

Portfolio dashboards should include these standard elements:

| Dashboard Section | Content | Update Frequency |
|------------------|---------|------------------|
| **Executive Summary** | Key metrics at a glance (health score, status distribution, financial summary) | Real-time |
| **Portfolio Health** | Overall portfolio health with trend over time | Daily |
| **Category Mix** | Actual vs. target allocation by investment category | Weekly |
| **Top Initiatives** | Status of 10 largest active initiatives | Weekly |
| **At-Risk Initiatives** | All yellow/red status initiatives with issue summary | Real-time |
| **Recent Completions** | Initiatives completed in past quarter with value delivered | Monthly |
| **Decisions Required** | Items awaiting governance decision | Real-time |
| **Benefits Summary** | Benefits realization status across portfolio | Monthly |
| **Resource Summary** | Capacity utilization by resource pool | Weekly |

Dashboard design should follow information visualization best practices: use color sparingly and consistently (red/yellow/green for status), avoid clutter, emphasize key metrics, provide drill-down capability, and ensure mobile-friendly display.

---

## Compliance and Audit: Ensuring Adherence

Compliance and audit mechanisms ensure policies are followed and provide assurance to executives, boards, and external auditors that governance is functioning as intended.

### Compliance Requirements

Organizations must demonstrate compliance with portfolio management policies across several dimensions:

**Policy Compliance** requires that all investments above threshold are processed through portfolio management governance. Compliance checks should identify any IT spending that bypassed the process. This often requires coordination with procurement and finance to flag IT spending that wasn't approved through portfolio governance.

**Financial Controls Compliance** ensures investments adhere to organizational financial policies regarding authorization limits, budget adherence, and financial reporting. Portfolio management must integrate with financial management systems to ensure consistent budget tracking.

**Governance Compliance** verifies that decisions are made by authorized governance bodies with appropriate membership and quorum. Meeting minutes should document attendance, decisions, and votes where applicable.

**Documentation Compliance** confirms that required artifacts (business cases, gate documents, status reports, final reports) are completed and archived. Document retention policies should specify retention periods aligned with legal and regulatory requirements.

**Audit Trail Maintenance** requires that decision history is preserved, including who decided what, when, based on what information. This enables reconstruction of decision-making for audit purposes.

### Audit Checkpoints

Regular audit checkpoints verify compliance:

| Checkpoint | Verification Method | Evidence Required | Frequency |
|------------|---------------------|-------------------|-----------|
| **Business Case Approval** | Review approval records | Signed business case with approval authority | Per initiative at Gate 1 |
| **Scoring Documentation** | Review scoring records | Individual scores with rationale | Per initiative at scoring |
| **Gate Approvals** | Review gate meeting minutes | Minutes showing decision and approvers | Per gate |
| **Change Approvals** | Review change log | Change requests with approval signatures | Ongoing |
| **Benefits Tracking** | Review benefits reports | Benefits reports at required intervals | Per benefits tracking schedule |
| **Closure Documentation** | Review closure checklist | Final report with lessons learned | Per initiative at closure |

### Audit Evidence and Retention

Document retention standards ensure audit evidence remains available:

| Document Type | Minimum Retention Period | Storage Location | Rationale |
|---------------|-------------------------|------------------|-----------|
| Business cases | 7 years | Portfolio repository | Financial and legal requirements |
| Approval records | 7 years | Portfolio repository | Governance evidence |
| Scoring documentation | 5 years | Portfolio repository | Decision traceability |
| Status reports | 3 years | Project archives | Operational history |
| Final reports | 7 years | Portfolio repository | Lessons learned |
| Benefits reports | 7 years | Portfolio repository | Value realization evidence |
| Gate review documents | 5 years | Portfolio repository | Governance evidence |

These retention periods align with typical financial record retention requirements and statute of limitations for contract disputes. Organizations with specific regulatory requirements may need longer retention.

---

## Policy Exceptions: Managing Flexibility

While policies establish mandatory requirements, organizational reality sometimes requires flexibility. The exception process provides controlled flexibility while maintaining governance integrity.

### Exception Process

The formal exception process includes these steps:

1. **Request Submission**: Requestor submits exception request to Portfolio Manager with rationale, risk assessment, and proposed mitigation
2. **PMO Review**: PMO assesses request against exception criteria and organizational precedent
3. **Risk Assessment**: PMO evaluates risks of granting exception
4. **Recommendation**: PMO provides written recommendation (approve/deny) with rationale
5. **Decision**: Appropriate authority makes final decision
6. **Documentation**: Exception, rationale, conditions, and expiration are formally documented
7. **Monitoring**: PMO tracks exception and any conditions attached
8. **Expiration**: Exception expires at defined date or event

### Exception Authority Levels

Exception authority should be aligned with the significance of the deviation:

| Exception Type | Example | Approval Authority | Notification |
|----------------|---------|-------------------|--------------|
| **Process Deviation** | Skip a minor procedural step | Portfolio Manager | Investment Board |
| **Threshold Deviation** | $90K initiative treated as minor | Investment Board Chair | Steering Committee |
| **Standard Exception** | Waive specific standard requirement | Investment Board | Steering Committee |
| **Policy Exception** | Waive core policy requirement | Steering Committee | Executive leadership |
| **Governance Exception** | Bypass gate review | CIO + Business Sponsor | Board (if material) |

### Exception Criteria

Not all exception requests should be approved. Evaluation criteria include:

- **Urgency**: Is there a legitimate business emergency?
- **Impact**: What is the impact of denial?
- **Risk**: What risks does granting the exception create?
- **Precedent**: Does granting set problematic precedent?
- **Alternatives**: Are there alternatives that satisfy policy?
- **Temporary vs. Permanent**: Is this a one-time need or symptom of policy problem?

If exception requests become frequent, this signals that the policy may need revision rather than continued exceptions.

---

## Key Takeaways

- **Hierarchical policies** flow from enterprise governance through portfolio policy to domain-specific standards and procedures
- **Clear policy scope** defines what is and isn't subject to portfolio governance, preventing confusion
- **Policy principles** articulate fundamental values that guide decision-making
- **Investment thresholds** ensure governance rigor scales with investment significance
- **Scoring standards** enable objective, transparent prioritization
- **Project standards** maintain consistent oversight throughout initiative lifecycle
- **Benefits standards** ensure value claims are concrete, measurable, and tracked
- **Documentation standards** enable efficiency and consistency
- **Compliance mechanisms** verify adherence to requirements
- **Exception processes** provide controlled flexibility while maintaining governance integrity

---

## Review Questions

1. How does the policy hierarchy ensure alignment between enterprise governance and portfolio management?
2. Why is it important to define both in-scope and out-of-scope boundaries for portfolio management?
3. How do investment thresholds enable efficient governance without creating bureaucracy?
4. What is the purpose of requiring independent scoring before group discussion?
5. How do status indicator standards reduce ambiguity in health reporting?
6. Why must benefits have both a baseline measurement and a target state?
7. What is the relationship between documentation standards and portfolio-level analysis?
8. How do audit checkpoints support governance integrity?
9. When should a policy exception be granted versus policy modification?
10. How do tolerance standards help determine when escalation is required?

---

## Summary

Policies and standards form the foundation of portfolio governance, establishing the mandatory requirements, consistent criteria, and disciplined processes that ensure investments are appropriately justified, prioritized, and managed. The hierarchical policy framework cascades from enterprise governance through portfolio-specific requirements to detailed operational standards. Investment thresholds ensure governance rigor scales with investment significance, while scoring standards enable objective prioritization. Project and benefits standards maintain consistent oversight and accountability throughout the initiative lifecycle. Documentation standards enable efficiency, while compliance mechanisms and exception processes maintain governance integrity. Together, these policies and standards create the structure necessary for effective, sustainable portfolio governance that optimizes value while managing risk.

---

## Chapter Navigation

| Previous | Next |
|----------|------|
| [Chapter 9: Roles and Responsibilities](/PortfolioManagementHandbook/chapters/09-roles-responsibilities/) | [Chapter 11: Metrics and KPIs](/PortfolioManagementHandbook/chapters/11-metrics-kpis/) |
