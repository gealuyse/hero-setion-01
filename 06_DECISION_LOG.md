# 06 — Decision Log
## Portfolio Project Log

> **Purpose**  
> Use this file to record what has been decided, why it was decided, what changed, and what is still pending.  
> This prevents the project from drifting or re-litigating old decisions.

---

## 1. How to Use This File

Add a new entry whenever:

- project hierarchy changes
- homepage copy is locked
- visual direction is approved
- a design direction is rejected
- scope changes
- a new source-of-truth decision is made
- an AI/dev handoff creates a new output

Use this format:

```md
## YYYY-MM-DD — Decision Title

### Decision
What was decided.

### Why
Reason behind the decision.

### Impact
What this affects.

### Status
Locked / Working / Revisit later.
```

---

# Current Decisions

## 2026-05-14 — Portfolio Direction Locked

### Decision

Use **Personal Product System Portfolio** as the primary portfolio direction.

### Why

It expresses the designer's focus on:

- workflow-heavy product design
- repeated daily tasks
- system thinking
- practical constraints
- design decisions with reasons
- clarity for both users and teams

### Impact

This direction controls:

- homepage narrative
- case study framing
- visual system
- image prompt direction
- development brief

### Status

Locked for V1.

---

## 2026-05-14 — Core Positioning Locked

### Decision

Use:

> Easy to work with. Serious about the details.

Supporting line:

> I design practical digital products that make repeated workflows easier, clearer, and less annoying — for users and teams.

### Why

The line balances personality and credibility.

It communicates:

- approachable collaboration
- detail seriousness
- practical product focus
- less generic UX positioning

### Impact

Use as the hero anchor and portfolio-wide tone reference.

### Status

Locked for V1.

---

## 2026-05-14 — CDP Becomes Lead Case

### Decision

Use **Customer Data Platform / CDP** as Lead Full Case.

### Why

CDP best proves:

- complex B2B system redesign
- reusable search/filter logic
- workflow clarity
- implementation collaboration
- real UX/UI ownership
- stronger alignment with the portfolio direction

### Impact

Homepage project order:

1. CDP
2. Service Transaction POS

Case study priority:

1. CDP case first
2. POS case second

### Status

Locked for V1.

---

## 2026-05-14 — Service Transaction POS Becomes Second Full Case

### Decision

Use **Service Transaction POS** as the Second Full Case.

### Why

POS still proves a strong and different design capability:

- constraint-led redesign
- familiar workflow preservation
- cashier/staff-facing operational UX
- screen-size adaptation
- visual system thinking

### Impact

POS remains a major portfolio proof, but it should not compete with CDP as the lead narrative.

### Status

Locked for V1.

---

## 2026-05-14 — Other Projects Paused

### Decision

Pause these projects for V1:

- Time Attendance
- Naaraan
- Showtime Swipe

### Why

CDP and POS are enough to form the portfolio backbone. Expanding too early risks diluting the homepage and delaying launch.

### Impact

Other projects can appear later as snapshots, tiles, or supporting work after CDP/POS are stable.

### Status

Locked for V1.

---

## 2026-05-14 — Confidentiality Rules Locked

### Decision

Use sanitized, recreated, anonymized, or illustrative visuals when needed.

Do not expose:

- client names
- logos
- real customer data
- campaign names
- internal URLs
- confidential business logic
- fake metrics

### Why

The portfolio must be safe, honest, and professional.

### Impact

All project visuals, case studies, and AI image prompts must follow this rule.

### Status

Locked.

---

## 2026-05-14 — No Unsupported Metrics Rule Locked

### Decision

Do not claim measurable impact unless direct evidence is available.

Avoid claims such as:

- increased conversion
- reduced task time
- reduced error rate
- improved adoption
- reduced support tickets
- saved cost
- improved campaign performance

### Why

Most projects either do not have available post-launch metrics or the designer did not own analytics.

### Impact

Case studies should focus on:

- design reasoning
- constraints
- trade-offs
- workflow clarity
- reusable patterns
- handoff clarity
- what to validate next

### Status

Locked.

---

## 2026-05-14 — Homepage Section Direction Locked

### Decision

Use six required homepage sections:

1. Hero
2. Selected Work
3. What I Make Clearer / What I Care About
4. How I Work
5. About Preview
6. Footer

### Why

This keeps V1 focused and prevents the portfolio from becoming too broad.

### Impact

Do not add a full Lab section unless a real Lab item exists.

### Status

Locked for V1.

---

## 2026-05-14 — Art Direction Locked for V1

### Decision

Use:

> warm technical editorial product-design documentation

Core narrative:

> Complexity → Structure → Clarity

### Why

This visual direction supports the designer's identity as practical, structured, product-minded, detail-aware, and human.

### Impact

Visual system should use:

- warm off-white background
- white cards
- thin borders
- charcoal text
- restrained accent
- workflow cards
- connector lines
- state chips
- decision notes
- constraint tags

Avoid:

- neon
- sci-fi HUD
- glossy 3D
- glassmorphism
- generic dashboard clones

### Status

Locked for V1.

---

# Pending Decisions

## Accent Color

### Options

- Muted rust as expressive primary direction
- Ink-blue as conservative fallback
- Olive as third option

### Status

Pending visual test.

---

## Typography

### Options

- General Sans + IBM Plex Mono
- Inter + IBM Plex Mono
- Editorial serif option as experimental direction

### Status

Pending visual test.

---

## About Preview

### Status

Primary direction chosen in previous work, but final copy still needs review.

---

## Dev Stack

### Options

- Single HTML file for fast prototype
- Next.js 14 + TypeScript + Tailwind + Framer Motion for scalable build

### Recommendation

Use single HTML first if the goal is quick direction testing. Move to Next.js after direction approval.

### Status

Pending execution decision.
