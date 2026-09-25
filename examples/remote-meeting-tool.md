# Example — Remote Meeting Reduction Tool

## Starting idea

> I want to build a tool that helps remote teams reduce unnecessary meetings.

## Weak response

A weak product-analysis assistant might immediately say:

> Remote work is growing, meeting fatigue is common, and AI can summarize discussions. This has strong potential. Build an MVP with calendar integrations and AI summaries.

This skips the most important question: **what behavior proves the problem is strong enough to create a new product?**

## Better discovery path

### Step 1 — Identify the strongest user

Instead of asking whether "remote workers" have too many meetings:

> Who feels the cost most strongly today — managers, individual contributors, project leads, or operations teams?

Suppose the user answers:

> Engineering managers. They spend a lot of time in recurring sync meetings.

### Step 2 — Recover actual behavior

Ask:

> What are those managers doing today to reduce meeting load?

Possible evidence:

- cancelling recurring meetings manually
- asking for written updates first
- using async standup tools
- merging meetings
- reviewing recordings at high speed

This is stronger than simply saying "meeting fatigue is common."

### Step 3 — Identify the actual job

The job may not be:

> "Have fewer meetings."

It may instead be:

> "Stay informed without attending every discussion."

That opens several product forms:

- async status workflow
- meeting decision log
- selective attendance assistant
- manager digest
- workflow integration

### Step 4 — Stress-test

Important failure questions:

- Are existing calendar and collaboration tools already good enough?
- Is the problem caused by company culture rather than missing software?
- Would reducing meetings require behavior change that software cannot enforce?
- Is this a standalone product or a feature inside existing collaboration software?

### Step 5 — Minimum validation

Before building a full product:

1. Interview 8–12 engineering managers who manage distributed teams.
2. Ask for the last three meetings they considered unnecessary.
3. Document what they did before, during, and after those meetings.
4. Offer a manual weekly "meeting reduction audit" based on their calendars.
5. Measure whether they act on the recommendations.

## Example diagnosis

**Demand status:** Demand exists but intensity is unproven.

**Critical assumption:** Managers will change workflow, not merely complain about meeting overload.

**Cheapest next test:** Manual calendar audit with a small group of managers.
