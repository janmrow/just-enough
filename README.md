# Just Enough

**Just Enough helps AI cut through unnecessary complexity and keep only what actually earns its place.**

Sometimes a plan, process, project, or solution starts accumulating structure faster than value. Just Enough gives the model a deliberate moment to step back and ask:

> How much of this complexity is actually justified?

It does not aim for the simplest possible answer. It looks for **enough complexity — and no more than the situation earns**.

## Why

Telling a model to *“simplify this”* is easy, but ambiguous.

Simpler could mean fewer steps, less code, fewer tools, less documentation, lower cost, a shorter process, or merely a shorter answer.

Just Enough gives that request a stable meaning.

It treats complexity as something that can create real value — but also carries costs such as time, attention, coordination, cognitive load, maintenance, risk, and opportunity cost.

The goal is not minimalism.

The goal is **proportionate complexity**.

## When to use it

Use Just Enough when something feels:

* overbuilt;
* harder to understand than it should be;
* surrounded by process or machinery;
* burdened by historical decisions;
* increasingly difficult to change;
* optimized beyond what the actual problem seems to require.

It is equally valid for Just Enough to conclude that the existing complexity is justified and should remain.

## Usage

Invoke the `just-enough` skill when you want a simplicity-oriented reality check.

For example:

```text
Use just-enough to review this release process.
```

```text
Use just-enough on the architecture we have designed so far.
```

```text
Apply just-enough to this marketing plan.
```

```text
Use just-enough here. I think we may be overcomplicating this.
```

Just Enough does not impose a special response format. The model should continue responding naturally while looking at the problem through the skill's reasoning lens.

## Install

The skill itself lives in [`SKILL.md`](SKILL.md).

Add this skill directory to the location your AI agent or coding environment uses for skills, following that host's installation convention.

## What it changes

Just Enough does not make the model smarter or give it additional domain knowledge.

It changes **what the model pays attention to**.

In particular, it encourages the model to examine:

* what the real outcome is;
* what each layer of complexity actually buys;
* what that complexity costs;
* what could be removed, combined, deferred, or replaced;
* whether some complexity exists mainly to manage earlier complexity;
* whether a simpler alternative would preserve the important value;
* whether further simplification would go too far.

Sometimes the result is a much simpler solution.

Sometimes it is a small adjustment.

Sometimes the right answer is to change nothing.

## Status

Early development — v0.1.

The current version is intentionally small and is being tested across different kinds of work and problems.

## License

[MIT](LICENSE)
