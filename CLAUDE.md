# Claude Code Project Instructions

## Project Overview

This is the **IT Portfolio Management Handbook** - a comprehensive ITIL/ITSM guide published on GitHub Pages.

- **URL:** https://zettai-seigi.github.io/PortfolioManagementHandbook/
- **Repository:** https://github.com/zettai-seigi/PortfolioManagementHandbook
- **Theme:** Jekyll with Just the Docs
- **License:** MIT

## Project Structure

```
PortfolioManagementHandbook/
├── docs/                    # GitHub Pages content (MAIN CONTENT)
│   ├── _config.yml         # Jekyll configuration
│   ├── index.md            # Home page
│   ├── chapters/           # All 16 chapters
│   └── images/             # Published images
├── README.md               # Repository documentation
├── LICENSE                 # MIT License
├── .gitignore              # Git ignore rules
└── CLAUDE.md               # This file
```

## Key Framework Elements

### Investment Categories (Transform-Grow-Run-Comply)
- **Transform** - New capabilities, innovation (15-25%)
- **Grow** - Expand existing capabilities (20-30%)
- **Run** - Maintain operations (40-50%)
- **Comply/Secure** - Regulatory/security (10-15%)

### Application Categories (TIME Model)
- **Strategic** - Competitive advantage, high value
- **Core** - Critical operations
- **Support** - Enable business functions
- **Retire** - Candidate for retirement

### 8 Critical Success Factors (CSFs)
1. Executive Sponsorship and Governance
2. Disciplined Investment Process (Stage-Gates)
3. Transparent Prioritization Criteria
4. Portfolio Management Office (PMO)
5. Benefits Accountability
6. Regular Portfolio Reviews and Rebalancing
7. Integrated Portfolio Management Tool
8. Continuous Improvement Culture

### 6 Key Performance Indicators (KPIs)
1. Strategic Alignment (target: ≥80%)
2. On-Time Delivery (target: ≥85%)
3. On-Budget Delivery (target: ≥90%)
4. Benefits Realization (target: ≥85%)
5. Resource Utilization (target: 80-85%)
6. Portfolio Health Score (target: ≥4.0/5.0)

### 5 Maturity Levels
1. Initial (Ad-hoc)
2. Repeatable (Basic)
3. Defined (Standardized)
4. Managed (Integrated)
5. Optimizing (Excellence)

## Content Guidelines

### Chapter Structure
Each chapter should include:
1. YAML frontmatter with layout, title, parent, nav_order, permalink
2. Learning Objectives section
3. Main content with ## and ### headings
4. Tables for structured data
5. Practical examples
6. Key Takeaways (bullet points)
7. Summary paragraph
8. Chapter Navigation links

### Writing Style
- Professional, instructional tone
- Consistent ITIL terminology
- Cross-reference other chapters where relevant
- Use real-world examples
- Target 2000-4000 words per chapter

### Handbook Parts
- Part I: Introduction (Chapters 1-3)
- Part II: Framework (Chapters 4-7)
- Part III: Governance (Chapters 8-11)
- Part IV: Implementation (Chapters 12-16)

## Common Tasks

### Editing Chapters
- Chapter files are in `docs/chapters/`
- Use Edit tool for precise changes
- Maintain consistent formatting

### Adding Images
- Place in `docs/images/`
- Reference with `../images/filename.png`

### Git Operations
```bash
git add .
git commit -m "Description"
git push origin main
```

## Important Notes

- Maintain investment category consistency across chapters
- The book is for GitHub Pages - don't create files that break Jekyll
- When editing, verify cross-references remain accurate
- CSF numbering should be consistent (1-8)
- KPI definitions must match across chapters
- Scoring framework should use 0-5 scale consistently
