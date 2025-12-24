# ATS Eligibility Automation (n8n)

## Purpose
This workflow automates skill-based eligibility checking for job applicants.

It is designed to simulate how an ATS system evaluates candidate skills
against job requirements using conditional logic.

---

## Workflow Trigger
- Triggered using a **Webhook**
- Receives candidate skill input

---

## Workflow Logic
1. Candidate skills are received through the webhook
2. Required job skills are predefined
3. IF / ELSE logic compares both skill sets
4. Workflow decides:
   - Eligible candidate
   - Not eligible candidate

---

## Output
- Returns eligibility status
- Can trigger further actions such as notifications or responses

---

## Use Case
- Resume / ATS screening automation
- Skill eligibility checking
- Demonstration of decision-based workflows

---

## Notes
- This workflow is created for learning and demonstration purposes
- No real hiring decisions or sensitive data are involved
