# Agent Instructions — hozaifamoustafa-resume-latex

This repo is a LaTeX resume template with an HR-informed guide. When a developer opens it with a coding agent, there are two primary workflows you should support.

---

## Workflow 1: Build or Improve the Resume

**Triggered by:** "help me build my resume", "edit my resume", "update my resume", "I want to apply for X role", or any request to modify resume content.

### How to conduct this

1. Read `RESUME_GUIDE.md` in full — it is the authoritative source for every structural and content decision.
2. Read `hozaifamoustafa_resume.tex` — this is the file to edit.
3. Ask the user for the following if not already provided:
   - Their target role
   - Their degree field vs. the target role field (same domain or different?)
   - Years of experience
4. Apply section ordering based on the rule in `RESUME_GUIDE.md` Section 1:
   - Same domain → Education before Experience
   - Different domain → Experience before Education
5. Edit the `.tex` file directly. Follow every constraint in the guide: quantified bullets, action verbs, correct section order, no personal info beyond what is listed, ATS-safe structure.
6. Do not add sections that are not in the guide. Do not invent content — only use what the user provides.
7. Compile check: remind the user to run `pdflatex hozaifamoustafa_resume.tex` to generate the PDF.

### Key files
| File | Purpose |
|---|---|
| `hozaifamoustafa_resume.tex` | The resume source — edit this |
| `RESUME_GUIDE.md` | HR criteria, section ordering rules, formatting constraints |

---

## Workflow 2: Gap Analysis — "What Am I Missing?"

**Triggered by:** "what am I missing?", "what should I build next?", "how do I strengthen my resume?", "what projects should I focus on?", or any question about technical gaps.

### How to conduct this

1. Read `RESUME_GUIDE.md` Section 13 — it contains the full role-to-gap mapping table.
2. Read the user's current resume (either `hozaifamoustafa_resume.tex` or ask them to paste their Projects and Skills sections).
3. Ask the user for their target role if not clear from context.
4. Compare their current projects and skills against the required proof points for that role in the Section 13 table.
5. Identify the specific proof point that is absent or weakly represented.
6. Recommend the exact project from the table. Be concrete:
   - Project name (meaningful, not generic)
   - Tech stack
   - Scope (achievable in 1–2 weeks)
   - What the deployed artifact looks like (link, installable, notebook, etc.)
   - How to write it on the resume once built
7. For a structured prompt the user can take to any LLM, refer them to `gap_analysis_prompt.md`.

### Key files
| File | Purpose |
|---|---|
| `RESUME_GUIDE.md` Section 13 | Role → gap → recommended project mapping |
| `gap_analysis_prompt.md` | Prompt template for deeper personalized analysis |

---

## General Rules

- Never guess at the user's background — ask if it is not in the resume or context.
- Never add skills or experience the user did not provide.
- Every edit to the `.tex` file must be traceable to a rule in `RESUME_GUIDE.md`.
- If the user asks about a role not in the Section 13 table, apply the same methodology: identify the 2–3 proof points that role requires, find what is absent from their resume, and recommend a focused project.
