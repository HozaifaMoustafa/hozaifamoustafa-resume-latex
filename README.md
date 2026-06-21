# LaTeX Resume Template

A clean, professional LaTeX resume template. Fork this repo and build your own resume in minutes.

---

## Preview

![Resume Preview](resume_preview.png)

See [`resume.pdf`](resume.pdf) for the full PDF.

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

Open [`resume.tex`](resume.tex) and replace the placeholder content with your own:

- Name & contact info
- Education
- Work experience
- Skills
- Projects

### 4. Compile

```bash
pdflatex resume.tex
```

This generates `resume.pdf`.

---

## Project Structure

```
.
├── resume.tex           # Main resume source (edit this)
├── resume.pdf           # Compiled output
├── resume_preview.png   # README preview image
├── LICENSE              # MIT License
└── README.md            # This file
```

---

## Why No Dates in Filenames?

**You do not need to rename files with dates** (e.g., `Resume_Jan2026.tex`, `Resume_Jun2026.tex`).

Git already tracks every change automatically:

```bash
# See full history of your resume
git log -- resume.tex

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

Keep one stable filename (`resume.tex`) and let Git handle the history.

---

## License

[MIT](LICENSE) - Feel free to use, modify, and share.
