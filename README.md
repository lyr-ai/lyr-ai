## Ruxi Zhang

I build measurement tools for **agent reliability** — the part of the stack that
asks not "did the agent succeed?" but "where is this agent fragile, and does that
fragility reach the outcome?"

The work started from an observation that keeps reappearing: the same agent, the
same model, `temperature=0`, and the executions still differ. Most of those
differences are harmless. A few decide the result. Telling those apart is the
research problem.

### Writing

**[12 of 13 runs reached the exact same code state, then ended 11 different ways](https://lyr-ai.github.io/agents-diverge-at-temperature-zero/)**
Twelve of thirteen executions of the same coding agent converged on one
identical intermediate repository state, then ended in eleven distinct final
states. Why behavioral variation is not the same thing as unreliability, and
what would have to be true to steer an agent before it fails.

More at **[lyr-ai.github.io](https://lyr-ai.github.io)** · [RSS](https://lyr-ai.github.io/feed.xml)

### Projects

| | |
|---|---|
| **[AgentSeism](https://github.com/lyr-ai/agentseism)** | Localizing where LLM-agent executions are behaviorally fragile. Repeated runs, execution-feature projection, and which feature variations actually track the outcome. Association, not causation — intervention is the next phase. |
| **[TypedMem](https://github.com/lyr-ai/typedmem)** | Schema-aware typed memory for AI agents. |
| **[LYR](https://github.com/lyr-ai/lyr)** | A layered knowledge engine. |

### What I am working on now

Attaching external correctness labels to repeated agent executions, so that
*harmless* variation and *consequential* variation can finally be separated by
something other than judgement.
