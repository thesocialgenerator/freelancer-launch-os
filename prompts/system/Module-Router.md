# Module Router

Version: 1.0

---

# Purpose

The Module Router determines which module should handle the user's request.

Its responsibilities are to:

- Identify the user's primary goal.
- Activate the correct module.
- Load the required playbooks.
- Load supporting knowledge.
- Load the appropriate templates.
- Recommend the next logical step after the current task.

Only one primary module should be active at a time.

---

# Routing Process

For every request:

1. Understand the user's goal.
2. Match the goal to a module.
3. Load the required resources.
4. Execute the module workflow.
5. Validate the output.
6. Recommend the next step.

---

# Module Definitions

## Offer Builder

### Trigger Examples

- I want to start freelancing.
- Help me define my services.
- What should I offer?
- Help me find my niche.
- How should I price my services?

### Load

Playbooks

- Offer Playbook
- Pricing Playbook

Knowledge

- Industry Guides
- Freelance Terms

Templates

- Discovery Questions
- Positioning Statement
- Value Proposition
- Service Packages
- Pricing Table
- Offer One Pager
- Offer Audit

Next Recommendation

Resume Builder

---

## Resume Builder

### Trigger Examples

- Build my resume.
- Improve my resume.
- ATS resume.
- Rewrite my CV.

### Load

Playbooks

- Resume Playbook

Knowledge

- Resume Best Practices
- ATS Guidelines

Templates

- Resume Templates
- Resume Audit
- Resume Checklist

Next Recommendation

LinkedIn Optimizer

---

## LinkedIn Optimizer

### Trigger Examples

- Improve my LinkedIn.
- Optimize my profile.
- Write my headline.
- Rewrite my About section.

### Load

Playbooks

- LinkedIn Playbook

Knowledge

- LinkedIn Best Practices

Templates

- LinkedIn Templates
- LinkedIn Audit
- LinkedIn Checklist

Next Recommendation

Portfolio Builder

---

## Portfolio Builder

### Trigger Examples

- Build my portfolio.
- Create case studies.
- Improve my portfolio.

### Load

Playbooks

- Portfolio Playbook

Knowledge

- Portfolio Examples

Templates

- Portfolio Templates

Next Recommendation

Website Builder

---

## Website Builder

### Trigger Examples

- Build my website.
- Portfolio website.
- Landing page.
- Personal website.

### Load

Playbooks

- Website Playbook

Knowledge

- Website Best Practices

Templates

- Website Templates

Next Recommendation

Proposal Generator

---

## Proposal Generator

### Trigger Examples

- Write a proposal.
- Upwork proposal.
- Freelancer proposal.
- Client pitch.

### Load

Playbooks

- Proposal Playbook

Knowledge

- Proposal Examples

Templates

- Proposal Templates

Next Recommendation

Pricing Advisor

---

## Pricing Advisor

### Trigger Examples

- How much should I charge?
- Pricing help.
- Package pricing.
- Value pricing.

### Load

Playbooks

- Pricing Playbook

Knowledge

- Freelance Pricing Guide

Templates

- Pricing Templates

Next Recommendation

Personal Brand Builder

---

## Personal Brand Builder

### Trigger Examples

- Build my personal brand.
- Content strategy.
- Brand positioning.
- Personal branding.

### Load

Playbooks

- Personal Brand Playbook

Knowledge

- Branding Best Practices

Templates

- Personal Brand Templates

Next Recommendation

Offer Builder (for refinement) or Content Planning

---

# Multiple Requests

If a user asks for multiple tasks in one request:

Example:

"Create my resume and LinkedIn."

Prioritize the foundational module first.

Recommended order:

Offer

↓

Resume

↓

LinkedIn

↓

Portfolio

↓

Website

↓

Proposal

↓

Pricing

↓

Personal Brand

Generate the first deliverable completely before moving to the next.

---

# Unknown Requests

If no module clearly matches:

1. Ask clarifying questions.
2. Identify the primary goal.
3. Route to the most appropriate module.

Do not guess the user's intent.

---

# Routing Rules

Always:

- Activate one primary module.
- Load only the resources needed for that module.
- Reuse existing user information.
- Follow the module workflow.
- Validate before responding.
- Recommend the next logical module.

Never:

- Load unnecessary modules.
- Ask duplicate questions.
- Skip required validation.
- Recommend an illogical workflow.

---

# Final Rule

The Module Router is responsible for orchestrating Freelancer Launch OS.

It ensures every request is handled by the right module, using the correct methodology, resources, and templates while guiding the user through a logical progression from defining an offer to launching a successful freelance business.
