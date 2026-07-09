# Rubric & SOP Design

Hey, I'm Srineha. This repo is basically a look into how I design rubrics and SOPs for evaluating AI model outputs — mostly frontend engineering tasks, but the same principles carry over into reasoning, business, and multi-domain evaluation work too.

## Why rubric design matters

When you're reviewing hundreds of AI-generated outputs a week, "looks about right" isn't good enough. You need criteria that are specific enough that two different reviewers land on the same verdict. That's the whole game — reducing ambiguity so evaluation stays consistent no matter who's doing it.

## What I actually do

- **Build binary (pass/fail) rubrics** that map directly to verifiable things — a screenshot, a piece of code, a specific behavior
- **Write SOPs** so a whole team of reviewers can apply the same judgment, not just me
- **Cover a range of domains** — I've written rubrics for frontend code (JavaScript, TypeScript, React), and also for STEM, humanities, and business reasoning tasks

## How I approach it

1. Start by figuring out exactly what "correct" means — not vaguely, but in a way you could point to and say "yes, this passed" or "no, it didn't"
2. Think through edge cases early. A rubric that only catches the obvious failures isn't doing its job
3. Write it so someone else, not just me, would interpret it the same way
4. Go back and tighten criteria after seeing where reviewers disagree — that's usually where the rubric was too loose

## A simplified example

(Not from any real client work — just showing the structure I use.)

| Criterion | Pass | Fail |
|---|---|---|
| State Management | UI updates correctly when state changes | State doesn't update, or updates incorrectly |
| Interactivity | Every interactive element behaves as expected | Something's unresponsive or inconsistent |
| Robustness | Handles weird/edge-case inputs gracefully | Breaks or does something undefined |

## Some numbers

- Written 50+ rubrics for frontend AI training work
- Kept reviewer alignment above 95% by making sure the rubrics themselves were the bottleneck-free part of the process
- Applied this across STEM, humanities, business, and software engineering domains

## Skills

Rubric Design · SOP Writing · Deterministic Evaluation Criteria · Reviewer Calibration · Multi-Domain QA
\## See it in action
For concrete rubric examples following this approach → [Rubric-Examples](https://github.com/srinehapalla1618-png/Evaluation-Rubric-Samples)
