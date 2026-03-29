# Week 12 — 2026-03-22

## Personal Commentary

It's becoming clear that software engineers will increasingly be delegated to high-leverage activities — security engineering, site reliability, architecture — rather than baby-sitting agents. There is little business incentive for that. On the other hand, if we actually believe agents can effectively solve problems, and we also believe that (a) any problem can be solved by throwing a sufficiently large number of tokens at it and (b) we can solve more problems by using more tokens — then both reduce to spending more tokens, and figuring out how to do that effectively (and cost-effectively) is the basis for any agentic leverage.

It turns out that spending tokens is not easy as long as humans are stuck in the loop. There are patterns — such as inversion of control — that can eject engineers out of their "baby-sitter" roles. That, however, will require adopting new workflows and a new culture of work.

## AI & Software Engineering

- **[The Effects of AI Assistance on Coding Skill Development](https://www.anthropic.com/research/AI-assistance-coding-skills)** — A small Anthropic study (n=52, mostly junior engineers) found that participants using AI assistance scored 17% lower on post-task comprehension than those who coded by hand. Notably, those who used the AI to ask clarifying questions retained more than those who delegated outright — suggesting the mode of interaction matters as much as the tool itself.

- **[A Sufficiently Detailed Spec Is Code](https://haskellforall.com/2026/03/a-sufficiently-detailed-spec-is-code)** — A critique of "spec driven development" applied to agents. What could the future of specs look like? Perhaps they will end up being a set of formally verifiable "core" algorithms and data structures that agents build boilerplate ("glue code") around.

- **[How Fabro Works](https://docs.fabro.sh/core-concepts/how-fabro-works)** — An example of an open-source "dark software factory" implementation. Fabro is a workflow engine that parses Graphviz-defined DAGs, dispatches nodes to handlers (LLMs, shell commands, human input), and manages execution through edge selection rules, parallelism, and checkpoints.

## Security

- **[Black-hat LLMs — Nicholas Carlini at [un]prompted 2026](https://www.youtube.com/watch?v=1sd26pWhfmg)** — Carlini demonstrates that with minimal scaffolding (a bash script and a Docker container), Claude generated 500 zero-days across open-source projects — including 22 confirmed Firefox CVEs and an unauthenticated SQLi in Ghost CMS. The barrier to offensive security research has dropped dramatically, and LLMs can reason about code in ways traditional fuzzers cannot.
