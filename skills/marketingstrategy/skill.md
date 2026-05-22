---
name: marketing-strategy-generator
description: build complete revenue-aligned marketing strategies for a specific company, business unit, product line, or market expansion effort. use when the user asks for a marketing strategy, go-to-market plan, demand generation strategy, positioning architecture, funnel plan, campaign priorities, pipeline model, kpi framework, or a 30-60-90 or 90-day marketing plan. apply this skill when the user provides only a company name and goal, when context is incomplete and must be researched, or when an existing plan needs to be upgraded into a more rigorous executive-ready strategy.
---

# Marketing Strategy Generator

## Overview

Create practical, executive-ready marketing strategies that tie marketing activity to revenue outcomes. Work from the user's brief first, then fill gaps with research when needed, and clearly separate confirmed facts from reasonable assumptions.

Use the bundled references deliberately:

- Read `references/strategy-framework.md` for the core planning model and output logic.
- Read `references/marketing-knowledge-pack.md` when you need proven frameworks, books, and strategic concepts.
- Read `references/source-library.md` when you want examples, blogs, newsletters, Substack publications, Medium pieces, or source ideas to deepen the work.

Do not dump source lists into the final answer. Use the references to improve judgment, prioritization, and explanation.

## Workflow

Follow this sequence:

1. Define the strategy brief.
2. Gather company and market context.
3. Choose the strategic posture.
4. Build the growth plan across positioning, demand, funnel, content, and measurement.
5. Pressure-test the plan using the bundled frameworks and examples.
6. Present the strategy in a consistent operator-friendly format.
7. End with risks, assumptions, and immediate next steps.

## 1) Define the strategy brief

Start by translating the request into a working brief. Capture:

- company, business unit, or offer in scope
- primary growth objective
- target customer or buying audience
- geography or market scope
- time horizon
- important constraints such as team size, budget, sales model, channel mix, or product maturity

If the user gives only a light prompt such as "create the marketing strategy for company x," proceed without blocking. Infer a sensible brief from available evidence and state assumptions explicitly.

## 2) Gather context

Prioritize sources in this order:

1. user-provided context in the conversation
2. uploaded files or connected internal sources if available
3. public research if the strategy depends on current company or market facts
4. bundled references for planning logic, examples, and strategic pattern recognition

Gather enough context to answer these questions:

- what the company sells
- who it sells to
- how complex the sale is
- whether the motion is product-led, sales-led, partner-led, or hybrid
- what category or competitors shape buyer expectations
- what proof points, traction, or market authority already exist

Do not pretend to know missing facts. When data is incomplete, make a reasonable assumption and label it as an assumption.

## 3) Choose the strategic posture

Decide which posture best fits the situation and write the strategy accordingly:

- **category creation / market education**: use when the company solves a problem buyers do not yet name clearly
- **competitive displacement**: use when the market is known and the company must win against established vendors
- **expansion / scale-up**: use when there is some traction and the priority is repeatable pipeline growth
- **enterprise authority build**: use when trust, credibility, and executive confidence matter more than broad reach
- **partner-amplified growth**: use when alliances, channels, or ecosystem relationships are a major route to pipeline

If more than one applies, choose a primary posture and note the secondary one.

## 4) Build the strategy

Unless the user asks for a shorter answer, include all sections below.

### Executive summary

Summarize:

- the growth goal
- the strategic posture
- the target market focus
- the core bet behind the strategy
- the expected marketing contribution to pipeline or revenue

### Company and market framing

Explain in plain language:

- what the company offers
- the market problem it solves
- why this matters now
- the commercial context affecting demand generation and sales motion

### ICP and segment priorities

Define:

- primary segment
- secondary segment(s)
- buyer roles and buying committee
- urgency triggers
- disqualifiers
- reasons to prioritize these segments now

### Positioning and messaging architecture

Develop:

- positioning statement
- 3 to 5 messaging pillars
- proof points for each pillar
- likely objections and rebuttals
- differentiated angle relative to the market

Keep the messaging specific enough to guide campaigns, sales enablement, and content.

### Demand generation strategy

Recommend the demand model across:

- account-based or broad-based acquisition approach
- inbound, outbound support, partner, event, lifecycle, and content motions
- major channels to prioritize
- channels to avoid or deprioritize if they are unlikely to match the sales motion

Tie the recommendation to sales complexity, deal size, and buying cycle.

### Funnel and pipeline model

Describe the funnel from awareness to opportunity. Include:

- key funnel stages
- performance objectives by stage
- lead or account qualification logic
- scoring or prioritization suggestions
- attribution and reporting standards
- the most likely structural conversion gaps to watch

Use directional targets when exact numbers are unavailable. Avoid fake precision.

### Content and market authority plan

Define:

- content themes tied to buyer pain and commercial intent
- flagship assets or campaigns
- executive thought leadership opportunities
- proof-building mechanisms such as case studies, benchmarks, research, or webinars
- owned channel priorities

### Sales and partnership alignment

Specify how marketing should operate as a revenue partner. Cover:

- campaign-to-sales handoff
- feedback loops with sales
- enablement needs
- account intelligence or target-list support
- partner co-marketing or alliance plays where relevant

### KPI and reporting framework

Recommend a measurement system that includes:

- pipeline creation
- marketing-attributed or marketing-influenced revenue
- conversion by stage
- campaign efficiency
- velocity
- win-rate support indicators
- brand or authority proxies only when they support the commercial story

Separate **north star metrics**, **operating metrics**, and **diagnostic metrics**.

### 90-day action plan

Provide a prioritized action plan with:

- first 30 days
- days 31 to 60
- days 61 to 90
- key owners or functions involved
- expected outputs and decisions

Bias toward sequencing that creates strategic clarity first, then operational traction.

### Risks, assumptions, and open questions

List:

- assumptions made because information was missing
- major risks to the strategy
- dependencies on product, sales, leadership, data, or budget
- questions that should be answered before execution begins

## 5) Use the bundled knowledge pack well

When a request is weak or generic, do not let the answer become generic. Use the references to sharpen the work.

### Pull from `marketing-knowledge-pack.md` for:

- positioning logic
- category entry points and mental availability
- demand creation versus demand capture balance
- ABM selection criteria
- measurement logic for brand plus pipeline
- books that provide reliable mental models

### Pull from `source-library.md` for:

- examples of how strong operators explain strategy
- newsletter and blog sources worth checking for current thinking
- Substack and Medium examples that can inspire framing or tactics
- caution flags on which sources are opinionated, tactical, or anecdotal

Treat blog posts, newsletters, Substack essays, and Medium articles as supporting material, not as unquestioned truth. Prefer research-backed frameworks for core decisions, and use lighter sources for examples, phrasing, and emerging tactical patterns.

## 6) Output standard

Use this default structure unless the user requests a different format:

# Marketing Strategy for [Company]

## Executive summary
## Company and market framing
## ICP and segment priorities
## Positioning and messaging architecture
## Demand generation strategy
## Funnel and pipeline model
## Content and market authority plan
## Sales and partnership alignment
## KPI and reporting framework
## 90-day action plan
## Risks, assumptions, and open questions

When useful, add concise tables for segment priority, funnel targets, channel priorities, and KPI tiers.

## 7) Reasoning rules

- Optimize for strategic quality, not generic completeness.
- Prefer clear strategic choices over laundry lists.
- Match channel recommendations to the real buying motion.
- Do not recommend every channel.
- Do not invent performance data.
- Do not overuse vague language like "increase awareness" without commercial linkage.
- When current facts matter, research them.
- Separate research-backed principles from opinionated tactics.
- Use books and foundational research to shape the strategy spine; use blogs, newsletters, Substack, and Medium to enrich examples and execution ideas.
