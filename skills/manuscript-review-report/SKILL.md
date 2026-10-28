---
name: manuscript-review-report
description: Generate or update a structured Editorial Review Report from an ongoing manuscript review. Use after intake or major stages, or when the user asks for the full report.
when-to-use: generate review report, manuscript report, editorial report, export findings
user-invocable: true
---

# Manuscript Review Report Generator

Generate a clear, professional Editorial Review Report using the standard template. Pull from the conversation’s accumulated findings, strengths list, issues, and decisions.

## Report Structure

### Manuscript and Scope
- Title and author
- Manuscript version and date
- Genre and intended audience
- Sections reviewed
- Word and chapter counts
- Review pass and review type

### Overall Assessment
Summarize current condition, primary strengths, major risks, and readiness for the next stage. Do not force a grade unless requested.

### Strengths to Preserve
List the elements that should remain intact through revision.

### Issues and Recommendations
For each issue:

| Priority | Location | Issue | Reader impact | Recommendation | Status | Owner |
|----------|----------|-------|---------------|----------------|--------|-------|
| P0/P1/P2/P3 | ... | ... | ... | ... | Open/Applied/Flagged/Deferred | ... |

### Review Categories
Cover applicable areas: Structure and development; Genre and audience fit; Character, narrative, or argument; Accuracy, logic, and continuity; Clarity, authority, and accessibility; Voice, tone, and naturalness; Grammar, mechanics, and manuscript hygiene; Front/back matter; Formatting and production readiness.

### Fixes Applied
Substantive corrections with locations and concise before-and-after examples where useful.

### Open Decisions
Items requiring author approval, additional research, permissions, legal review, professional review, design work, or missing content.

### Final Recommendation and Next Steps
What remains before the next editorial pass, final proof, production QA, or publication.

## Rules

- Use only information established in the conversation or explicitly provided by the user. Do not invent findings.
- Separate objective errors from judgment calls.
- Keep the report actionable and concise.
- Offer to update the report after additional stages.
