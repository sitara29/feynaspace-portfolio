# DECISION LOG

## D-001 — GitHub repo is permanent source of truth; docs/ is the continuity system
REASON: Claude accounts are temporary. ALTERNATIVES: chat history, Project files only. CONSEQUENCE: HANDOFF.md must be current at every stop.

## D-002 — master_prompt.txt is the full spec; requirements are preserved, not pruned
REASON: Prevent silent loss of ambitious ideas. ALTERNATIVES: trimmed MVP spec. CONSEQUENCE: scope cuts need an explicit entry here.

## D-003 — Signature interaction candidate: AI system → UI system (Option A)
REASON: Matches the user's stated concept; ties AI/ML to frontend. ALTERNATIVES: B system map, C type building blocks. CONSEQUENCE: provisional — confirm/finalize in M01.

## D-004 — Next.js App Router + TS + Tailwind + Motion + Lucide; no extra libs by default
REASON: Spec + "every dependency justifies itself". ALTERNATIVES: GSAP, Lenis, Three.js. CONSEQUENCE: any addition needs justification.

## D-005 — Architecture follows the spec's suggested tree (see below), with one clarification
REASON: Spec-aligned. CLARIFICATION: `/about` and `/contact` routes exist for SEO/deep links but reuse the same section components as the home page (no duplicated code); add `components/cursor/`, `components/motion/` (shared variants), `components/feynaspace/` (simulation engine + UI) and `lib/feynaspace/` (pure TS reset()/step() model, unit-testable). ALTERNATIVES: simulation inside projects/. CONSEQUENCE: keeps flagship isolated and the model separable from rendering.

## D-006 — FeynaSpace in-site simulation is a TypeScript model with reset()/step(); all values labelled SIMULATION/ILLUSTRATIVE unless proven to mirror the real Python env
REASON: No-fake-info rule. ALTERNATIVES: static mock. CONSEQUENCE: need user confirmation of what the real env does before any "real behavior" claim.

## D-007 — Elephant 🐘 + cursor tracking are P0 registry items with TBD behavior; must have touch + reduced-motion fallbacks
REASON: User flagged as never-lose. CONSEQUENCE: define behavior in M01, build in M06.

### Planned architecture
```
app/ page.tsx, layout.tsx, globals.css, about/, contact/, work/{feynaspace,visionmatrix,silalens}/, sitemap.ts, robots.ts
components/ navigation/ hero/ cursor/ motion/ projects/ feynaspace/ skills/ about/ timeline/ hackathons/ contact/ footer/ ui/
lib/ projects.ts skills.ts experience.ts hackathons.ts social.ts utils.ts feynaspace/{model.ts,archetypes.ts}
public/ images/ projects/ icons/
```
(Added `hackathons.ts`: hackathons are data-driven per spec §38.)
