# Resume Best Practices — An HR-Informed Guide

Practical criteria for writing a resume that passes both ATS filters and human review.
Applies whether you are a student, a career changer, or a seasoned professional.

---

## 1. The First Rule: Section Ordering Depends on Your Background

This is the most common structural mistake people make.

### Is your degree in the same field as the job you're applying for?

```
Yes → Education comes BEFORE Experience
No  → Experience comes BEFORE Education
```

**Why it matters:**  
Recruiters read top-down. If your degree is directly relevant (e.g., Computer Science degree → Software Engineering role), lead with it — it validates everything that follows. If your degree is unrelated (e.g., Economics degree → Data Analyst role), your work history and skills are more convincing proof than your major, so lead with those instead.

### Recommended section order by profile

| Profile | Recommended Order |
|---|---|
| Student / recent grad (relevant degree) | Education → Skills → Projects → Experience |
| Student / recent grad (unrelated degree) | Skills → Projects → Experience → Education |
| Experienced (domain-matched degree) | Experience → Education → Skills |
| Experienced (career changer) | Skills → Experience → Education |
| Experienced (10+ years) | Summary → Experience → Skills → Education |

---

## 2. Length

| Experience Level | Target Length |
|---|---|
| 0–3 years | 1 page — strictly |
| 3–10 years | 1–2 pages |
| 10+ years | 2 pages max |

**Rule:** Every line must justify its existence. If removing it doesn't hurt you, remove it.

---

## 3. Contact Information

Include at the top:
- Full name (larger font)
- Professional email (`firstname.lastname@gmail.com`, not `gamer2003@hotmail.com`)
- Phone number (with country code if applying internationally)
- LinkedIn URL (customized: `linkedin.com/in/firstname-lastname`)
- GitHub / Portfolio (if relevant to the role)
- City and country — **no full street address**

**Do not include:** photo, date of birth, marital status, nationality (unless explicitly required by local norms or the job posting).

---

## 4. Summary / Objective (Optional)

Use only if you have 10+ years of experience or are making a significant career change.

- 2–3 sentences maximum
- Describes who you are, what you bring, and what you are looking for
- Tailored to the specific role — never generic

**Skip it** if you are a student or have under 5 years of experience. The space is better used for actual content.

---

## 5. Experience Section

### Format each role as:

```
Job Title | Company Name | City, Country | Month Year – Month Year
- Achievement or responsibility
- Achievement or responsibility
```

### The quantification rule

Every bullet that can be quantified, should be:

| Weak | Strong |
|---|---|
| Improved system performance | Reduced API response time by 40% by caching query results |
| Managed a team | Led a team of 6 engineers across 3 time zones |
| Built internal tools | Built an internal dashboard used by 200+ employees daily |

**Formula:** `Action verb + what you did + measurable impact`

### Action verbs that signal ownership

Architected, Automated, Built, Cut, Delivered, Designed, Drove, Engineered, Implemented, Increased, Led, Launched, Migrated, Optimized, Reduced, Refactored, Shipped, Solved, Spearheaded

### Rules
- Use **past tense** for previous roles, **present tense** for current role
- 3–5 bullets per role for recent positions; 1–2 for older ones
- Remove roles older than 10–15 years unless directly relevant
- List only the last 2–3 positions if you have many

---

## 6. Education Section

```
Degree, Major | University Name | City, Country | Year Graduated
GPA: X.X / 4.0  (only include if ≥ 3.3)
Relevant coursework: ... (only include for students with no experience)
```

- Include honors, scholarships, or dean's list if notable
- Drop GPA once you have 3+ years of experience (work history speaks louder)
- Do not list high school once you have a university degree

---

## 7. Skills Section

- **Group by category:** Languages, Frameworks, Tools, Platforms, Databases, Soft Skills
- **Do not rate yourself** with stars, bars, or percentages — they are meaningless to reviewers
- List only skills you can defend in an interview
- Mirror the keywords in the job description (ATS optimization)

**Example:**
```
Languages:    Python, SQL, JavaScript
Frameworks:   FastAPI, React, dbt
Tools:        Git, Docker, Airflow
Platforms:    AWS (S3, Lambda, Redshift), Azure
```

---

## 8. Projects Section

Especially valuable for students and career changers.

```
Project Name | github.com/you/project
- What it does in one sentence
- Tech stack used
- Scale or impact (users, data volume, stars, etc.)
```

- List 2–4 projects max
- Prefer projects with real users, deployed apps, or open-source activity
- Name the project, not just the tech ("Inventory Forecasting System" beats "Python ML Project")

---

## 9. ATS (Applicant Tracking System) Compatibility

Most companies filter resumes through software before a human sees them.

**Pass the filter:**
- Use standard section headings: `Experience`, `Education`, `Skills`, `Projects`
- Avoid tables, columns, text boxes, headers/footers — they confuse parsers
- Submit as PDF unless the job posting specifically asks for `.docx`
- Include exact keywords from the job description (tools, frameworks, job titles)
- Spell out acronyms at least once: `Continuous Integration (CI)`

**This template is ATS-friendly by design.** The LaTeX source uses a single-column layout with clean section headings.

---

## 10. Tailoring vs. Generic Resumes

A single generic resume sent to 100 companies will underperform a tailored resume sent to 10.

For each application:
1. Read the job description carefully
2. Add the specific tools/skills they mention (if you have them)
3. Reorder bullets to lead with the most relevant experience
4. Adjust your title/summary to match the role

This takes 10–15 minutes per application and meaningfully improves your callback rate.

---

## 11. Common Mistakes That Cost Interviews

| Mistake | Fix |
|---|---|
| Responsibilities without results | Add numbers and outcomes to every bullet |
| Dense walls of text | Max 2 lines per bullet; use white space |
| Outdated or irrelevant jobs | Cut roles older than 10 years or unrelated to the target role |
| Inconsistent formatting | Same date format, font size, and bullet style throughout |
| Typos and grammar errors | Proofread twice; use Grammarly for a final pass |
| Generic objective statement | Remove it or write a targeted 2-sentence summary |
| Emailing a `.tex` or `.docx` | Always export and send as PDF |
| Listing every job you have ever had | Curate: only what is relevant and recent |
| Skills you cannot defend in an interview | Remove them — interviewers will test you |

---

## 12. The One-Pass Test

After writing your resume, read it as if you are a recruiter with 8 seconds per page:

1. Does the top third make your value immediately clear?
2. Are achievements quantified?
3. Is the formatting consistent and easy to scan?
4. Are the keywords from the job description present?
5. Is every word earning its space?

If you hesitate on any of these, revise before sending.

---

## Sources and Inspiration

These criteria are derived from publicly available HR research, ATS documentation, and hiring manager guides including:

- SHRM (Society for Human Resource Management) resume guidelines
- Greenhouse and Lever ATS parsing documentation
- Harvard OCS Resume & Cover Letter Guide
- LinkedIn Talent Insights hiring trend data

---

*This guide lives in the [hozaifamoustafa-resume-latex](https://github.com/HozaifaMoustafa/hozaifamoustafa-resume-latex) repository. Fork the template, follow the guide, ship a better resume.*
