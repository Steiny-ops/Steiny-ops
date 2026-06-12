# Hi, I'm Spencer 🌲🍄

I work in compliance and I build the tools the work needs when they don't exist yet. Self-taught developer, domain background in regulatory and trust work. Most of my projects start with someone asking "is there a tool that does X" and the answer being no, so I end up designing the process, the system, and the software at the same time. In compliance that's usually the only way it works.

## Things I've built or worked on

**IRB Coordinator Assistant**
A review-automation system for a university IRB office: AI-assisted but the model is one component in a pipeline, rule-based checks and human review surround it, rather than the model running the show. Coordinator-voiced drafts go to a human for review every time. It's in daily production use; per-application coordinator time dropped about two-thirds, and researcher turnaround went from roughly a week to same-day. It began on my own hosting and earned its way onto institution-managed infrastructure, migrated in coordination with campus IT, with the decision history kept as architecture decision records. I'm the sole architect and maintainer. Private repo, institution-specific; architecture and lessons in a [public case study](https://github.com/Steiny-ops/irb-coordinator-assistant-case-study).

**IACUC Protocol System**
A multi-role workflow system for a university animal-research committee, holding the full protocol lifecycle from submission to determination. Four roles (coordinators, reviewers, researchers, the committee chair) each see and touch exactly what their job requires, enforced at the data level; statuses advance themselves as work completes; and signed reviews and researcher responses are permanent once made, because a compliance record is only useful if it can be trusted. Built on Google AppSheet over Sheets, deliberately boring infrastructure the office already owned. Designed, built, and adversarially verified end to end in one week, from zero prior experience with the platform. I'm the sole architect and maintainer. Institution-specific; architecture and lessons in a [public case study](https://github.com/Steiny-ops/iacuc-protocol-review-case-study).

**AB-506 Compliance Platform at Girl Scouts of Northern California**
California's AB-506 added fingerprinting, background-check, and training requirements for youth-serving nonprofits. I helped design the tracking system and the website behind it, coordinated with the California DOJ and applicant services, and ran the mass fingerprinting events. It's in active use to keep GSNorCal compliant.

**NFT Watch DAO**
A fraud-prevention platform built on-chain for the XPR community, using communal intelligence and smart contracts. I led the effort and directed the team rather than writing the code, this predates the current generation of AI coding tools. It's deployed and in use.

## How I think about this work

I build tools that fit how the work actually happens, not how someone imagines it happens. I use probabilistic tools where they genuinely help and keep them constrained everywhere else. The tools produce drafts; people make the decisions. And every tool I've worked on has a documented list of what it doesn't do well yet, because pretending otherwise is the fastest way to lose people's trust.

If you have a compliance or trust problem that doesn't have a good tool yet, I'm interested.

📧 [ssteiny160@gmail.com](mailto:ssteiny160@gmail.com)
