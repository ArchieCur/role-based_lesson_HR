# MDC HR Buddy Training
### Role-Based AI Learning Series · Units 1–3

**An interactive AI training lesson built around a real HR workflow — not a generic AI summit.**

---

## What This Is

Three connected scenarios. One HR Coordinator named Jamie Rivera. Two weeks of Tuesday mornings at Meridian Dynamics Corporation that kept getting harder.

Most AI training teaches people what AI *is*. This series teaches HR professionals what they're *responsible for* when AI enters their workflow — and where their judgment needs to reposition.

The pedagogical premise: **transferring HR judgment from software-facing to AI-facing.**

Software-facing judgment is binary. The system does what it does. You follow the process or you don't. AI-facing judgment is continuous. The system can do many things. The human has to decide what it *should* do, when, with what data, with what oversight, and with what documentation. That's a fundamentally different cognitive posture — and it's what these three units were built to develop.

---

## The Three Units

### Unit 1 — The Data Inside the Form
*October 14, 8:47 AM. Open enrollment opens in three days.*

Jamie's manager asks her to set up HR Buddy to handle the enrollment volume. She has two files open on her desktop: a Benefits Summary PDF and a CorePeople360 export containing employee SSNs, dates of birth, and dependent information. HR Buddy is waiting.

**What do you upload?**

Three branches. Three different things to learn. No wrong answers — only consequences.

---

### Unit 2 — The Consent Problem
*October 15, 7:52 AM. There is a 2pm meeting with Legal.*

Legal wants to know what HR Buddy accessed yesterday. Jamie already knows the answer: no audit log was configured. Whatever it did with 14 employee queries isn't captured anywhere. She has six hours. Then, at 4:47pm, the affected employee emails directly.

**Two decision nodes. Six paths. One consistent lesson about transparency and process.**

---

### Unit 3 — The Audit Trail
*October 22, 9:15 AM. One week later.*

Marcus, an HR Business Partner, has built a termination workflow using HR Buddy and wants Legal's sign-off before rolling it out to the whole team. Jamie reads it before the 9:30am meeting and senses something wrong — the workflow makes HR Buddy the decision-maker and the manager the rubber stamp. The meeting starts in 12 minutes.

**What do you do?**

The series closes with *Jamie's Journey* — five transferable instincts earned through two weeks of decisions, not six hours of summit slides.

---

## How to Use It

**No installation. No login. No dependencies.**

1. Clone or download this repository
2. Open `lesson/index.html` in any browser
3. Click **Begin Unit 1**

Each unit links to the next. The series takes 30–45 minutes end to end, or 10–15 minutes per unit.

**To share with others:** Upload the `lesson/` folder to any static host — [Netlify](https://netlify.com) (drag and drop), [GitHub Pages](https://pages.github.com), or any web server — and share the link to `index.html`.

---

## Lesson Structure

```
lesson/
├── index.html       Landing page — series overview and entry point
├── unit1.html       Unit 1: The Data Inside the Form
├── unit2.html       Unit 2: The Consent Problem
├── unit3.html       Unit 3: The Audit Trail
└── assets/
    └── mdc-logo.png
```

Each unit is a self-contained React application (loaded via CDN — no build step required). Desktop and mobile layouts are both supported. The 1440×900 desktop canvas scales to fit any screen size.

---

## Design System

The lesson runs on the **MDC HR Buddy Design System** — a purpose-built visual language that simulates a fictional enterprise desktop environment: Microsoft Teams, a ticketing system (HelpGate), an HRIS (CorePeople360), an AI assistant sidebar (HR Buddy), and a Windows-style taskbar.

The design intentionally places the learner *inside* the work environment, not in front of a slide deck. Every decision is made in context — at Jamie's desk, at the time it would actually happen.

**Design tokens:** Corporate blues (`#1e3a6b`), enterprise square-cornered windows, monospace data displays, a docked HR Buddy panel with a custom faceted crystal icon.

---

## The Fictional Enterprise

**Meridian Dynamics Corporation (MDC)** — a fictional 28,000-employee company with a realistic HR technology stack:

| System | Analog |
|--------|--------|
| HelpGate | ServiceNow-adjacent ticketing |
| CorePeople360 | Workday-adjacent HRIS |
| OptiEnroll Hub | Benefits enrollment portal |
| HR Buddy | AI assistant (the subject of this training) |
| Microsoft Teams | Unchanged |

The characters — Jamie Rivera, Marcus L. (HRBP), Charles Douglas (Legal), Antwan Baker (IT) — are composites of real HR roles, not caricatures. Jamie is capable. The scenarios are hard because the situations are genuinely hard, not because she makes careless mistakes.

*Easter egg: CD = Claude Design. AB = Anthropic Backslash.*

---

## Pedagogical Principles

These are the design constraints that shaped every content and interaction decision:

1. **No back button after a decision.** Real workplace decisions aren't reversible.
2. **No score or grade.** This is not a quiz. The learner experiences consequences, not points.
3. **No "Correct!" / "Wrong!" messaging.** Every branch teaches something. The debrief is reflective, not corrective.
4. **Jamie is capable.** The framing is always "here's what this situation was really about" — not "you made a mistake."
5. **The carry-forward card is a design system component.** It appears in every unit's debrief and bridges explicitly into the next unit. Knowledge accumulates.
6. **The complaint is an asset.** In Unit 2, Daniel's three questions create MDC's new AI deployment policy. A complaint handled well produces better outcomes than its absence.

---

## The Posse

This series was built as a structured human-AI collaboration:

| Collaborator | Role |
|---|---|
| **ArchieCur** | Instructional designer, HR domain expert, human-layer reviewer — caught every seam where the scenario accidentally gave characters knowledge they wouldn't have |
| **Claude Sonnet 4.6** | Lesson content — unit scripts, branch text, debrief reinforcement lines, Jamie's Journey |
| **Claude Opus 4.7** | Design brief and pedagogical architecture |
| **Claude Design** | High-fidelity interactive prototype — design system, component specs, visual language |
| **Claude Code** | Production build — this repository |

ArchieCur's contribution is the one that can't be automated: knowing exactly what an HR professional would know, what vocabulary they'd use under pressure, and what feels true versus what feels like an AI's idea of an HR professional. Every vocabulary correction in the lab notebooks is a signal of that.

---

## Why This Exists

> *"Every other ad is Tony Robbins AI Summit. It is a 3 day summit for two hours a day that will teach you everything you need to know about AI."*
>
> — ArchieCur, Unit 3 reviewer notes

Jamie didn't get six hours of AI summit content. She got two weeks of Tuesday mornings that kept getting harder and a set of instincts she'll carry into every AI deployment MDC runs from here.

**That's what AI capable actually looks like.**

This series is a proof of concept for role-based AI training built from the workflows, vocabulary, and judgment calls of a specific job — not from a generic AI literacy framework. The HR series is the first. The methodology applies to any role.

---

## License

MIT · ArchieCur + Claude Sonnet 4.6 + Claude Opus 4.7 + Claude Design + Claude Code (Anthropic) · 2026
