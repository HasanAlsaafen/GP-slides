---
marp: true
title: "CourseMate"
description: "AI-Powered Course Registration Platform"
theme: default
paginate: true
size: 16:9
header: "CourseMate"
footer: "PPU • Graduation Project"
style: |
  section {
    font-family: "Times New Roman", "Cambria", serif;
    padding: 56px 72px;
    line-height: 1.2;
  }

  header, footer {
    font-size: 16px;
    opacity: 0.8;
  }

  h1 {
    font-size: 48px;
    margin-bottom: 14px;
  }

  h2 {
    font-size: 38px;
    margin-bottom: 10px;
  }

  p, li {
    font-size: 30px;
  }

  li {
    margin: 10px 0;
  }

  .rule {
    height: 3px;
    width: auto;
    background: rgba(1, 37, 55, 0.3);
    margin: 12px 0 18px 0;
  }

  section.title {
    display: flex;
    flex-direction: column;
    justify-content: center;
    text-align: center;
  }

  .emph {
    font-weight: bold;
  }

  .small {
    font-size: 24px;
  }
---


<!-- _class: title -->

# CourseMate
## AI-Powered Course Registration Platform

<div class="rule"></div>

**Hasan Al-Saafin · Mais Arafeh · Isra Iqnaibi**  
**Supervisor:** Dr. Mohammad Jabari  
Palestine Polytechnic University

---

# Context & Motivation
<div class="rule"></div>

- Course registration is a **critical academic process**.
- At PPU, the current system is **Semi-Manual**.
- Heavy human intervention leads to:
  - delays,
  - human-induced bottlenecks
  - frequent registration errors.
- * AI and other technologies could be leveraged to enable intelligent automation.

---

# Problem Statement
<div class="rule"></div>

- Students face:
  - Limited semester-based academic planning increase students’ reliance on academic advising to ensure     proper course selection, understand academic warnings affecting registration, and improve their academic standing.
  - missed opportunities due to the absence of a notification system.
- Supervisors handle:
  - repetitive advising,
  - high workload during peak periods.
- Result: **inefficient, error-prone registration workflow**.

---

# Proposed Solution
<div class="rule"></div>

- **CourseMate**: an AI-powered registration assistant.
- Automatically:
  - validates academic rules,
  - detects conflicts,
  - recommends feasible schedules.
- Acts as a **decision-support system** for students and supervisors rather that a **System of Records**.

---


# Scope & Constraints
<div class="rule"></div>

- Focus on **Bachelor’s degree programs ecxipt medicine** only.
- Target users:
  - students,
  - academic supervisors.
- Key constraints:
  - limited database access,
  - legacy system integration,
  - continuous AI prompt refinement.

---

# Methodology 
<div class="rule"></div>

- Plan-driven **Waterfall methodology** with prototype validation.
- Selected due to:
  - rule-sensitive academic domain,
  - need for early error detection,
  - the university workflow is phase-based, with the first semester dedicated to introduction and planning, and the second semester focused on implementation. 

