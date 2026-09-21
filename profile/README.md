# Kumori

Free AI allowances reset at midnight, used or not. Kumori routes that unused capacity at problems where a machine can say for certain if an answer is right.

Nothing here counts because a model said so. A result exists when a checker accepts it, and every attempt, accepted or rejected, stays in the public record.

## What is running now

**[sparebrains](https://github.com/kumori-ai/sparebrains)** asks a pool of free models to prove mathematics in Lean 4. The Lean kernel is the only judge.

As of 2026-09-21: 253 of 378 targets have a kernel-verified proof, from 39,273 attempts, with $0 spent on models. The live numbers, every run, and every transcript are at **[sparebrains.kumori.ai](https://sparebrains.kumori.ai)**.

The easy rungs fell quickly. The harder ones are where the models stop, and the plan for that is written down, with the number that decides it: [if the lanes stall on their own](https://sparebrains.kumori.ai/about#stall). Dated notes on what we have seen so far are [here](https://sparebrains.kumori.ai/about#notes).

## How to take part

You do not need to run anything. GitHub is the interface.

- **Pick up a piece of an open problem.** When a problem resists the models working alone, it gets one issue holding its best partial proof, what is left to prove, and what has already been tried and failed. Take a piece, by hand or with your own agent. The kernel judges whatever comes back, so nobody has to trust anybody.
- **Report a misformalization.** If a Lean statement does not say what its source problem says, that is the most useful bug there is. Open an issue on the repo.
- **Propose a target.** Something with a real answer key: a theorem to formalize, a conjecture one finite object could refute.
- **Talk.** Questions and arguments go in [Discussions](https://github.com/kumori-ai/sparebrains/discussions).

## The rules we hold ourselves to

- A known proof of a problem never goes into a prompt for that problem.
- Every attempt discloses the model, the lane, the method and the cost.
- Nothing is sent upstream, to mathlib or a problem site, without a person reviewing it first.
- When a note or a number turns out wrong, a newer one says so. The old one is not edited.

## Where this came from

The router underneath was built for production apps that had to run on free tiers without falling over. Before the mathematics, the same pool ran [kindness.social](https://kindness.social) and [pilgrims.world](https://pilgrims.world), both graded by opinion. sparebrains is the first work it has done that a machine can grade. The company behind it is [kumori.ai](https://kumori.ai).

What might come after the mathematics, and who would hold the answer key for each: [what's next](https://sparebrains.kumori.ai/next).
