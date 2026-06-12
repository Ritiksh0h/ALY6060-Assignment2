# ALY6060 — Stakeholder Engagement Gap Dashboard: AI Implementation

**Course:** ALY6060: Decision Support & Business Intelligence  
**Student:** Ritik Shah  
**University:** Northeastern University  
**Live Dashboard:** [stakeholder-survey.netlify.app](https://stakeholder-survey.netlify.app)

---

## Problem Statement

Organizations rolling out AI tools face a critical stakeholder engagement challenge: not all departments are equally prepared, informed, or supported. This internal survey identifies **which departments have the largest stakeholder engagement gap** during AI implementation at a retail / e-commerce company — and prioritizes them for targeted intervention using a multi-dimensional quadrant model.

The dashboard answers one central question for decision-makers: **Who needs stakeholder engagement the most, and why?**

---

## Repository Structure

```
ALY6060-Assignment2/
│
├── index.html                           # Part 2 — Interactive multi-page dashboard (live on Netlify)
├── ALY6060_Survey_Final.csv             # Part 2 — Toy dataset (100 responses, 7 departments)
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

| # | Question | Response Type | Purpose |
|---|----------|--------------|---------|
| Q1 | How ready do you feel to adopt and use AI tools in your current role? | 1–5 rating scale | Baseline capability per department |
| Q2 | How adequate is the AI-related training your department has received? | 1–5 rating scale | **Primary X-axis** of engagement quadrant |
| Q3 | How open and prepared is your team to adapt to AI-driven organizational change? | 1–5 rating scale | Resistance risk indicator |
| Q4 | How well does your team understand the quality and strategic value of your data? | 1–5 rating scale | **Primary Y-axis** of engagement quadrant |
| Q5 | How engaged do you feel as a stakeholder in the AI implementation process? | 1–5 rating scale | Direct engagement gap measurement |

### Quadrant Model

Departments are mapped on two axes — **Training Adequacy (Q2)** vs. **Data Quality Perception (Q4)** — to produce four engagement priority segments:

| Quadrant | Training | Data Perception | Priority | Action |
|----------|----------|-----------------|----------|--------|
| I | Low | High | 🔴 Engage First | Understands data value, lacks support — highest ROI |
| II | High | High | ✅ Champion | Already capable — leverage as peer mentors |
| III | Low | Low | 🟡 Engage Second | Needs awareness-building before training |
| IV | High | Low | 🔵 Monitor | Trained but not applying data thinking |

### Dataset

- **File:** `ALY6060_Survey_Final.csv`
- **Rows:** 100 simulated survey responses
- **Departments:** IT, Marketing, Finance, HR, Customer Service, Store Operations, Warehouse & Logistics
- **Columns:** RespondentID, Department, Q1–Q5 (all 1–5 rating scales)

### Dashboard Pages

- **Live:** [stakeholder-survey.netlify.app](https://stakeholder-survey.netlify.app)
- Open `index.html` locally in any browser — no install needed

| Page | Description |
|------|-------------|
| Executive Overview | Company-wide engagement health across all 5 dimensions |
| Engagement Quadrant | Bubble chart: Training Adequacy vs. Data Quality Perception — core prioritization view |
| Gradient Priority Map | Color-coded heatmap + gradient bars showing urgency across all depts and dimensions |
| Dept Deep-Dive | Select any department for full radar profile vs. company average |
| Action Plan | Evidence-based engagement recommendations with projected outcomes |
| Survey Design | Full survey question documentation with analytical purpose |

---

## Key Findings

- **Warehouse & Logistics** — Quadrant I (Engage First): 18 employees, training adequacy 1.4/5, data quality perception 4.4/5. Highest engagement gap, highest intervention ROI.
- **Finance** — Quadrant I (Engage First): Understands data value (4.3/5) but severely undertrained (2.3/5).
- **IT + Marketing** — Quadrant II (Champions): High training and data perception — designated as peer mentors.
- **Customer Service + Store Operations** — Quadrant III (Engage Second): Low awareness and low training — needs foundational work before tool rollout.

---

## Tools Used

- **Dashboard:** HTML, CSS, JavaScript, Chart.js 4.4.1
- **Report:** Microsoft Word (.docx)
- **Data:** Custom generated CSV (toy dataset with deliberate dept-level profiles)
