# Kumori

Kumori is an AI lab. New ideas, built with AI, all running on one engine we built ourselves. **[kumori.ai/lab](https://kumori.ai/lab)** has everything we build; **[kumori.ai/engine](https://kumori.ai/engine)** shows the engine, live.

The engine is ours. What it makes, we share. This is where the shared part lives: work that proves something, published so anyone can check it.

## What is public here

**[sparebrains](https://github.com/kumori-ai/sparebrains)** points free AI capacity at mathematics, in Lean 4. The Lean kernel is the only judge: a result exists when the checker accepts it, and every attempt, accepted or rejected, stays in the public record.

As of 2026-10-07: 264 of 378 targets have a kernel-verified proof, from 47,886 attempts, with $0 spent on models. Live numbers, every run and every transcript: **[sparebrains.kumori.ai](https://sparebrains.kumori.ai)**.

**[boomi-patterns](https://github.com/kumori-ai/boomi-patterns)** is a set of unofficial, checked patterns for Boomi Data Integration, Integration and Flow, built and driven by API, with what broke on the way.

## How to take part

You do not need to run anything. GitHub is the interface.

- **Pick up a piece of an open problem.** When a problem resists the models working alone, it gets one issue holding its best partial proof, what is left, and what has been tried. Take a piece, by hand or with your own agent. The kernel judges whatever comes back.
- **Report a misformalization.** If a Lean statement does not say what its source problem says, that is the most useful bug there is.
- **Propose a target.** Something with a real answer key.
- **Talk.** Questions and arguments go in [Discussions](https://github.com/kumori-ai/sparebrains/discussions).

## The rules we hold ourselves to

- A known proof of a problem never goes into a prompt for that problem.
- Every attempt discloses the model, the lane, the method and the cost.
- Nothing is sent upstream, to mathlib or a problem site, without a person reviewing it first.
- When a note or a number turns out wrong, a newer one says so. The old one is not edited.

## Where it is going

Today, verified math. Next, any problem a machine can check: [what's next](https://sparebrains.kumori.ai/next).

Want something built on the same engine? **[kumori.ai/consulting](https://kumori.ai/consulting)**.
