# MASTER SPEC — Sai Rishitha Portfolio
Source: `master_prompt.txt` (54 numbered sections). This is the permanent structured form. Nothing here may be removed or simplified without an entry in DECISION_LOG.md. "TBD" = intentionally unspecified.

## 1. Identity
- Name: Malisu Sai Rishitha (short: Sai Rishitha). Computer Science student.
- Positioning: **A Computer Science developer with AI/ML depth and strong frontend capability.** Primary = frontend; differentiator = AI/ML.
- Candidate headline: "I build intelligent digital experiences." (may be improved). Eyebrow: `COMPUTER SCIENCE • AI/ML • FRONTEND`.
- Tone: confident, curious, intelligent, slightly playful. Human, not corporate. Still a student; never "aspiring"/"currently learning"/"beginner" wording.
- Target: Frontend Developer Intern recruiters. Recruiter journey: 0–5s "not a normal student portfolio" → 60s "she can build" → GitHub "real source".

## 2. Philosophy & quality bar
- **DESIGNED, NOT DECORATED.** Expensive, not busy. Every animation has a purpose.
- Feels like an interactive digital studio / "a young AI/ML developer's personal digital laboratory transformed into a premium product studio."
- Must NOT be: resume-in-HTML, template, college assignment, generic AI gradient site, dashboard, Dribbble clone, Mayank clone, neon/cyberpunk, glassmorphism-heavy, purple AI gradient, particles/blobs/3D-for-3D's-sake.
- Reference (quality/interaction only): https://mayankconsole.vercel.app/ — do NOT copy layout, colors, type, animations, section order, wording, cards, motifs, nav, decorations, footer, cursor, signature interaction.
- Final audit questions: first 5s, first 30s, project quality, premium feel, originality (if mistakable for Mayank → redesign), frontend proof, mobile, performance, accessibility.

## 3. Visual system
- Deep neutral base + warm/off-white type + ONE primary accent + ONE secondary accent. Gradients very sparingly. Exact palette: TBD (M02).
- Type: headings Geist / Space Grotesk / Satoshi / Inter Tight (pick in M02); body Inter or Geist; metadata JetBrains Mono. Huge display type, tight tracking, don't overuse uppercase.
- Grid: 12-col desktop, 4-col/simplified mobile, generous whitespace, consistent margins/rhythm.
- Breakpoints: mobile <640, tablet 640–1024, desktop 1024–1440, large >1440. Mobile is redesigned, not stacked desktop (hover→tap, cursor→touch, horizontal→vertical storytelling).

## 4. Motion
- Motion/Framer Motion. Staggered reveals, masked text, clip-path reveals, subtle image movement, spring buttons, section transitions, scroll reveals, subtle parallax.
- Timing: micro 100–250ms; cards 300–500ms; hero 600–1000ms. Prefer spring/ease-out/transform/opacity/clip-path.
- Avoid: constant bounce, spin, heavy blur, big parallax, animation everywhere, long loaders. Loader (optional) ≤ very short, "INITIALIZING EXPERIENCE…".
- Respect `prefers-reduced-motion`.
- Signature scroll: smooth, deliberate, cinematic; section numbers, progress indicator, scroll-based type, changing metadata, sticky project labels, optional horizontal project movement. Performance first.

## 5. Page structure
Nav → Hero (+ marquee) → Signature interaction (AI system → UI system) → Selected Work (3 projects) → About → Skills → Building With Intelligence → Leadership/Experience → Hackathons ("Built under pressure.") → Resume CTA → Contact → Footer.
Routes: `/`, `/about`, `/work/feynaspace`, `/work/visionmatrix`, `/work/silalens`, `/contact`.

### Navigation
Minimal sticky: `SAI RISHITHA` · WORK · ABOUT · SKILLS · JOURNEY · CONTACT · CTA `LET'S TALK →`. Changes on scroll, accessible, smooth scroll, elegant non-generic mobile nav (must not harm usability).

### Hero
Strong, readable, not overloaded. CTAs: primary `EXPLORE MY WORK →`, secondary `VIEW RESUME ↗`; GitHub/LinkedIn/email links. Options: text reveal, staggered type, floating technical metadata, skill ticker, subtle cursor interaction, status indicator, time/location, subtle grid/editorial bg. Avoid particles, blobs, huge 3D, aggressive parallax.

### Signature interaction
One original device. Chosen candidate: **A. AI SYSTEM → UI SYSTEM** (`INPUT → MODEL → DECISION → EXPERIENCE`). Alternatives B (system map nodes), C (type building blocks) — final choice confirmed in M01. Subtle, performant.

### Technology marquee
Customised (e.g. REACT • NEXT.JS • TYPESCRIPT • JAVASCRIPT • TAILWIND • PYTHON • AI/ML • OPENCV • DEEPFACE • GIT • GITHUB). Smooth, pause/respond on interaction, mobile-safe, no layout shift, not tall, accessible fallback.

### About
Editorial, narrative not paragraph. Opening idea: "I'm Sai Rishitha — a Computer Science student building at the intersection of intelligent systems and digital experiences." Covers CS background, AI/ML, frontend, projects, hackathons, experimentation, UI/UX interest, how tech *feels*. Human voice. Personal details beyond those supplied: TBD (do not invent).

### Personality / Easter eggs
Developer notes, playful microcopy, system-style labels, build philosophy, hover details, technical easter eggs. Confident, not childish.

## 6. Selected Work (EXACTLY 3 featured)
Title `SELECTED WORK`; subtitle: where AI, engineering, experimentation and interfaces meet. Each: number, category, title, short description, tech tags, visual preview, GitHub button, live demo (only if exists), case-study button. Example meta `01 / AI • REINFORCEMENT LEARNING`. NOT stacked generic cards. Hover: image scale, type shift, metadata reveal, arrow move, preview alive, subtle bg shift; CTA `VIEW PROJECT →` → `EXPLORE SYSTEM ↗`. No hover-only critical info.

### 01 FeynaSpace — *Reinforcement Learning Environment for AI Tutoring* (FLAGSHIP)
Tech: Python, Reinforcement Learning, React, Next.js, TypeScript, Tailwind. Concepts: student archetypes, state representation, reward functions, memory decay, learning progression, `reset()`, `step()`.
Preview = interactive mini tutoring simulation: STUDENT STATE → OBSERVE → ACTION → REWARD → LEARNING STATE. Values: engagement, retention, mastery, difficulty, learning state — labelled `SIMULATION`/`ILLUSTRATIVE`. User can switch archetype, trigger action, see state transition, reward change, learning-state update. Must feel like a product / interactive case study, not a card. Also: Scaler × Meta AI Hackathon context. Cursor tracking + elephant 🐘 interaction (see IDEA_REGISTRY; exact behavior TBD in M06).

### 02 VisionMatrix — *AI-Powered Face Recognition / Image Recognition System*
Tech: Python, OpenCV, DeepFace, FaceNet, RetinaFace, CustomTkinter. Preview: IMAGE → FACE DETECTION → FACE EMBEDDING → MATCH → RESULT; stylized CV interface (bounding boxes, embedding viz, states, confidence representation). No accuracy numbers.

### 03 SilaLens — *Digital Preservation of Temple Sculptures*
Cultural/visual/human contrast. Sculpture imagery, digital preservation, metadata, documentation, heritage. Do NOT invent features; actual project details: TBD (to be supplied).

### Case studies
Structure: Overview · Problem/Motivation · Context · My Role · Approach · Architecture · Technology · Interface · Challenges · Outcome · Learning · Links. Only true facts; unknown = TBD.

### Narrative
FeynaSpace = how I explore intelligent systems; VisionMatrix = CV/AI; SilaLens = tech for cultural problems; Portfolio = how I turn ideas into polished experiences. (Portfolio is also a completed project.)

## 7. Skills (no bars/percentages/stars)
Categories: **Frontend** (React.js, Next.js, JavaScript, TypeScript, HTML5, CSS3, Tailwind, React Router, Responsive Web Design, Component-Based UI, UI/UX Implementation) · **AI/ML** (Reinforcement Learning, TensorFlow, TensorFlow Lite, Scikit-learn, NumPy, Pandas, OpenCV, DeepFace, FaceNet, RetinaFace) · **Programming** (Python, Java, C, SQL) · **Tools** (Git, GitHub, VS Code, MySQL, Jupyter, Google Colab, Canva) · **AI-Assisted Development** (Claude, ChatGPT, GitHub Copilot, AI-assisted coding/debugging, prompt-driven development).
Hierarchy: PRIMARY frontend; SECONDARY Python/Java/C/SQL/Git/GitHub; SPECIALIZATION AI/ML, CV, RL. Interaction: large category titles with hover reveal (REACT→COMPONENT ARCHITECTURE; NEXT.JS→ROUTING • SSR • SSG • APP ROUTER; PYTHON→AI/ML • COMPUTER VISION). Hover reveals must have non-hover equivalent (tap/focus).

### Building With Intelligence
Small section/detail: Claude, ChatGPT, GitHub Copilot as dev tools; not an "AI tools portfolio".

## 8. Leadership vs Work Experience
Distinct labels `LEADERSHIP` vs `WORK EXPERIENCE`. Leadership: AI/ML Lead — GDG GNITS; General Coordinator, Dev Relations — ArthaChain; Organizing Committee — GNITS MUN; Anchor — Agentic AI Event. Work experience: **none supplied → do not invent** (section may be omitted/TBD). Concise editorial timeline, not corporate jobs.

## 9. Hackathons — "BUILT UNDER PRESSURE."
Timeline/trail/horizontal sequence: Top 4 Teams — ServiceNow Co-Innovation Day; Round 2 — EY Techathon 6.0; Scaler × Meta AI Hackathon — FeynaSpace; Arani Hackathon 2.0; NASA Space Apps; VNR VJIET Hackathon; Product Space AI Agent Hackathon. Dates/results beyond those listed: TBD.

## 10. Resume
Prominent CTAs `VIEW RESUME ↗` / `DOWNLOAD RESUME ↓`. URL/file: TBD.

## 11. Contact
Headline: LET'S BUILD SOMETHING INTERESTING. Copy: open to internships, collaborations, interesting technical problems, opportunities to build. Email, GitHub, LinkedIn, Resume. Form: NAME / EMAIL / MESSAGE / `SEND MESSAGE →` with validation, loading, success, error. No backend configured → structure for later connection; never pretend it sends. Copy-to-clipboard email.

## 12. Footer
`SAI RISHITHA`, `AI/ML • FRONTEND • SOFTWARE`, GitHub/LinkedIn/Email/Resume, `Built with Next.js • React • TypeScript • Tailwind`. Not a copy of Mayank's.

## 13. Cursor
Desktop only, subtle. Dot; links → `VIEW →`; project → `EXPLORE`; external → `↗`. Disabled/simplified on mobile, touch, reduced-motion. (Project-specific: cursor tracking and elephant — see FeynaSpace.)

## 14. Micro-interactions
Magnetic CTAs, arrow movement, color transitions, image scaling, underline animation, nav-state transitions, cursor states, scroll progress, section-number transitions, copy email, link hover previews, button press states. Restraint.

## 15. Accessibility
Semantic HTML, keyboard nav, visible focus, contrast, alt text, accessible buttons/forms, reduced motion, no hover-only critical info, correct heading hierarchy, ARIA only when needed.

## 16. Performance
Optimized images/fonts/animations, minimal client JS, server components where appropriate, CSS transforms, lazy loading, next/image, no layout shift, every dependency justified.

## 17. SEO
Title `Sai Rishitha — AI/ML & Frontend Developer` (may improve), description, Open Graph, favicon, canonical, sitemap, robots.txt, semantic headings.

## 18. Architecture & data
Next.js + React + TypeScript + Tailwind + Motion + Lucide (GSAP/Lenis/Three.js only if justified). Data-driven: `lib/projects.ts`, `skills.ts`, `experience.ts`, `social.ts`, `utils.ts`. Adding repo URLs = edit one data file. Missing GitHub/live/image/form-error → polished fallback states. Reusable components, typed, no giant components, reusable animation variants.

## 19. No-fake-information policy
Never fabricate users, clients, revenue, experience, internships, awards, testimonials, metrics, accuracy, performance, stars, downloads, certifications, technologies, deployments, URLs. Unknown → TBD/placeholder/configurable. FeynaSpace demo values labelled SIMULATION/ILLUSTRATIVE; separate REAL IMPLEMENTED BEHAVIOR from ILLUSTRATIVE.

## 20. Project status rule
FeynaSpace, Interactive Developer Portfolio, VisionMatrix, SilaLens = completed projects. Present confidently. Never fake professional experience.

## 21. Deployment
Expectations: TBD (Vercel is the likely host given Next.js — not yet decided). Final audit vs every section here at M17.
