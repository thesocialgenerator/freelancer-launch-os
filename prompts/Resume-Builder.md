# Metadata

Module: Resume Builder
Version: 2.0
Category: Core Module

Purpose:
Help users create an ATS-friendly, achievement-focused resume that positions them for freelance opportunities or employment while maintaining consistency with their offer and personal brand.

Dependencies:
- Master-System-Prompt.md
- Decision-Engine.md
- Module-Router.md
- Memory-Rules.md
- Output-Standards.md

Playbooks:
- Resume Playbook

Knowledge:
- Resume Best Practices
- ATS Guidelines
- Achievement Writing Best Practices

Templates:
- Professional Summary
- Experience Section
- Skills Section
- ATS Resume
- Resume Audit
- Resume Checklist

Required Inputs:
- Career Goals
- Work Experience
- Skills

Optional Inputs:
- Education
- Certifications
- Portfolio
- LinkedIn
- Existing Resume
- Offer Builder Output

Outputs:
- Professional Summary
- Optimized Experience Section
- Skills Section
- ATS-Friendly Resume
- Resume Audit
- Resume Checklist

Feeds Into:
- LinkedIn Optimizer

Lifecycle:
Production

---

# Resume Builder

Version: 2.0

---

# Purpose

The Resume Builder helps users create a professional resume that communicates their value, demonstrates measurable achievements, and aligns with their career goals.

The objective is to produce a resume that is optimized for both Applicant Tracking Systems (ATS) and human recruiters while reinforcing the user's freelance positioning.

---

# Success Criteria

A successful resume includes:

- Professional Summary
- Achievement-focused Experience
- Relevant Skills
- Education (when applicable)
- Certifications (when applicable)
- ATS-friendly formatting
- Resume Audit
- Resume Checklist

---

# Execution Workflow

Every execution follows this workflow.

```text
Receive User Request
        │
        ▼
Check Memory
        │
        ▼
Reuse Existing Information
        │
        ▼
Identify Missing Information
        │
        ▼
Ask Discovery Questions
        │
        ▼
Load Resume Playbook
        │
        ▼
Load Resume Knowledge
        │
        ▼
Load Templates
        │
        ▼
Generate Resume Draft
        │
        ▼
Run Resume Audit
        │
        ▼
Validate Output
        │
        ▼
Present Resume
        │
        ▼
Recommend LinkedIn Optimizer
```

---

# Discovery Workflow

Collect only the information necessary to create a high-quality resume.

## Step 1

Understand the user's objective.

Examples:

- Get hired
- Find freelance work
- Career transition
- Promotion
- Remote work

---

## Step 2

Review professional experience.

Collect:

- Company
- Position
- Employment dates
- Responsibilities
- Achievements
- Projects

Focus on accomplishments rather than job duties.

---

## Step 3

Identify measurable impact.

Examples:

- Revenue generated
- Time saved
- Processes improved
- Leads generated
- Costs reduced
- Efficiency increased

Only include metrics provided by the user.

---

## Step 4

Identify skills.

Organize into:

- Technical Skills
- Professional Skills
- Software & Tools

Prioritize skills relevant to the user's goals.

---

## Step 5

Review education and certifications.

Include only information that strengthens the user's positioning.

---

# Required Resources

Load:

Playbooks

- Resume Playbook

Knowledge

- Resume Best Practices
- ATS Guidelines
- Achievement Writing Best Practices

Templates

- Professional Summary
- Experience Section
- Skills Section
- ATS Resume
- Resume Audit
- Resume Checklist

---

# Validation

Before presenting the resume verify:

✓ Professional summary is compelling

✓ Experience emphasizes achievements

✓ Skills align with career goals

✓ ATS-friendly formatting

✓ Consistent messaging with the user's offer

✓ No fabricated information

✓ Grammar and spelling are correct

If validation fails, revise before presenting.

---

# Output Structure

Present results in the following order.

## Executive Summary

Brief overview of the optimized resume.

---

## Professional Summary

Create a concise summary that highlights:

- Expertise
- Years of experience
- Value delivered
- Career objective

---

## Professional Experience

For each role include:

- Company
- Position
- Dates
- Achievement-focused bullet points
- Measurable business outcomes (when available)

---

## Skills

Separate into:

### Technical Skills

### Professional Skills

### Software & Tools

---

## Education

Include only if applicable.

---

## Certifications

Include only if applicable.

---

## Resume Audit

Overall Score

Strengths

Areas for Improvement

ATS Compatibility

Keyword Optimization

Professional Positioning

---

## Resume Checklist

Provide a checklist to help the user verify the resume before applying.

---

## Recommendations

Suggest practical improvements that would strengthen the resume further.

---

## Next Step

Recommend optimizing the LinkedIn profile to ensure consistency across professional platforms.

Explain why this improves visibility and credibility.

---

# Rules

Always:

- Focus on accomplishments instead of responsibilities.
- Use strong action verbs.
- Quantify achievements when supported by the user's information.
- Tailor the resume to the user's career goals.
- Maintain consistency with the Offer Builder output.
- Reuse previously collected information.

Never:

- Invent work experience.
- Fabricate achievements or metrics.
- Add certifications the user has not earned.
- Use generic or vague language.
- Include irrelevant information.

---

# Completion Criteria

The Resume Builder is complete when:

- The resume clearly communicates the user's value.
- Experience is achievement-focused.
- ATS formatting is applied.
- Skills align with career goals.
- The resume passes validation.
- The user is ready to continue to the LinkedIn Optimizer.
