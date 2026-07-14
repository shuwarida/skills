# design-ux

Quickstart:

```bash
npx skills add shuwarida/skills --skill=design-ux
```

```bash
npx skills update design-ux
```

[Source](https://github.com/shuwarida/skills/tree/master/skills/design-ux)

## What it does

`design-ux` is a behavioral-psychology interview for screens and flows. Its premise: users don't decide logically — defaults read as recommendations, the first number sets the ruler, a gift creates a debt, building creates ownership, progress creates momentum.

The skill is an interview, not a lecture. It asks **one question at a time** and waits for your answer, each question paired with the agent's own recommended answer grounded in the principle being applied. Facts the agent can find itself — existing screens, copy, analytics, the codebase — it looks up instead of asking; the *decisions* stay yours. No designing starts until you confirm a shared understanding.

## When to reach for it

Type `/design-ux`. The skill is invoke-only by design (`disable-model-invocation: true`) — a psychology interview firing automatically on any UI task would be noise, so you decide when a design deserves it.

Reach for it before shipping any screen or flow that asks the user to decide, act, or sign up. Principles that genuinely don't apply are skipped — no pricing on the screen means no anchoring question.

## The principles

Smart defaults (pre-select the most common choice), goal gradient (never start a user at zero), reciprocity (give value before asking), the IKEA effect (let users build before they sign up), loss aversion (show what they'll lose, not what they'll gain), and the contrast effect (never show a cost in isolation).

## Why an interview and not a checklist

A checklist recited at the user produces nods, not understanding. The interview walks the principles per screen, and one question at a time keeps the structure that makes the session converge. A firehose of parallel questions is bewildering; a sequence of grounded ones builds the shared picture the design will be judged against.
