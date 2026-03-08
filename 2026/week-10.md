# Week 10 — 2026-03-08

## Personal Commentary

With industrial, agent-based production of code replacing the artisanal craft of human beings, we are forced to address issues of scale our industry has never considered. When the software development lifecycle was conducted by humans only, the rate of change was adjusted to our ability to judge, form consensus, and cultivate engineering culture. The increased rate of change means these tools are now diminished in range and effectiveness. And when they are phased out from certain projects or organizations, their cultural significance will also diminish.

The consequences will be cultural and the profession of software engineering will expand to cover new ground. AI-produced software is forcing outcomes in areas such as programming language and compiler design, formal verification methods, software architecture and intermediate forms of software design, new methods of testing and benchmarking, and new approaches to failure tolerance, chaos engineering, and distributed testing.

These are all to account for the fact that with a higher expected rate of change we expect higher code churn and more errors in production. Errors of oversight, judgement, and poor business decisions are upstream errors that will also compound — at an even higher rate — into software failures.

## AI Agents & Software Engineering

- **[Your LLM Doesn't Write Correct Code. It Writes Plausible Code](https://archive.is/qCYkg)** — A case study on how syntactically correct agent-produced software still fails due to compounding errors: lack of clearly communicated intent, inability to measure all dimensions of correctness (performance, security), and agents using lazy reasoning — jumping to conclusions without properly investigating the problem.

- **[When AI Writes the World's Software](https://leodemoura.github.io/blog/2026/02/28/when-ai-writes-the-worlds-software.html)** — Leo de Moura on formal verification methods for AI-generated software. A direct look at what it takes to establish correctness guarantees when humans are no longer the primary authors.

- **[Execution Doesn't Fix Distribution](https://x.com/aakashgupta/status/2026777633623781808)** — Increased ability to execute via agents doesn't translate into top-line growth — it gets stuck in the same distribution bottleneck it always has.

- **[How I Dropped Our Production Database](https://alexeyondata.substack.com/p/how-i-dropped-our-production-database)** — Don't mix agent access to destructive commands with access to a production environment. A short, cautionary tale.

## Security

- **[10 Fundamental (but Really Hard) Security Metrics](https://www.philvenables.com/post/10-fundamental-but-really-hard-security-metrics)** — A framework for creating business-aligned security metrics. The techniques apply well beyond Fortune 500 scale — especially if we accept the premise of agentic engineering with its increasingly slim margin of error.
