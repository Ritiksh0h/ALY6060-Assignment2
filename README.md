# ALY6060 — AI Tool Adoption: Internal Stakeholder Survey Dashboard

**Course:** ALY6060: Decision Support & Business Intelligence  
**Student:** Ritik Shah  
**University:** Northeastern University  
**Live Dashboard:** [stakeholder-survey.netlify.app](https://stakeholder-survey.netlify.app)

---

## Problem Statement

Organizations rolling out AI tools face a critical stakeholder challenge: employees are often unprepared, undertrained, and uncertain about how AI will affect their roles. This internal survey investigates employee readiness, job-displacement concerns, satisfaction with current AI tools, training adequacy, and preferred AI solutions — providing actionable data to guide a more effective, people-centered AI implementation strategy.

---

## Repository Structure

```
ALY6060-Assignment2/
│
├── index.html                           # Part 2 — Interactive survey dashboard (live on Netlify)
├── ALY6060_AI_SurveyData.csv            # Part 2 — Toy dataset (80 responses, 7 columns)
├── ALY6060_Assignment2_RitikShah.docx   # Part 1 — Written report (~1100 words, APA)
└── README.md
```

---

## Part 1 — Written Report

The report answers three questions:
1. What strategies maintain stakeholder commitment throughout a project?
2. What are the negative consequences of low stakeholder involvement?
3. How do those strategies help build a data analytics culture?

Cited sources are from ALY6060 course lecture materials (Lessons 2-1, 2-2, and 2-4), including the Davenport & Harris framework on analyst-decision-maker trust.

---

## Part 2 — Internal Survey & Dashboard

### Survey Questions

| # | Question | Response Type |
|---|----------|--------------|
| Q1 | How ready do you feel to adopt AI tools in your current role? | 1–5 rating scale |
| Q2 | How concerned are you about AI tools replacing parts of your job? | Not Concerned / Slightly / Moderately / Very / Extremely Concerned |
| Q3 | How satisfied are you with the AI tools currently available to you at work? | 1–5 rating scale |
| Q4 | Has your organization provided adequate training and support for AI tool adoption? | Yes / Somewhat / No |
| Q5 | Which type of AI tool would most improve your productivity and reduce stress? | Automation / Data & Analytics / Writing & Communication / Scheduling / Customer Service AI |

### Dataset

- **File:** `ALY6060_AI_SurveyData.csv`
- **Rows:** 80 simulated survey responses
- **Departments:** Marketing, Operations, IT, HR, Finance, Sales, Leadership
- **Columns:** RespondentID, Department, Q1–Q5 responses

### Dashboard

- **Live:** [stakeholder-survey.netlify.app](https://stakeholder-survey.netlify.app)
- Open `index.html` locally in any browser — no install needed
- **Charts included:**
  - KPI cards: avg readiness, avg satisfaction, % trained, % high job concern
  - Bar chart: AI readiness by department (Q1)
  - Donut chart: job displacement concerns (Q2)
  - Bar chart: AI satisfaction by department (Q3)
  - Donut chart: training adequacy (Q4)
  - Bar chart: preferred AI tools for productivity & stress reduction (Q5)
- **Interactive:** Filter all charts by department

---

## Tools Used

- **Dashboard:** HTML, CSS, JavaScript, Chart.js 4.4.1
- **Report:** Microsoft Word (.docx)
- **Data:** Custom generated CSV (toy dataset)
