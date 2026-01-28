# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a **landing page copywriting and content strategy repository** for Faith Essentials, an Islamic education subscription platform by AlMaghrib Institute. There is no application code, build system, or test suite — the repo stores versioned copy, briefs, quality control documents, and image assets for a landing page redesign.

## Repository Structure

- `copy/version-a/`, `version-b/`, `version-c/` — Three landing page copy variants, each targeting a distinct persona
- `copy/briefs/` — Master briefs defining tone, emotional entry point, objections, and visual direction per version
- `copy/designer-briefs/` — Visual direction document for designers
- `copy/ads/` — Paid ad copy variants tied to each landing page version
- `copy/archive/pre-hormozi-rewrite/` — Backup of earlier copy before the Hormozi framework rewrite
- `copy/quality-control-checklist.md` — Fact-checking template for verifying stats, instructors, pricing
- `copy/hormozi-and-copy-quality-review.md` — Comprehensive copy assessment with grades and improvement recommendations
- `copy/review-existing-vs-new.md` — Comparison of the live site vs. new versions
- `copy/cross-version-qa.md` — Cross-version consistency QA
- `assets/images/` — Instructor photos, course thumbnails, and site UI mockups

## Three Personas / Landing Page Versions

| Version | Persona | Angle | Target |
|---------|---------|-------|--------|
| A — "The Grounding" | Searching Salma | Identity / Crisis | 22-35, reconnecting with faith |
| B — "The Scholars" | Kareem | Access / Authority | 28-45, committed learner |
| C — "The Gift" | Parent/Guardian | Family / Community | Parents worried about children drifting |

All three follow a shared Hormozi-framework persuasion flow: Hero → Problem Agitation → Bridge → Product Intro → Features → Scholar Showcase → Course Library → Social Proof → Objection Handling → Price Anchoring → Final CTA.

## Key Product Facts (for consistency)

- **32 courses** across 7 categories, **400 lectures**, **~80 hours** of content
- **10 scholars** featured (critical: verify which 10 — there is a known discrepancy between the live site roster and the course catalog)
- **Pricing:** $15/month or $120/year (saves $60/year), $0.50/day framing
- **10,000+ lifetime students**, **2,100+ active subscribers** (internal only)

## Known Issues

- **Instructor discrepancy:** The live site lists different instructors than the course catalog. Only 5 names overlap. This must be resolved with stakeholders before finalizing copy.
- **Version grades:** A = B, B = B+, C = A- (per hormozi-and-copy-quality-review.md). Versions A and B need headline rewrites, dream outcome sections, and ~20% trimming.

## Working With This Repo

- When editing copy, always cross-check facts against `copy/quality-control-checklist.md`
- Maintain consistency across all three versions for stats, pricing, and instructor names
- Preserve the Hormozi persuasion flow structure when modifying any landing page version
- The `copy/briefs/` files define the canonical tone and angle for each version — consult them before rewriting
