---
title: Improving Identity and Data Management
---

# Improving Identity and Data Management — Product Strategy + Growth Case Study

For full repository source, see [this file on GitHub](https://github.com/lindanguyen9/ux_research_portfolio/blob/main/case_studies/improving_identity_and_data_management.md).

## Executive Summary
- Problem: Duplicate profiles and unclear data meaning undermined trust and slowed orchestration.
- Decisions: Invest in identity resolution and in-product data understanding; phase role-based visualizations.
- Outcomes: Programmatic duplicate merge shipped; data pages enhanced with descriptions; tracking adoption and resolution speed.

## Story, Approach, Insights, Impact, Leadership
Company: Braze  
Dates: Dec 2023–Present  
Role: Research Lead

### The Story
Identity and data quality sit at the core of lifecycle marketing. As our customers scaled, cracks appeared: duplicate user profiles obscured who the user truly was; teams lacked shared understanding of what data existed and how it should be used; and operators needed clarity fast to orchestrate campaigns with confidence. I led a multi-round research effort to map the real problems, align on decisions, and guide near-term product improvements alongside longer-term strategy.

### Objectives
- Identify the most consequential problems customers face in identity and data management.
- Inform product strategy and near-term UX changes to reduce ambiguity and friction.
- Improve confidence and speed for both technical and non-technical operators.

### Approach
- Several rounds of in-depth 1:1 interviews across regions (AMER, EMEA, APAC) and roles (non-technical/technical marketers, marketing operations, engineers, product) to surface pain points, mental models, and desired outcomes.
- Surveys to validate prevalence and prioritize issues across a broader customer base.
- Ongoing collaboration with PM and Design to turn insights into decision-ready proposals and phased delivery.

### What We Learned (Selected Insights)
1) Duplicate profiles undermine trust and downstream orchestration  
   Evidence: Teams struggled to resolve identity conflicts, leading to inconsistent targeting and reporting.

2) Different roles require different mental models for “who is a user?”  
   Evidence: Engineers favored record-level views; marketers needed person-centric cues and de-duplication status at-a-glance.

3) Lack of an in-product data dictionary slows work and creates shadow documentation  
   Evidence: Many customers maintained external data dictionaries to understand fields and meanings, causing drift and errors.

### What Changed Because of the Research
- Shipped: A programmatic and in-platform duplicate-user merging capability to directly address identity fragmentation.
- Shipped: Enhancements to data pages, enabling field descriptions to improve shared understanding and reduce reliance on external docs.
- Roadmap: Prioritized clarity features (e.g., variant visualizations of user/profile relationships) and a sequenced plan to harden identity management primitives while improving day-to-day operator UX.

### Impact (Early Signals; Tracking In Progress)
- Product: Identity conflict resolution moved from ad-hoc workarounds to supported workflows; data comprehension improved with in-product descriptions.
- Users: Early qualitative feedback from customers to their GTM partners is positive; broader adoption observed across the customer base.
- Organization: Clearer alignment between PM/Design/Eng on identity and data primitives and near-term UX wins.

Tracking in progress: instrumentation for adoption of merge capabilities, reduction in duplicate profile prevalence, time-to-resolution for identity conflicts, reliance on external dictionaries, and campaign QA/review cycle time.

### Leadership Actions
- Partnered closely with the Lead PM and Sr. Product Designer to advocate for identity-first investments and co-authored a future roadmap framing short-term wins and long-term primitives.
- Facilitated decision reviews translating research into crisp tradeoffs (e.g., merge heuristics, guardrails, visibility) and sequenced bets balancing risk and value.

### Methods & Collaboration Details
- Methods: Multi-round 1:1 interviews, surveys; ongoing synthesis to inform iterative product decisions.
- Participants: Many customers across regions (AMER, EMEA, APAC) and roles (non-technical/technical marketers, marketing operations, engineers, product).
- Partners: PM, Design, Eng; GTM partners for qualitative feedback channels.
- Constraints: Typical enterprise constraints (access, data hygiene variability); confidentiality limits on sharing artifacts.

### What’s Next
- Expand measurement for identity-merge adoption and duplicate reduction; define success thresholds by cohort.
- Explore role-based visualizations for identity and profile relationships to match mental models across teams.
- Continue tightening in-product data understanding (dictionary governance, provenance, and change visibility).

### Confidentiality
Customer details and artifacts are not shared; summaries are sanitized.

[← Back to Home](/ux_research_portfolio/)
