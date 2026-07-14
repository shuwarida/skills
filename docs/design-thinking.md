# design-thinking

Quickstart:

```bash
npx skills add shuwarida/skills --skill=design-thinking
```

```bash
npx skills update design-thinking
```

[Source](https://github.com/shuwarida/skills/tree/master/skills/design-thinking)

## What it does

`design-thinking` is a pre-brief interview grounded in psychology, run before any pixel exists. Its premise: professional design starts not with "is it beautiful?" but with "what will the viewer actually understand?" — aesthetics are subjective, confusion is objective. If a design has to be explained, it has failed.

The skill is an interview, not a lecture. It asks **one question at a time** and waits for your answer, each question paired with the agent's own recommended answer grounded in the principle being applied. Facts the agent can find itself — existing screens, copy, analytics, the codebase — it looks up instead of asking; the *decisions* stay yours. No designing starts until you confirm a shared understanding.

## When to reach for it

Type `/design-thinking`. The skill is invoke-only by design (`disable-model-invocation: true`) — a psychology interview firing automatically on any UI task would be noise, so you decide when a design deserves it.

Reach for it before pixels exist: a new design, a redesign, an identity or logo.

## The principles

The perception gap (where does the eye land first, what gets missed?), the viewer's starting emotional state, predictive empathy (design for the emotion the viewer leaves with), memory encoding (give the brain something to resolve), brand voice before visuals, and the experience around the work itself.

## Why an interview and not a checklist

A checklist recited at the user produces nods, not understanding. The interview walks the principles in dependency order, and one question at a time keeps the structure that makes the session converge. A firehose of parallel questions is bewildering; a sequence of grounded ones builds the shared picture the design will be judged against.
