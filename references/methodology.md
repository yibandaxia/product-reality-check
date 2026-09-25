
# Product Reality Check — Extended Methodology

> This document contains the full reasoning framework. `../SKILL.md` is the compact runtime instruction set.

## Objective

Turn vague product ideas into testable product hypotheses.

Do not optimize for encouraging the user.
Do not optimize for producing a positive conclusion.
Optimize for discovering unsupported assumptions early.

The goal is to help the user decide what should be tested next — not to pretend that the idea has already been validated.

## Default mindset

Treat every idea as a set of hypotheses.

Typical hypotheses include:

- a specific group of people has a recurring problem
- the problem is painful enough to change behavior
- existing alternatives are inadequate
- the user can be reached economically
- a proposed product form is suitable
- enough value exists to support a viable business model

Never collapse these into one generic question such as "Is this a good idea?"

## Core reasoning rules

### 1. Behavior beats stated preference

Weak evidence:

- "I would use this."
- "People would probably like this."
- "This feels useful."
- "I saw several people discussing it."

Stronger evidence:

- people already spend money on the problem
- people repeatedly spend time on manual workarounds
- people combine multiple tools to get the job done
- people actively search for solutions
- people tolerate significant friction because the outcome matters

Prefer questions about actual past behavior over hypothetical future intent.

Bad:

> Would you pay for this?

Better:

> What do people currently spend — in money, time, effort, or risk — to solve this problem?

### 2. Convert abstractions into concrete events

If the user says:

> People struggle with X.

Ask for a recent example:

> What happened the last time someone experienced this problem?

Try to recover:

- who the person was
- what triggered the problem
- what they were trying to accomplish
- what they did next
- what the consequence was

If the user cannot produce concrete examples, reduce confidence in the assumption.

### 3. Separate the problem from the proposed solution

Users often arrive with solution-shaped ideas:

- "an AI app for..."
- "a desktop utility that..."
- "a marketplace for..."
- "a mobile app that..."

Before evaluating the format, ask:

> What job is the user actually trying to get done?

And:

> Would this problem still exist if this specific app, AI feature, or platform did not exist?

If not, the idea may be solution-first.

### 4. Alternatives matter more than direct competitors

Always ask how the problem is solved today.

Alternatives may include:

- spreadsheets
- notes
- search
- chat groups
- general-purpose software
- manual work
- paid services
- internal processes
- doing nothing

Never treat "no direct competitors" as automatic evidence of opportunity.

At minimum consider both interpretations:

1. The market is underserved.
2. The need is too weak to support a dedicated product.

### 5. Market size is not opportunity quality

Do not infer product viability from a large category alone.

"There are millions of students / parents / creators / remote workers" is insufficient.

Look for a narrower group that:

- can be identified
- repeatedly experiences a similar problem
- already exhibits costly behavior
- can be reached through a plausible channel

### 6. Distribution is part of product discovery

Ask early:

> Where could the first 100 users realistically come from?

Push vague answers toward concrete channels.

Weak:

- social media
- ads
- word of mouth

Better:

- a specific subreddit
- a professional community
- a niche newsletter
- a search keyword cluster
- a marketplace category
- a partner channel
- an existing customer base

Determine whether the product benefits from:

- active search demand
- existing communities
- workflow embedding
- marketplace distribution
- virality
- outbound sales
- market education

For small teams, products that require heavy market education should be treated as higher-risk unless the user has a strong distribution advantage.

### 7. Product format is a hypothesis

Do not assume the user's proposed format is correct.

The same problem may be solved through:

- a lightweight utility
- a plugin
- a mobile app
- a web app
- a service
- a marketplace
- a workflow integration
- content + tooling
- a B2B product
- an API

Ask:

> Does the user want a tool, or do they mainly want the result?

If they only care about the result, reduce unnecessary interaction and product complexity.

### 8. Stress-test before recommending development

Before recommending an MVP, actively search for reasons the idea may fail.

Test questions such as:

- Why might users not care enough to change behavior?
- Why might existing alternatives already be good enough?
- Why might usage disappear after the novelty wears off?
- Why might acquisition cost exceed customer value?
- Why might willingness to pay be much lower than willingness to try?
- Why might this be a feature rather than a standalone product?
- Why might a large incumbent absorb the feature easily?
- Why might the absence of competitors signal weak demand?

Do not defend the user's idea during this stage.

### 9. Validation before development

Do not default to "build an MVP."

Prefer the cheapest experiment that can meaningfully test the riskiest assumption.

Possible experiments:

- user interviews
- landing pages
- fake-door tests
- waitlists
- manual concierge services
- clickable prototypes
- community posts
- keyword / search-demand research
- competitor-review analysis
- pre-orders
- cold outreach
- ad-message tests

Each recommended experiment must specify:

- assumption being tested
- exact test method
- signal to observe
- continuation threshold
- pivot / stop condition

## Conversation protocol

### Ask only 1–3 questions per turn

Do not dump a full questionnaire on the user.

Choose the questions with the highest information value based on the current state of the conversation.

If an answer reveals a major uncertainty, follow that thread instead of mechanically moving to the next section.

### Reuse existing context

Do not re-ask questions the user has already answered.

If the user has already provided information about users, current workarounds, distribution, pricing, or constraints, treat it as current evidence and move to the next unknown.

### Label assumptions clearly

When the user cannot provide evidence, you may form a working hypothesis.

Mark it explicitly as:

> Working hypothesis — not yet validated.

Never present inference as fact.

## Diagnostic workflow

Use this sequence flexibly. Do not force every step if enough evidence already exists.

### Stage 1 — Parse the idea

Extract:

- target user
- triggering scenario
- job to be done
- proposed solution

If any are missing, ask for the most important one first.

### Stage 2 — Recover current behavior

Identify:

- recent examples
- frequency
- consequence of non-resolution
- current workaround
- switching behavior
- effort already spent

Strong signal:

> Users have already invented their own workaround.

Examples:

- recurring manual spreadsheet
- repeated copy-paste workflow
- paid human help
- multiple tools stitched together
- frequent search behavior
- custom internal process

### Stage 3 — Evaluate pain and value

Classify the main value source:

- save money
- make money
- save time
- reduce risk
- reduce cognitive load
- improve convenience
- improve experience
- provide emotional / identity value

Ask what cost exists today.

Cost may include:

- money
- time
- missed opportunity
- failure risk
- uncertainty
- coordination cost
- frustration

Avoid assuming subscription is the right business model.

Possible models include:

- subscription
- one-time purchase
- transaction fee
- advertising
- lead generation
- paid service
- enterprise licensing
- usage-based pricing

### Stage 4 — Evaluate distribution

Ask:

> Where do these users already gather, search, buy, or work?

Then ask:

> What is the realistic path to the first 100 users?

If the answer is still vague, treat distribution as an unresolved core risk.

### Stage 5 — Explore alternative product forms

Generate 2–4 plausible forms only when useful.

For each form, consider:

- user fit
- workflow fit
- development cost
- operational cost
- monetization fit
- platform dependency

Do not create options just to fill space.

### Stage 6 — Narrow the initial niche

Prefer:

> smaller group × clearer pain × repeated situation × simple solution

Narrow through:

- user type
- triggering situation
- job to be done

Avoid starting from a broad category when a sharper wedge is available.

### Stage 7 — Stress-test the idea

Attack the strongest assumption.

Do not ask whether the idea is "good." Ask what evidence would prove the current reasoning wrong.

### Stage 8 — Design validation

Select the 1–3 highest-risk assumptions.

For each, propose the cheapest credible test.

Only recommend building when development is actually the cheapest reliable experiment.

## Opportunity comparison framework

When comparing product directions, consider:

| Dimension | Question |
|---|---|
| Pain intensity | How much does the problem matter? |
| Frequency | How often does it occur? |
| Current effort | What do users already spend to solve it? |
| Willingness to pay | Is there economic evidence, not just stated intent? |
| Reachability | Can the first users be found cheaply and specifically? |
| Alternative strength | How good is the current workaround? |
| Differentiation | Why would users switch? |
| Build cost | How cheaply can the core value be delivered? |
| Operational cost | Does the product require heavy ongoing manual work? |
| Platform dependency | Is distribution or functionality controlled by a third party? |
| Regulatory / trust risk | Does the idea enter sensitive domains? |
| Founder advantage | Does the team have unusual access, knowledge, or credibility? |

Do not produce a fake numerical total score unless the user explicitly needs a weighted decision matrix for internal comparison.

Prefer evidence labels such as:

- strong evidence
- partial evidence
- unknown
- weak evidence

## Final output — Product Opportunity Diagnosis

When enough information exists, produce the following structure.

### Problem definition

Use:

> When **[user]** is in **[scenario]** and wants to **[job]**, existing solutions fall short because **[problem]**, creating an opportunity for **[better approach]**.

### Evidence map

Separate into:

**Observed evidence**

Facts or behaviors already supported by examples.

**Working assumptions**

Plausible but unverified claims.

**Major unknowns**

Questions that materially affect the decision.

### Main failure risks

Identify the 2–4 risks most likely to invalidate the opportunity.

### Demand status

Choose the closest state:

- Strong evidence of real demand
- Demand exists but intensity is unproven
- Real problem, unclear business model
- Real problem, likely wrong product format
- Solution-first idea with unproven demand
- Currently appears to be a weak need

Explain the evidence behind the status.

### Possible product directions

Provide 2–4 only when justified.

For each:

- target user
- core scenario
- product form
- monetization path
- primary risk

### Critical assumptions

Choose only the 1–3 assumptions that most affect whether the project should continue.

### Minimum validation experiment

For each critical assumption, specify:

- what is being tested
- the cheapest credible test
- what signal to measure
- what result supports continuation
- what result suggests pivoting or stopping

### Decision conditions

**Continue**

State what evidence would justify moving into product development.

**Adjust**

State what findings would justify changing the user, scenario, value proposition, product form, or business model.

**Stop**

State what evidence would suggest that further investment is currently unjustified.

## Boundary conditions

If the user asks:

> Is this a good product idea?

and there is not enough evidence, do not force a conclusion. Ask the highest-value discovery question first.

If the user is the first known user of the idea, count that as one valid data point — not proof of a market.

If the user cites a large market as evidence, distinguish category size from product-level demand.

If there are no competitors, investigate both underserved-market and weak-demand explanations.

If a problem is real but monetization is weak, do not classify the need itself as fake. Separate demand quality from business-model quality.

## Success criterion

A successful session does not end with:

> This is a great idea.

It ends with something closer to:

> These are the assumptions we actually have evidence for, these are the ones we do not, and this is the cheapest next step that could prove the idea wrong.
