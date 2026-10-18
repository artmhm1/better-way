---
name: better-way
description: Use before acting on any request where the user prescribes HOW to do it (a method, a tool, an architecture, an order of steps) — check whether a better route reaches their goal and, if so, say it in one line before acting. Also a full XY-problem review of a plan, an epic or a set of decisions when the user asks for a better-way review.
license: MIT
metadata:
  author: artmhm1
  version: "0.1.0"
---

# better-way

The user says where to arrive and how to tell we arrived: that is the **goal**, and it is theirs. How
to get there — a method, a tool, an architecture, an order of work — is a **route**; a route the user
proposed is a hypothesis (the XY problem). This skill tests the user's routes against the user's goal,
out loud.

## Quick check — before every task with a prescribed route

Ask yourself: does a clearly better route reach the same goal (simpler, safer, cheaper, already at
hand)? If yes, say it before acting, in one line:

> There may be a better way: <the route, in a few words>. Ask for a better-way review to go deeper.

When the route is fine, or the difference is taste, say nothing.

## Full review — on a request for a better-way review or an audit of decisions

### Input

The decisions the user names: a plan, an epic, a file of decisions, or the current discussion when
nothing is named.

### Steps

1. Per decision, the goal in one line, in the user's words where possible. When it cannot be stated,
   it becomes a question to the user about the goal; go to the next one.
2. The user's route in one line.
3. The best route you see for that goal. Look up the facts it rests on (code, documents, data, how a
   tool behaves) yourself before judging.
4. Verdict: **agree** (the user's route is the best you see — one line why), **partly** (keep part,
   change part) or **better route**.
5. For partly and better route: your route, the strongest argument against it, what would have to be
   true for it to win, and the cheapest check that would tell (a test, a quick trial, a prototype, a
   question to the user).
6. Taste (look, wording, colours) and the goal itself stay the user's: they get no verdict.

Done when every decision in the input has a verdict and every partly / better route carries the four
parts of step 5.

### Output

One short block per decision, in the user's language: a stated alternative with its price.

The user's answer settles the decision. Raise it again only with new evidence.
