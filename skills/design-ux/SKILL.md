---
name: design-ux
description: Behavioral psychology interview for screens and flows that ask the user to decide, act, or sign up — smart defaults, goal gradient, reciprocity, endowment (IKEA effect), loss aversion, and the contrast effect.
disable-model-invocation: true
---

Users aren't making logical decisions: defaults read as recommendations, the first number sets the ruler, a gift creates a debt, building creates ownership, progress creates momentum.

## How to run: grill, don't lecture

This skill is an interview, not a checklist to recite. Grill the user relentlessly through the principles below until you reach a shared understanding of the design:

- Walk the principles for each screen or flow that asks the user to decide, act, or sign up, resolving dependencies between answers one-by-one — an earlier answer reshapes the later questions. Skip principles that genuinely don't apply (no pricing → no contrast question).
- Ask one question at a time and wait for the answer. Multiple questions at once are bewildering.
- For every question, give your recommended answer, grounded in the principle you're applying.
- A *fact* you can find yourself (existing screens, copy, analytics, the codebase) — look it up rather than asking. The *decisions* are the user's — put each one to them and wait.
- Do not start designing until the user confirms shared understanding.

## 1. Smart defaults

Pre-select the most common choice for every field. Defaults read as recommendations — "this is what most people pick" — and 70–90% of users never change them. The user's job shifts from "fill this out from scratch" to "scan and adjust what doesn't fit", a fundamentally easier task. Fewer open decisions means more completions (jam study: 24 flavors → 3% bought; 6 flavors → 30%). Let the button carry the outcome too: "Show 12 results", not "Search".

## 2. Goal gradient

Never start a user at zero. Count something they've already done as step one — account creation, the first pre-checked item — so progress opens at 20%, not 0%. The closer people feel to the finish, the faster they move toward it (loyalty card with 2 of 10 stamps pre-filled: nearly double the completion of an empty 8-stamp card). Zero feels like standing still; a head start feels like momentum, and that feeling is what separates finishers from second-screen drop-offs.

## 3. Reciprocity

Give value before asking for anything. Deliver a genuinely useful partial result first — their score, top issues, what passed — then ask: "Want the complete breakdown? Save your report." Blurring results behind "create an account to see" is holding them hostage: a restaurant demanding your card before showing the menu. A received gift creates an unconscious debt (the strongest driver of persuasion per Cialdini; free samples lift purchases up to 2,000%), so the sign-up never feels like a wall — the user already got something worth coming back for.

## 4. Endowment (IKEA effect)

Let users build before they sign up. Choosing a name, a palette, a card style — each choice makes the thing *theirs*, and people value what they built far above an identical thing made by someone else; even just feeling ownership is enough. By the time the sign-up screen appears, leaving no longer means skipping a form — it means abandoning something they made (Duolingo: language picked, goal set, first lesson done before any account). The button says "Continue", not "Sign up".

## 5. Loss aversion

When a screen asks users to act, flip the framing: don't sell what they'll gain, show what they'll lose if they don't. Losing weighs roughly twice as much as gaining the same thing (Kahneman), and status quo bias makes people protect what they already have. Show the concrete stakes by name — *their* files, with a countdown — and make the dismiss option own the risk ("I'll risk it"), never a free escape hatch ("Maybe later"). A pitch has zero psychological weight; the felt cost of inaction wins.

## 6. Contrast effect

Never show a cost in isolation. The brain evaluates every number relative to the one it just saw, so control what the user sees first — that first number becomes the ruler. A $50/mo plan on its own page reads as "$600 a year"; the same $50 under a $1,900 laptop with a "just 2.6%" label reads as a rounding error. Same offer, different anchor (the $90 steak exists to make the $40 salmon reasonable).

Source: https://www.youtube.com/watch?v=2TlIg3VokY8
