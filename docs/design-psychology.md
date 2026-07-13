# design-psychology

Quickstart:

```bash
npx skills add shuwarida/skills --skill=design-psychology
```

```bash
npx skills update design-psychology
```

[Source](https://github.com/shuwarida/skills/tree/master/skills/design-psychology)

## What it does

`design-psychology` is a pre-design interview grounded in behavioral psychology. Its premise: professional design starts not with "is it beautiful?" but with "what will the viewer actually understand?" — aesthetics are subjective, confusion is objective. And users don't decide logically: defaults read as recommendations, the first number sets the ruler, a gift creates a debt, building creates ownership.

The skill is an interview, not a lecture. It asks **one question at a time** and waits for your answer, each question paired with the agent's own recommended answer grounded in the principle being applied. Facts the agent can find itself — existing screens, copy, analytics, the codebase — it looks up instead of asking; the *decisions* stay yours. No designing starts until you confirm a shared understanding.

## When to reach for it

Type `/design-psychology`. The skill is invoke-only by design (`disable-model-invocation: true`) — a psychology interview firing automatically on any UI task would be noise, so you decide when a design deserves it.

Reach for it before pixels exist for a new design, or before shipping any screen or flow that asks the user to decide, act, or sign up. Principles that genuinely don't apply are skipped — no pricing on the screen means no anchoring question.

## The two parts

**Part I — Pre-brief** runs before any pixel exists: the perception gap (where does the eye land first, what gets missed?), the viewer's starting emotional state, predictive empathy, memory encoding, brand voice before visuals, and the experience around the work itself.

**Part II — Behavioral principles** runs per screen or flow: smart defaults, goal gradient (never start a user at zero), reciprocity (give value before asking), the IKEA effect (let users build before they sign up), loss aversion, and the contrast effect (never show a cost in isolation).

## Why an interview and not a checklist

A checklist recited at the user produces nods, not understanding. The interview walks the principles in dependency order — Part I answers reshape which Part II questions matter — and one question at a time keeps the structure that makes the session converge. A firehose of parallel questions is bewildering; a sequence of grounded ones builds the shared picture the design will be judged against.
