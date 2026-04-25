# The Trainer's Compendium — BCT Complete Reference & Field Test

> A complete editorial-style reference of the **British Certified Trainer Masterclass** (CPD Standards Office) — Riyadh edition, April 2026. **Completed & Certified · 15 CPD Hours.**

**One single-file website · Two synchronised views · Tab-switchable in place.**

- 📖 **Compendium** — 17 sections covering every framework from Knowles to Kirkpatrick
- 🎯 **Field Test** — 12 interactive applied scenarios with instant feedback

**Live site:** `https://<your-github-username>.github.io/<repo-name>/`

Direct link to the assessment: append `#assessment` to the URL.

---

## 📖 About

A **two-part interactive reference** synthesising every framework from the BCT Masterclass into a single interconnected body of knowledge, plus an applied assessment tool to test framework fluency. Everything lives in one HTML file — a **tab switcher at the top** lets the reader toggle between the reference and the test without leaving the page.

### Part I — The Compendium

Organised around the four-phase cycle of the professional trainer: **Analyse → Design → Deliver → Evaluate**.

**Foundations & Adult Learning**
- *The Premise:* What training actually is (and what it isn't)
- *The Honest Test:* Behaviour change after the room empties
- **Malcolm Knowles' Six Principles of Adult Learning** (Andragogy) — with Kapp 1833 attribution
- **Andragogy vs. Pedagogy** — full comparative taxonomy

**Communication & Leadership**
- **Albert Mehrabian's 55-38-7 Law** — with the scientific caveat from Mehrabian himself
- **Bass & Avolio's Four I's** of Transformational Leadership (1994)
- **The Fifteen Trainer Competencies** — with critical skills flagged

**Learners & Personality**
- **Kolb's Experiential Learning Cycle** (1984)
- **Honey & Mumford's Four Learning Styles** — mapped on the Logical–People × Intro–Extro axes
- **VARK + Digital** — Neil Fleming's 1987 framework, modern extension
- **DISC Profiles** — four personality types + engagement strategies
- **The Hidden Symmetry** — DISC ↔ Honey-Mumford ↔ Kolb mapped as three lenses on the same human

**Design & Delivery**
- **The ADDIE Model** — Analyse · Design · Develop · Deliver · Evaluate
- **SMART Goals** paired with Bloom's Taxonomy
- **The Six Design Moves** — from pre/post tests to session plan
- **DISC-NTRO** (opening) · **The Five R's** (sustaining) · **Wrap-Up Story** (closing)
- **The Delivery Kit** — the boring infrastructure that lets elegant content land

**Evaluation**
- **The Three-Angle Evaluation** — Self · Peer · Audience
- **The Kirkpatrick-Phillips Ladder** — all five levels from smile-sheet to ROI
- **BCT Assessment Criteria** — Theory + Practical for the badge

**The Whole Game**
- A single-sentence summary of the entire professional discipline

### Part II — The Field Test

An **interactive diagnostic quiz** that tests whether you can *apply* the frameworks, not just recite them. **12 real-world scenarios · 30 minutes · instant feedback**.

- **3 scenarios per phase** (Analyse, Design, Deliver, Evaluate)
- **Multi-select questions** with correct answers, wrong answers, and traps
- **Per-option explanations** — every choice gets a rationale
- **"The Lesson"** — memorable takeaway after each scenario
- **Final diagnostic profile** — score, verdict, phase-by-phase breakdown, strengths/weaknesses, prescribed next steps

Compiled by **Mohammed Emad Osman Omer**, Educator and Researcher (Doha, Qatar), from field notes taken during the in-person sessions in Riyadh, cross-referenced with original academic sources.

---

## 🚀 Deployment — GitHub Pages

### If this is your first time:

1. **Create a new GitHub repository** — e.g., `bct-compendium`
2. **Upload these files** via the web interface (drag & drop):
   - `index.html`
   - `README.md`
   - `.nojekyll`
3. **Enable GitHub Pages:**
   - Go to your repo → **Settings** → **Pages**
   - Under "Source" select `main` branch and `/` (root) folder
   - Click **Save**
4. Wait ~1–2 minutes, then visit `https://<your-username>.github.io/<repo-name>/`

### If you already have the repo:

- **Just replace `index.html`** with the new one. GitHub Pages will rebuild automatically.
- **Delete the old `assessment.html`** from your repo — it's no longer needed (everything is in `index.html` now).

---

## 🎨 Design Notes

Everything lives in a **single self-contained HTML file** — no build step, no dependencies beyond Google Fonts. Both views share:

- **Fraunces** (display serif) · **Inter Tight** (UI sans) · **JetBrains Mono** (technical metadata)
- A warm editorial palette: cream paper, rust accent, gold highlights, sage & navy
- Hand-drawn SVG textures (paper grain) for authenticity
- Responsive breakpoints for mobile and tablet
- Print stylesheet optimised for A3 landscape PDF export

**Philosophy:** The visual language is deliberately un-corporate. The goal is a document that feels more like a thoughtful magazine essay than a PowerPoint summary — because adult learners deserve that respect.

---

## 📄 License

Open access. Share, adapt, fork, or submit improvements. The underlying frameworks belong to their original authors; the editorial arrangement is shared under CC-BY-SA.

---

*"The trainer does not transfer content. The trainer transfers capacity — the learner's own capacity, returned to them with interest."*

**M.E.O.** · Doha, Qatar · 2026
