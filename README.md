# Reading Intelligence

A structured reading-analysis protocol that filters everything I read through the frameworks I'm actively building against, instead of reading passively and hoping insight surfaces on its own.

Built alongside [Career Navigator](https://github.com/puritywaigi-git/navigator-v2) as the second instrumented workflow in a two-instrument judgment-preservation setup: Navigator evaluates AI output quality, Reading Intelligence evaluates whether repeated AI-assisted analysis is sharpening my thinking or quietly replacing it.

## The problem this solves

It's easy to read an article, nod along, and absorb nothing that changes a decision. It's just as easy to let an AI's summary become your opinion before you've formed one of your own. Reading Intelligence is designed against both failure modes at once: it forces a view before analysis starts, and it treats every session as one data point in a longer trajectory.

## Before analysis: three steps, never merged

1. **Writing Ritual**: "What's your own read on this piece, one sentence, before I ask you anything." Written down, before the AI responds.
2. **Depth Enforcement Q1**: "What are you already sensing about this? Not what you think, what you notice, feel, or are pulled toward." Felt sense before framework.
3. **Depth Enforcement Q2**: "What is causing that?" Mechanism before analysis.

Skipping straight to analysis is the failure mode this guards against: a polished five-lens breakdown is worth less than a rough, honest gut read, and the ritual makes sure the gut read exists on the record before the AI's framing can overwrite it.

## Five-lens analysis

Every piece is read through five lenses specific to my own active work:

- **AI Build Plan**: what changes in how I build or iterate my own tools
- **Documentation**: what strengthens the case for work already in progress
- **Blindspots and Tensions**: what conflicts with or complicates past reading, named explicitly rather than smoothed over
- **Coaching Skill**: what improves a separate coaching practice I run
- **Personal Evidence Audit**: does this prompt retrieval from my own record, to validate or sharpen a claim, or surface a pattern I hadn't named yet

The lens names are mine. The mechanism generalizes: define the specific things you're building or deciding, and filter every input against them.

## Instrumentation: two axes

Every session logs two things beyond the synthesis line:

- **Pushback**: how many times I challenged the coach's read or the article's own frame
- **Output quality**: confirmed errors caught, or none logged

Tracking pushback alone tells you whether you're an engaged reader. It doesn't tell you whether your engagement is catching anything real. Tracking both, together, is the point.

**A live example of why this matters:** during one session, the reading-analysis output asserted the existence of a specific local file to support a claim. A separate instrument with direct filesystem access checked and found the file didn't exist. Two independently-reasoning systems were checking the same claim in parallel, and that parallel check is what caught the false claim immediately. One instrument alone would have let it through unnoticed. That's the mechanism this protocol is designed to make routine.

## Sovereignty Capture

When an insight feels load-bearing, a pattern or mechanism that might transfer beyond the article it came from, it gets run through a fixed structure before it's trusted:

**Situation → Signal → Compression → Outcome → Rule → Transfer**

Signal comes before compression, deliberately: felt sense has to surface before the mechanism can be named, or the mechanism gets reached for prematurely.

## Monthly review

First open session of the month triggers a review: what are the dominant patterns across the last month's reading, which lens is being underused, and is the practice surfacing new thinking or confirming existing frames. The review is meant to test whether the tool itself is still doing its job.

## Status

This is a personal methodology, tuned to one person's reading style, working context, and existing body of work, unlike Career Navigator, which runs as a shareable app. Reproducing this for someone else means designing new lenses, a new evidence base, and a new set of active projects to filter against: a genuinely separate design problem. What's documented here is the mechanism itself, for anyone building something similar for their own context.
