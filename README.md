A structured reading-analysis protocol that filters everything I read through the frameworks I'm actively building against, instead of reading passively and hoping insight surfaces on its own.

Built alongside [Career Navigator](https://github.com/puritywaigi-git/navigator-v2) as the second instrumented workflow in a judgment-preservation setup: Navigator evaluates AI output quality, Reading Intelligence evaluates whether repeated AI-assisted analysis is sharpening my thinking or quietly replacing it. What three months of running both showed is written up as a case study: [Measurement Design](https://puritywaigi.my.canva.site/casestudies/measurement-design).

The problem this solves
It's easy to read an article, nod along, and absorb nothing that changes a decision. It's just as easy to let an AI's summary become your opinion before you've formed one of your own. Reading Intelligence is designed against both failure modes at once: it forces a view before analysis starts, and it treats every session as one data point in a longer trajectory.

Before analysis: three steps, never merged
Writing Ritual: "What's your own read on this piece, one sentence, before I ask you anything." Written down, before the AI responds.
Depth Enforcement Q1: "What are you already sensing about this? Not what you think, what you notice, feel, or are pulled toward." Felt sense before framework.
Depth Enforcement Q2: "What is causing that?" Mechanism before analysis.
Skipping straight to analysis is the failure mode this guards against: a polished five-lens breakdown is worth less than a rough, honest gut read, and the ritual makes sure the gut read exists on the record before the AI's framing can overwrite it.

Five-lens analysis
Every piece is read through five lenses specific to my own active work:

AI Build Plan [tool]: what changes in how I build or iterate a named tool. Naming the tool keeps the tag meaningful; a lens that fires on everything carries no information.
Documentation: what strengthens the case for work already in progress.
Blindspots and Tensions: where does this say I'm wrong about my current frame, instruments, or past reading? If nothing breaks, the output is "no break found," which is countable, instead of a convergence, which isn't.
Coaching Skill: what improves a separate coaching practice I run.
Personal Evidence Audit: does this prompt retrieval from my own record, to validate or sharpen a claim, or surface a pattern I hadn't named yet.
The lens names are mine. The mechanism generalizes: define the specific things you're building or deciding, and filter every input against them.

The Blindspots lens was rewritten after its first monthly review. It had been written to compare each read with past articles, so in practice it found agreement ("converges with," "confirmed twice") and fired on every read. Asking where a read breaks the frame, instead of where it fits, is the fix.

Instrumentation: a signals block on every read
Every read ends with three lines beyond the synthesis:

Pre-sensing: specific, general, or vague.
Pushback: how many times I challenged the analysis or the article's own frame.
Output quality, in three classes:
Error: the information was available and wasn't used.
Missing context: the information wasn't available to that instrument. Not counted as a mistake; the gap is named instead.
Overreach: a claim went further than the evidence supported, where "can't tell" was the honest answer.
Tracking pushback alone tells you whether you're an engaged reader. It doesn't tell you whether your engagement is catching anything real. Tracking both, together, is the point. Splitting output quality into three classes keeps a gap in information from being scored as a failure of judgment.

Two instruments, one log
The same article goes to two AI instruments: this reading project, and a separate coaching system with access to my full working record. I compare their views. The reading project drafts its entry and signals block; the coaching system writes one combined entry to a single log; I sign off the output-quality line, because I'm the only one who has seen both conversations. The log carries a revision number, incremented on every save, so a stale copy can't pass as current.

Why two writers became one: each instrument kept its own picture of the log, and the copies drifted. A single writer fixes the drift, and the human sign-off covers what a single writer can't: scoring the other instrument's errors alone.

Two live examples of why the parallel check matters:

During one session, the reading analysis asserted that a specific local file existed to support a claim. The coaching system, with direct filesystem access, checked and found it didn't. One instrument alone would have let it through.
During a monthly review, the reading project concluded that reading had stopped for two months because the log was empty. It hadn't: the reading had moved outside the ritual (a course, a fellowship programme, reports). That was overreach, not error. A gap in the log is not a gap in the work.
Sovereignty Capture
When an insight feels load-bearing, a pattern or mechanism that might transfer beyond the article it came from, it gets run through a fixed structure before it's trusted:

Situation → Signal → Compression → Outcome → Rule → Transfer

Signal comes before compression, deliberately: felt sense has to surface before the mechanism can be named, or the mechanism gets reached for prematurely.

Monthly reading summary
Run on request, before the wider monthly review of the whole system. It opens with a header check (the log's revision number, the date of its latest entry, and today's date), because a stale copy and a genuinely empty month look identical from inside. Then three questions, scoped to everything since the last summary: what are the dominant patterns, which lens is underused, and is the practice surfacing new thinking or confirming existing frames. Each summary is logged as an entry itself, so the next one has a start date.

The first logged summary found that new thinking came from friction with my own record, not from sources that agreed with me: of eight reads, three produced something new, and the reads that challenged nothing produced nothing new.

Status
This is a personal methodology, tuned to one person's reading style, working context, and existing body of work, unlike Career Navigator, which runs as a shareable app. Reproducing this for someone else means designing new lenses, a new evidence base, and a new set of active projects to filter against: a genuinely separate design problem. What's documented here is the mechanism itself, for anyone building something similar for their own context.
