# Just Enough

<p>
  <img src="assets/hero.png" alt="Just Enough — Find enough in a world of more." width="1280">
</p>

**An AI skill for deciding which complexity earns its place.**
Use it with code, plans, processes, and everyday decisions.

A plan gains another step. A project gains another tool. Soon, keeping the machinery running becomes a job of its own.

Just Enough gives your agent a moment to return to the goal, weigh what the extra structure buys, and find the right amount of complexity. Sometimes that means removing something. Sometimes it means keeping what is already there.

## See it work

*Illustrative example.*

You're planning a one-off, free workshop for twelve people. The plan has grown to include a booking website, attendee accounts, and automated reminders.

You ask:

```text
Use just-enough on this plan.
We need a headcount,
venue details, and a way
to contact attendees.
```

A proportionate decision might be:

| Keep | Set aside for now |
| --- | --- |
| A sign-up form, an attendee list, and one reminder | A custom booking website and attendee accounts |
| The capacity limit, venue access information, and a named contact | An automated reminder service for this one event |

The useful work stays. The extra machinery has to justify itself.

The same question applies to a release process, a software architecture, a design brief, or a personal project.

## Install

With Node.js 22.20 or later and npm available, run:

```sh
npx skills add janmrow/just-enough
```

Choose your agent and installation scope when prompted.

For a manual installation, copy `SKILL.md` to `<skills-directory>/just-enough/SKILL.md`. For Codex projects, use `.agents/skills/just-enough/SKILL.md`. Only that file is needed; the skill has no scripts or runtime dependencies.

## Use it

Once installed, ask for it by name:

```text
Use just-enough here.
Reassess our plan so far.
What complexity earns its place?
```

In Codex, you can also invoke it with `$just-enough`.

It is especially useful in the middle of a conversation, when there is already a plan or solution to examine. Your agent keeps its normal voice and fits the answer to the task.

## Stop at enough

Complexity can earn its place through correctness, safety, reliability, real constraints, and important human needs. Keep what protects the outcome.

When the current approach already fits, leaving it alone is a good result.

Read the complete reasoning lens in [`SKILL.md`](SKILL.md).

## License

[MIT](LICENSE).
