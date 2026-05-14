# 04 — Dev Implementation Brief
## Homepage Prototype V1

> **Purpose**  
> Use this file when handing the portfolio project to an AI developer, Claude Code, Codex, Cursor, or a human front-end developer.

---

## 1. AI / Developer Role

You are a front-end developer.

Your task is to build a homepage prototype based on the existing portfolio direction.

Do not rewrite the brand strategy.
Do not invent project information.
Do not add fake metrics.
Do not change the project hierarchy.

---

## 2. Read First

Use these documents in this order:

1. `00_MASTER_SOURCE_OF_TRUTH.md`
2. `03_ART_DIRECTION_BRIEF.md`
3. `02_CONTENT_AND_CASE_STUDY_BRIEF.md`
4. `01_STRATEGY_BRIEF.md`

If documents conflict, follow `00_MASTER_SOURCE_OF_TRUTH.md`.

---

## 3. Build Scope

Build homepage V1 only.

Required sections:

```text
1. Hero
2. Selected Work
3. What I Make Clearer / What I Care About
4. How I Work
5. About Preview
6. Footer
```

Do not build full case study pages yet.
Do not add a full Lab section unless a real Lab item exists.
Do not create fake project details.
Do not use real client logos or names.

---

## 4. Recommended Stack Options

### Fastest Prototype

Use if the goal is quick direction testing:

```text
Single HTML file
Tailwind CDN
Vanilla JavaScript
Optional GSAP CDN for simple motion
```

### Scalable Build

Use if the goal is future production:

```text
Next.js 14 App Router
TypeScript
Tailwind CSS
Framer Motion
```

Recommendation:

Start with a single HTML prototype if the goal is to validate visual direction quickly. Move to Next.js after direction is approved.

---

## 5. Homepage Content

### Hero

```text
Easy to work with. Serious about the details.

I design practical digital products that make repeated workflows easier, clearer, and less annoying — for users and teams.

UX/UI Designer focused on workflow-heavy products, internal tools, design systems, and front-end-aware prototyping.
```

Primary CTA:

```text
View selected work
```

Secondary CTA:

```text
Contact
```

### Selected Work

Headline:

```text
Work built around real tasks.
```

Show only two main project cards:

1. Customer Data Platform / CDP
2. Service Transaction POS

### Belief Cards

```text
Small frictions are not small.
Teams should not have to guess the logic.
Every decision needs a reason.
```

### How I Work

```text
Understand the repeated task.
Find where people guess.
Make the flow visible.
Hand off as a system.
```

### Footer

```text
Still trying to make small things less annoying.
```

---

## 6. Layout Rules

### Mobile First

Mobile layout:

- single column
- clear headline first
- hero visual below copy
- project cards stacked
- belief cards stacked
- process steps as vertical list
- no hover-only critical content
- keep visual density low

### Desktop

Desktop layout:

- hero split layout
- left: copy and CTAs
- right: workflow system board
- Selected Work uses two large project cards
- belief/process sections use modular grid
- footer remains calm and human

### Navigation

Recommended header items:

```text
Work · Process · About · Resume · Contact
```

Sticky header is allowed if subtle.

---

## 7. Visual Implementation Rules

Use:

- warm off-white background
- warm-white / white cards
- charcoal text
- thin soft-gray borders
- restrained accent color
- precise spacing
- state chips
- small labels
- connector lines
- workflow fragments
- annotation-like notes

Avoid:

- heavy shadows
- glossy gradients
- glassmorphism
- neon
- sci-fi HUD
- fake dashboards
- stock illustrations
- decorative abstract blobs

---

## 8. Hero Visual Implementation

Hero visual should be built from simple HTML/SVG/CSS shapes:

- cards
- lines
- chips
- small UI fragments
- labels
- arrows
- decision notes
- constraint tags

Meaning:

> scattered workflow fragments becoming a clearer product system.

Do not use a generic dashboard screenshot.

---

## 9. Interaction Rules

Principle:

> Motion should explain, not decorate.

Recommended V1 interactions:

- subtle card hover
- project card reveal of “what became clearer”
- connector line highlight on hero hover
- smooth scroll to sections
- copy email interaction if needed

Motion specs:

- short duration, around 200–320ms
- no bouncy effects
- no long loading animation
- respect reduced motion

Accessibility:

- focus rings visible
- keyboard navigation works
- no hover-only essential content
- color contrast should meet WCAG AA where possible
- text remains readable on mobile

---

## 10. Project Card Requirements

Each project card should include:

```text
Project name
Domain / product type
One-line workflow problem
What became clearer
Role / scope tags
CTA
```

### CDP Card Direction

Should communicate:

- B2B customer data platform
- reusable search/filter pattern
- marketing workflow clarity
- customer data, consent, campaign, and journey logic connection

Avoid fake metrics and dashboard charts.

### POS Card Direction

Should communicate:

- service transaction workflow
- familiar cashier/staff workflow
- 800×600 and 1920×1080 adaptation
- modernization through visual system

Avoid restaurant / retail checkout visuals.

---

## 11. Output Expected from AI Developer

When using this file with an AI developer, ask for:

1. Implementation plan
2. Component / section breakdown
3. Full code
4. Responsive behavior notes
5. Accessibility notes
6. What was intentionally not built

---

## 12. Acceptance Criteria

The homepage prototype passes if:

- It clearly says the designer is a UX/UI Designer.
- It communicates workflow-heavy product focus.
- It shows CDP and POS as the two main proofs.
- It uses the locked positioning and copy direction.
- It feels warm, structured, practical, and product-led.
- It does not look like a generic SaaS dashboard.
- It does not invent metrics or client information.
- It works on mobile first.
- It is easy to scan within 10 seconds.
- Every interaction has a reason.
