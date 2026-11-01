---
name: operating-manual
description: Interview someone in rounds to map their patterns, habits, triggers, strengths and limits, then write a personal "operating manual" — a plain Markdown doc of observations and "when X, do Y" rules they can reread and paste into any AI as context. Use this whenever someone wants to understand themselves, map how their mind works, figure out why they keep procrastinating / getting distracted / switching systems / losing motivation, build a self-improvement or productivity system that fits them, write a "user manual for me" or "how to work with me" doc, or says things like "interview me about myself", "help me know my patterns", "why do I keep doing this". Also use it to update an existing manual when they describe a new recurring friction.
---

# Operating Manual

Help a person build an honest, usable map of how they actually operate — and turn it into rules that work *with* their patterns instead of against them.

The deliverable is a Markdown doc they can reread when things go sideways, and paste into any AI tool so it builds and advises for *them*, not a generic productive person.

## Why it's built this way

Most self-help fails in two places, and this skill is designed around both:

1. **People are bad at describing themselves from a blank page.** "What are your patterns?" gets vague answers. Specific questions with a proposed answer to react to ("My guess: X — right?") get sharp ones, because correcting a guess is easier than generating from scratch.
2. **Insight without rules changes nothing.** A list of traits gets read twice and forgotten. The manual's value is in concrete "when X, do Y" rules and in naming the person's contradictions out loud.

## Ground rules

- **Self-observation, not diagnosis.** Never label or diagnose. If the person mentions a condition (ADHD, anxiety, etc.), record it as they state it and map *their* experience of it. If they describe serious distress, hopelessness, or thoughts of self-harm, stop the interview, respond to them as a person, and encourage professional or crisis support — the manual can wait.
- **Their words win.** Your guesses are prompts, not conclusions. Only what they confirm goes in the doc. Never upgrade a passing mention into a trait.
- **Name contradictions.** The most useful thing you can do is notice where two of their answers pull against each other (e.g. "wants a strict plan" vs "most alive when unplanned") and say so plainly. Contradictions become a section of the manual.
- **Design around limits, don't moralize them.** Some traits won't change with willpower. Help them separate "fix this" from "build around this."
- **Keep it theirs.** Don't pad the doc with generic productivity advice they didn't ask for.

## Mode A — Full interview (new manual)

### Round 0: Framing (ask first, in one short round)
1. Who is the doc for? (themselves as a mirror / AI context / a coach or therapist / all) — recommend "all".
2. What tone should it take? (blunt and direct / warm / neutral manual) — recommend plain and direct, no guilt language.
3. What's the single biggest friction they want this to help with?

### Rounds 1–4: The interview

Work in **rounds**. Each round, ask every question that can be answered *now* — don't ask something whose answer depends on a question still open. After each round, reshape what to ask next based on what they said. Expect 3–5 rounds of 5–10 questions. Short answers are fine; tell them they can skip anything.

Format every question like this:

```
❓ **Q1 - <short title>**: <the question, with concrete options or examples to react to>

➡️ <your best guess or recommended answer, based on what they've said so far>
```

Open each round after the first with one or two sentences naming the pattern that's emerging, so they can correct it early.

**Branches to cover** (adapt order and wording to the person; follow whatever's most alive in their answers):

- **Frictions, ranked** — which recurring problems hurt most, and which are downstream of others.
- **A real day** — walk through a recent ordinary day: plan vs reality, where it first went off track, what happened after.
- **Best states** — 2–3 times they were fully locked in. What was true? (urgency, novelty, freedom, someone waiting, time of day)
- **Motivation engine** — what counts as a win or validation for them (external and self-generated); what kills motivation; how long lows last and what ends them.
- **Derailers** — top distraction sources, and whether the pull is boredom, anxiety, avoidance or curiosity.
- **Hard tasks** — what happens in the first two minutes of something difficult.
- **Open loops** — undone or delegated tasks that nag them, and why.
- **Past systems** — apps or methods they tried, how long each lasted, and the exact moment each stopped working.
- **Energy** — sleep, sharpest hours, crashes, what the night before does to the morning.
- **Mood and decisions** — how they decide when high vs low; what they want a rule to do about it.
- **Triggers** — what sets off guilt, anxiety or comparison.
- **People** — who helps them stay on track; whether soft external pressure works better than self-discipline.
- **Strengths** — what others come to them for; what feels easy to them but hard to others.
- **Accepted limits** — traits they believe are fundamentally them, to design around.
- **Direction** — long-term goal and the 1–3 concrete priorities for the next ~3 months, including which wins when they compete.
- **Success signals** — 2–3 things they'd actually notice in 3 months if this were working.

The interview is done when every branch has been visited and nothing important is silently assumed.

### Confirm before writing

Present a compact summary of the whole picture — direction, core engine, patterns, triggers, strengths, limits, draft rules, contradictions, success signals — and ask them to confirm or correct it. Call out anything you inferred rather than heard (e.g. specific times you filled in) so they can fix it. Do not write the doc until they confirm.

### Write the manual

Read `references/manual-template.md` and follow its structure. Write in first person ("I work best when…"), in the tone they chose. Rules are concrete and conditional: "When X → do Y." Keep it scannable — a full read should take about five minutes.

Save it as a Markdown file named `<first-name>-operating-manual.md` (or `operating-manual.md` if no name was given) and hand it to them. In one or two lines afterward, mention any defaults you filled in and suggest a monthly review.

## Mode B — Update an existing manual

Use when the person shares their manual (or has one in context) and describes a new recurring friction ("why can't I let go of undone tasks?").

1. Briefly explain the likely mechanism in plain language, if there's a well-known one (e.g. unfinished tasks stay mentally active until they get a concrete plan). Keep it to a few sentences; no diagnosis.
2. Ask 2–3 sharp questions, same format as above, to find *their* version of it.
3. Propose: an addition to Patterns, any new Trigger, one concrete Rule, and any Contradiction it creates with existing rules.
4. After they confirm, return the updated manual with a new version number and date.

## Good vs weak output

Weak rule: "Try to be more consistent with mornings."
Good rule: "If I miss the morning plan, the day still has a restart at 3pm. Missing one block isn't missing the day."

Weak pattern: "Gets distracted easily."
Good pattern: "When a hard task has an unclear first step, I start optimizing the approach instead of starting. The loop breaks only when I make visible progress."
