# ALY6060 — Stakeholder Involvement & Analytics Tools Survey Dashboard

**Course:** ALY6060: Decision Support & Business Intelligence  
**Student:** Ritik Shah  
**University:** Northeastern University  

---

## Overview

This repository contains the deliverables for Assignment 2: Stakeholder Involvement. The project examines strategies for maintaining stakeholder commitment in data analytics projects, the consequences of low engagement, and how those strategies contribute to building a data-driven organizational culture.

Part 2 presents an internal stakeholder survey on employee satisfaction with analytics tools, powered by a toy dataset of 80 simulated responses across 7 departments, visualized through an interactive HTML dashboard.

---

## Repository Structure

```
ALY6060-Assignment2/
│
├── ALY6060_Assignment2_RitikShah.docx   # Part 1 — Written report (~1100 words, APA)
├── ALY6060_SurveyData.csv               # Part 2 — Toy dataset (80 responses, 7 columns)
├── ALY6060_Dashboard.html               # Part 2 — Interactive survey dashboard
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
| Q1 | How satisfied are you with the analytics tools provided? | 1–5 rating scale |
| Q2 | How often do you use data/analytics tools in your daily work? | Never / Rarely / Sometimes / Often / Always |
| Q3 | Do you feel adequately trained to use the analytics tools available? | Yes / Somewhat / No |
| Q4 | How much do analytics tools help you make better business decisions? | 1–5 rating scale |
| Q5 | How would you rate the overall quality of data you work with? | Poor / Fair / Good / Very Good / Excellent |

### Dataset

- **File:** `ALY6060_SurveyData.csv`
- **Rows:** 80 simulated survey responses
- **Departments:** Marketing, Finance, Operations, HR, Sales, IT, Product
- **Columns:** RespondentID, Department, Q1–Q5 responses

### Dashboard

- **File:** `ALY6060_Dashboard.html`
- Open in any modern browser — no server or install required
- **Charts included:**
  - KPI cards: avg satisfaction, avg decision impact, % trained, % regular users
  - Bar chart: tool satisfaction by department (Q1)
  - Donut chart: usage frequency distribution (Q2)
  - Donut chart: training adequacy breakdown (Q3)
  - Bar chart: decision impact by department (Q4)
  - Bar chart: data quality perception (Q5)
- **Interactive:** Filter all charts by department using the buttons at the top

---

## How to View the Dashboard

1. Clone or download this repository
2. Open `ALY6060_Dashboard.html` in any browser (Chrome, Firefox, Edge, Safari)
3. No dependencies or installations needed

```bash
git clone https://github.com/Ritiksh0h/ALY6060-Assignment2.git
cd ALY6060-Assignment2
open ALY6060_Dashboard.html   # macOS
# or double-click the file on Windows
```

---

## Tools Used

- **Dashboard:** HTML, CSS, JavaScript, Chart.js 4.4.1
- **Report:** Microsoft Word (.docx)
- **Data:** Custom generated CSV (toy dataset)
