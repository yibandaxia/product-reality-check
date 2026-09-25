<div align="center">
<h1>Product Reality Check · 需求鉴真</h1>
 </div>  
<div align="center"><a href="README.md">English</a> ·
    <a href="README.zh-CN.md">简体中文</a>
</div>

<div align="center"> <img width="200" height="200" alt="product-reality-check" src="https://github.com/user-attachments/assets/eaadd4e5-b7ab-41c1-9e5e-a8ef7f3ae4fc" />
</div>

> A skeptical product-manager skill for turning vague ideas into testable product hypotheses.

AI has made it easier to build products. It has not made it easier to know **what deserves to be built**.

Product Reality Check helps founders, indie hackers, product managers, and solo builders examine an idea before committing serious time to it.

Instead of immediately answering:

> "Sounds promising. Build an MVP."

it works backward from the proposed solution:

**Idea → User → Scenario → Existing behavior → Alternatives → Pain → Value → Distribution → Product form → Validation**

The goal is not to kill ideas. The goal is to expose unsupported assumptions early enough that changing direction is still cheap.

## What it helps with

Use this skill when you want to answer questions such as:

- Is this a real problem or just an interesting feature?
- Who experiences the problem strongly enough to act?
- What do people do today instead?
- Is the pain frequent, costly, urgent, or merely annoying?
- Is there evidence of willingness to pay?
- Where could the first 100 users come from?
- Is the proposed product format actually the right one?
- Which niche is the best place to start testing?
- What is the cheapest experiment that could invalidate the idea?

## Core principles

### Behavior beats opinions

"I would use this" is weak evidence.

Someone already spending time, money, effort, or attention to solve the problem is much stronger evidence.

### Alternatives matter more than direct competitors

The strongest competitor may be:

- a spreadsheet
- a chat group
- search
- manual work
- an existing general-purpose tool
- a workaround
- doing nothing

"There are no competitors" is not automatically good news.

### Distribution is part of product discovery

A good solution without a realistic path to users is not yet a strong product opportunity.

The skill asks a concrete question early:

> Where could the first 100 users realistically come from?

### Validation should be cheaper than building

An MVP is not always the minimum-cost experiment.

Depending on the assumption, a better test may be:

- interviews
- landing pages
- fake-door tests
- waitlists
- community posts
- manual concierge services
- prototypes
- pre-orders
- search-demand research

## How it works

Start with a rough idea:

> I want to build a tool that helps remote teams reduce meeting overload.

The skill does not immediately judge the idea. It asks focused questions, usually 1–3 at a time, such as:

> What behavior made you believe meeting overload is painful enough to solve?

> What are teams already doing to reduce or avoid meetings?

> Who feels the cost most strongly: managers, individual contributors, or operations teams?

As evidence accumulates, the skill produces a **Product Opportunity Diagnosis**.

## Output

A completed diagnosis normally includes:

### 1. Problem definition

A concise statement in this form:

> When **[user]** is in **[scenario]** and wants to **[job]**, existing solutions fall short because **[problem]**, creating an opportunity for **[better approach]**.

### 2. Evidence map

Separates:

- observed evidence
- reasonable but unverified assumptions
- major unknowns

### 3. Main risks

Identifies the assumptions most likely to invalidate the opportunity.

### 4. Demand status

Uses evidence-based states rather than arbitrary scores:

- Strong evidence of real demand
- Demand exists but intensity is unproven
- Real problem, unclear business model
- Real problem, likely wrong product format
- Solution-first idea with unproven demand
- Currently appears to be a weak need

### 5. Possible product directions

For each plausible direction:

- target user
- core use case
- product format
- monetization path
- main risk

### 6. Critical assumptions

Focuses on the 1–3 assumptions that matter most.

### 7. Minimum validation experiment

Defines the cheapest experiment that can meaningfully test those assumptions.

### 8. Decision criteria

Explains what evidence would justify:

- continuing
- changing direction
- stopping

## Installation / usage

The runtime skill is intentionally compact and lives in [`SKILL.md`](./SKILL.md).

The full framework, rationale, and deeper methodology are kept separately in [`references/methodology.md`](./references/methodology.md), so agents can load a lighter instruction set without losing the underlying product-discovery framework.

You can copy `SKILL.md` into a skill-enabled agent or use it as a system / project instruction in an AI workspace that supports reusable instruction files.

Example sessions are available in [`examples/`](./examples/).

## Repository structure

```text
product-reality-check/
├── README.md
├── README.zh-CN.md
├── SKILL.md
├── LICENSE
├── references/
│   └── methodology.md
└── examples/
    ├── remote-meeting-tool.md
    ├── local-event-planner.md
    └── freelance-payment-reminder.md
```

## Who it is for

Especially useful for:

- indie hackers
- solo founders
- product managers
- startup teams
- AI builders
- people who generate more ideas than they can reasonably build

## What this skill is not

It is not:

- an idea scoring calculator
- a market-size generator
- a substitute for talking to users
- a tool for turning every idea into a business
- a cheerleader that assumes the proposed solution is correct

## Examples

See:

- [`examples/remote-meeting-tool.md`](./examples/remote-meeting-tool.md)
- [`examples/local-event-planner.md`](./examples/local-event-planner.md)
- [`examples/freelance-payment-reminder.md`](./examples/freelance-payment-reminder.md)

## Contributing

Useful contributions include:

- stronger discovery questions
- better failure-pattern detection
- improved validation experiments
- additional examples
- localization
- clearer decision criteria

The goal is not to make the skill more optimistic.

The goal is to make it better at discovering weak assumptions before users spend weeks building the wrong thing.

## License

MIT
