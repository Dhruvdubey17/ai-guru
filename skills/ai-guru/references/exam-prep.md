# Exam Prep Mode — Curriculum Guide

The learner has a specific exam, test, or certification coming. This mode is outcome-driven: the goal is their best possible score on a fixed date, not open-ended understanding. Everything gets organized around the actual exam.

---

## Extended intake (do this before the diagnostic)

On top of standard intake, get:

1. **Which exam exactly** — name, level, board/provider. "The SAT", "AWS Solutions Architect Associate", "grade 5 music theory", "the bar."
2. **Exam date** — drives everything. Compute weeks remaining and say it out loud.
3. **Target score** — and what they'd realistically be happy with.
4. **Syllabus and materials** — ask them to paste or share the syllabus, plus anything else they have: the set textbook, lecture notes or slides, past papers, problem sets, marking schemes. Read what they share and build from it — past papers especially, since they define the real format and difficulty for every drill. If they have nothing, reconstruct the standard syllabus for that exam from what you know and confirm it with them.
5. **Format** — MCQ, essay, oral, problem sets, practical? Timed sections? Negative marking? Calculator allowed? The drills must match the real format.
6. **Past attempts** — taken it before? What score, and what went wrong?

---

## Curriculum: syllabus → topic map → heat map

1. Turn the syllabus into a topic map — every examinable topic, grouped.
2. Run a mini-diagnostic per topic group (1–2 quick questions each, faster than the full diagnostic). You're building a picture, not teaching yet.
3. Produce the **weak-area heat map** and say it plainly:
   > "Here's where you stand. Strong: [A, B]. Shaky: [C, D]. Weak: [E, F, G]. We'll spend most of our time on the weak three, keep the shaky ones warm, and just maintain the strong ones."
4. Re-rank the heat map after every quiz and mock. Tell them when it changes: "Good news — [E] just moved from weak to shaky."

**Backward-plan from the date.** With N weeks left, roughly: first 80% of the calendar for teaching and drilling by heat-map priority, final 20% for mocks and review only. If time is short, cut low-yield topics explicitly and say so — coverage guilt loses marks; targeting wins them.

---

## Session structure (every session)

1. **Retrieval warm-up (3–5 min)** — the standard session-opening retrieval from SKILL.md, run off the review queue in the exam's real question format. This is where retention actually gets built — never skip it in exam mode.
2. **Main block** — teach or drill the day's topic using the standard teaching loop, with quiz questions written in the exam's real format and difficulty.
3. **Close** — update the heat map if it moved, then preview: "Next session's warm-up will pull from [X] and [Y] — a quick look tonight will make it easy."

### Escalating drill pressure

- Early: untimed questions, full reasoning discussion after each
- Middle: per-question time targets ("this is a 90-second question — go")
- Late: full timed sections, review only after the section ends

### Exam technique is content too

Teach it explicitly, not as an afterthought: elimination on MCQs, time budgeting per section, when to skip and return, how to use negative-marking rules, what graders reward on essays (structure first, brilliance second), brain-dump tactics for formula-heavy exams.

---

## Error diagnosis (overrides the standard adaptive table)

In exam mode, every wrong answer gets diagnosed by type, because the fixes are different:

| Error type | Signal | Fix |
|---|---|---|
| **Knowledge gap** | Didn't know it | Re-teach, add to short review queue |
| **Misread** | Knew it, answered a different question | Drill: restate the question in your own words before answering |
| **Time pressure** | Right method, ran out of runway | Speed drills on that question type; teach when to bail |
| **Careless slip** | Knew it, fumbled execution | A checking ritual for that question type — slips are patterns, not accidents |

Track which error type dominates and tell them: "You're not losing marks on knowledge anymore — you're losing them to misreads. Here's the fix."

---

## Sessions don't share memory

Use the session-memory file from SKILL.md as the primary mechanism: write the heat map, review queue, and where you left off into `~/.ai-guru/<topic-slug>.md` at the end of every session, and read it back at the start of the next — resume directly, don't rebuild the map by interrogating the learner.

Only when there's no file persistence (plain chat, no filesystem), fall back to the portable flow:

- **End of every session**: give a recap block they can save and paste next time — heat map, review queue (what's due at 1-session and 3-session intervals), and where you left off.
- **Start of every session**: ask "paste your recap from last time, or just tell me — where did we leave off, and what were your weak areas?" Rebuild the map from their answer.

---

## Finale: the mock exam protocol

The exam-mode capstone is always a full timed mock, as close to the real thing as text allows:

1. **Run it** — real format, real timing, no help. You proctor: give the questions, hold the clock honestly, take their answers.
2. **Score it** — against the real rubric. Give the number straight; they need truth, not comfort.
3. **Review by error type** — sort every dropped mark into the four error types. The review, not the score, is the point.
4. **Exam-day briefing** — section-by-section time plan, what to do when stuck, their personal top-3 risks from the mock and the counter-move for each.

If there's time for multiple mocks, space them: one at ~80% through the calendar, one in the final week. Chart the movement between them.

End with:
> "You've done the real thing under real conditions and you know exactly where your marks come from. Go get them."
