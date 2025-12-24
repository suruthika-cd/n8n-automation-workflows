# ATS Resume Automation Workflow (n8n)

## Overview
This workflow automates the initial screening stage of a recruitment process
using **n8n automation** and **NLP-based analysis**.

It demonstrates how resumes can be automatically processed,
evaluated against job requirements, and routed based on eligibility.

---

## Workflow Steps

1. A candidate submits their details through a **Google Form** and uploads a resume.
2. The uploaded resume is automatically fetched by the workflow.
3. **NLP techniques** are used to extract skills and relevant keywords from the resume.
4. An **ATS score** is calculated by comparing extracted skills with predefined job requirements.
5. If the ATS score meets the eligibility criteria:
   - The resume is automatically forwarded to the **HR email**.
6. If the ATS score does not meet the criteria:
   - An automated **rejection email** is sent to the candidate within seconds.

---

## Automation Logic
- Trigger: Google Form submission (via webhook)
- Decision-making: IF / ELSE logic based on ATS score
- Actions:
  - Email routing
  - Automated candidate response

---

## Use Case
- Resume screening automation
- ATS eligibility evaluation
- Reducing manual effort in early recruitment stages

---

## Notes
- This workflow is designed for **learning and demonstration purposes**.
- Email routing and scoring logic are simplified representations.
- No real candidate data or production credentials are included.
