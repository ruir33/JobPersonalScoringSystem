```markdown
# JobPersonalScoringSystem

**Job Personal Scoring System**  
*The purpose of all these prompts and steps is to improve your chances to get the job you want/need!*

---

## Overview

This system helps you **evaluate your CV against a Job Description (JD)** using a **personal scoring mechanism**. It generates:

- A **quantitative score** based on how well your profile matches the JD.
- **Personalized action plans** with realistic timelines to close skill/experience gaps.
- **ATS-friendly insights** to improve your resume's performance in Applicant Tracking Systems.

> **Note**: Originally designed with **Grok (xAI)**, but fully compatible with **ChatGPT, Gemini, Claude**, and other LLMs.  
> For best results: **Run the process across multiple models and compare outputs**. Use your judgment to create a final action plan that *feels right*.

> **Warning**: You still have to **execute the action plans**! No score improves without effort.

---

## Lazy Mode (Fast Report + Action Plans)

Ideal if you just want a **quick score + improvement roadmap** optimized for ATS.

---

### Step 1: Extract Weighted Requirements from Job Description

**Goal**: Generate a JSON with weighted importance for each JD requirement.

#### Instructions:
1. Go to **[www.grok.com](https://www.grok.com)** (or your preferred LLM interface)
2. Open file: `01.P.JD info extraction.txt`
3. **Paste the prompt**
4. **Attach your Job Description** (e.g., `JD.docx`, `.pdf`, `.txt`)
5. Run the prompt

> Output: JSON with requirements and weights (e.g., `"Python": 25`, `"Leadership": 15`, etc.)

---

### Step 2: Evaluate Your CV Against the JD

**Goal**: Score your CV based on the extracted JD weights.

#### Instructions:
1. Open file: `02.P.CV evaluation process.txt`
2. **Paste the prompt**
3. **Attach your CV in PDF** (e.g., `RuiRibeiro.20251126.pdf`)
4. **Include the JSON from Step 1** in the prompt (copy-paste)
5. Run the prompt

> Output:  
> - Match analysis per requirement  
> - **JSON with your personal scores**

---

### Step 3: Generate Final Report + Action Plans

**Goal**: Get a polished report with your **total score** and **actionable improvement plan**.

#### Instructions:
1. Open file: `03.P.Report elaboration.txt`
2. **Paste the prompt**
3. **Include both JSONs** (from Step 1 + Step 2)
4. Run the prompt

> Output:  
> - **Full report above JSON** → Save as `.docx` (preserves formatting) or `.txt`  
> - **Final JSON** (for tracking/progress)

---

### Step 4: Understand Your Results

Your report will include:

| Section | Description |
|-------|-----------|
| **Overall Score** | `/100` – How close you are to the ideal candidate |
| **Breakdown by Requirement** | Match % per skill/experience |
| **Personalized Action Plans** | Specific, prioritized steps |

#### Action Plan Timelines
| Timeline | Duration |
|--------|----------|
| `Immediate` | < 24 hours |
| `Really Short` | 1–3 days |
| `Short` | 1–2 weeks |
| `Short+` | 2–4 weeks |
| `Medium` | 1–2 months |
| `Medium+` | 1–3 months |

---

## Tips for Best Results

- Use **clean, well-formatted** JD and CV files.
- Prefer **PDF** for CV (preserves layout).
- Run the full flow on **at least 2 LLMs** and merge the best action items.
- Update your CV **after each improvement cycle** and re-score.
- Track progress in a simple table:

```markdown
| Requirement | Initial Score | Target | Action Taken | New Score | Date |
|-------------|---------------|--------|--------------|-----------|------|
| Python      | 60/100        | 90     | Complete Codecademy Pro | 88/100    | 2025-12-20 |
```

---

## File Structure (Recommended)

```
JobPersonalScoringSystem/
│
├── JD/
│   └── YourJobDescription.docx
├── CV/
│   └── YourName.20251126.pdf
├── Prompts/
│   ├── 01.P.JD info extraction.txt
│   ├── 02.P.CV evaluation process.txt
│   └── 03.P.Report elaboration.txt
├── Outputs/
│   ├── 01_JD_weights.json
│   ├── 02_CV_scores.json
│   ├── 03_Final_Report.docx
│   └── Action_Plan_Progress.xlsx
└── README.md
```

---

## Final Words

> **This is not magic. It’s a mirror.**  
> The score shows where you stand.  
> The action plan shows where to go.  
> **Your effort makes the difference.**

**Good luck — go get that job!**

---

*Created with ❤️ using Grok (xAI) — Works with any LLM*  
*Last updated: December 2025*
```
