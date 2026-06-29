# LaTeX Resume Template

A clean, professional LaTeX resume template. Fork this repo and build your own resume in minutes.

---

## Preview

![Resume Preview](hozaifamoustafa_resume_preview.png)

See [`hozaifamoustafa_resume.pdf`](hozaifamoustafa_resume.pdf) for the full PDF.

---

## Getting Started

### 1. Fork or Clone

```bash
git clone https://github.com/HozaifaMoustafa/hozaifamoustafa-resume-latex.git
cd hozaifamoustafa-resume-latex
```

### 2. Install LaTeX

- **Windows:** [MiKTeX](https://miktex.org/) or [TinyTeX](https://yihui.org/tinytex/)
- **macOS:** [MacTeX](https://www.tug.org/mactex/)
- **Linux:** `sudo apt install texlive-full`

### 3. Edit the Template

Open [`hozaifamoustafa_resume.tex`](hozaifamoustafa_resume.tex) and replace the placeholder content with your own:

- Name & contact info
- Education
- Work experience
- Skills
- Projects

### 4. Compile

```bash
pdflatex hozaifamoustafa_resume.tex
```

This generates `hozaifamoustafa_resume.pdf`.

---

## Using with a Coding Agent

This repo is wired for coding agents (Claude Code, Cursor, Copilot, etc.) via `CLAUDE.md`. Once you open the repo in your agent, two commands work out of the box:

### Build your resume

Tell your agent:
> "Help me build my resume. I'm applying for [role]."

The agent will:
1. Read the HR guide and the `.tex` template
2. Ask you three questions: target role, whether your degree matches the field, and years of experience
3. Apply the correct section ordering and formatting rules
4. Edit the `.tex` file directly — no manual LaTeX required

### Find your technical gaps

Tell your agent:
> "What am I missing on my resume?"

The agent will:
1. Read your current Projects and Skills sections
2. Compare them against the proof points required for your target role
3. Recommend one specific project to build — with a name, tech stack, scope, and what the deliverable should look like

For a standalone prompt you can paste into any LLM (ChatGPT, Gemini, etc.), see [`gap_analysis_prompt.md`](gap_analysis_prompt.md).

---

## Resume Best Practices Guide

Before editing the template, read [`RESUME_GUIDE.md`](RESUME_GUIDE.md) — it covers:

- **Section ordering logic** based on your background (student vs. experienced, relevant vs. unrelated degree)
- ATS compatibility tips
- How to quantify achievements
- Common mistakes that cost interviews
- Tailoring your resume per application

---

## Project Structure

```
.
├── hozaifamoustafa_resume.tex           # Main resume source (edit this)
├── hozaifamoustafa_resume.pdf           # Compiled output
├── hozaifamoustafa_resume_preview.png   # README preview image
├── RESUME_GUIDE.md      # HR-informed guide: structure, ATS, gap analysis
├── gap_analysis_prompt.md               # Prompt template: "what am I missing?"
├── CLAUDE.md            # Coding agent instructions (both resume workflows)
├── LICENSE              # MIT License
└── README.md            # This file
```

---

## Why No Dates in Filenames?

**You do not need to rename files with dates** (e.g., `Resume_Jan2026.tex`, `Resume_Jun2026.tex`).

Git already tracks every change automatically:

```bash
# See full history of your resume
git log -- hozaifamoustafa_resume.tex

# See what changed in a specific commit
git show <commit-hash>

# Tag a milestone version (e.g., before a job application)
git tag v2026.06.22
git push origin v2026.06.22
```

Using dated filenames:
- Creates clutter
- Makes it harder for others to use as a template
- Defeats the purpose of version control

Keep one stable filename (`hozaifamoustafa_resume.tex`) and let Git handle the history.

---

## License

[MIT](LICENSE) - Feel free to use, modify, and share.
