# Hi, I'm Storm 👋

**Backend & platform engineer, building reliable agent infrastructure and developer tools.**

I work on the execution layer around AI agents: runtimes, tools, permissions, and recovery. My background is in distributed services and data infrastructure. These days, I contribute to [DeerFlow](https://github.com/bytedance/deer-flow) and [dbx](https://github.com/t8y2/dbx), and turn real codebases into learning material.

[Projects](#projects) · [Open-source contributions](#open-source-contributions) · [Agent 工程拆解](https://stormtian.github.io/agent-engineering-book/)

## Projects

| Project | What I'm building | Explore |
| --- | --- | --- |
| [Agent 工程拆解](https://github.com/StormTian/agent-engineering-book) | A Chinese sourcebook on execution loops, context, tools, memory, recovery, and permissions across 12 agent projects. | [Read online](https://stormtian.github.io/agent-engineering-book/) |
| [Codebase to Mastery](https://github.com/StormTian/codebase-to-mastery) | A portable Agent Skill for learning from real repositories through source tracing, active recall, and implementation exercises. | [Get the skill](https://github.com/StormTian/codebase-to-mastery#install) |
| [狩魔手记 · Witcher Quest Atlas](https://github.com/StormTian/witcher-quest-atlas) | An interactive Witcher 3 quest and decision map, with local progress tracking and spoiler controls. | [Explore the map](https://stormtian.github.io/witcher-quest-atlas/) |

## Open-source contributions

_Selected work · updated 2026-10-09_

- **DeerFlow · merged:** Fixed sandbox commands hanging on stdin ([#6117](https://github.com/bytedance/deer-flow/pull/6117)), made Lark runtime readiness consistent ([#5994](https://github.com/bytedance/deer-flow/pull/5994)), and exposed Lark runtime image configuration in Helm ([#5835](https://github.com/bytedance/deer-flow/pull/5835)).
- **DeerFlow · open PRs:** Per-sandbox broker verification and persistent quarantine after uncertain shell execution ([#6436](https://github.com/bytedance/deer-flow/pull/6436)); model selection for individual IM conversations ([#6534](https://github.com/bytedance/deer-flow/pull/6534)).
- **dbx · merged:** Added MySQL generated-column editing, including VIRTUAL / STORED expressions and the corresponding CREATE / ALTER SQL ([#11252](https://github.com/t8y2/dbx/pull/11252)).

## Engineering focus

- **Reliable execution:** sandbox lifecycles, state recovery, tool integration, and permission boundaries.
- **Learning from source:** trace actual behavior, rebuild small subsystems, and verify changes with reproducible checks.

`Go` · `Python` · `Rust` · `TypeScript` · `Kubernetes` · `gRPC` · `ClickHouse` · `MCP`

> Build systems that make intelligence executable.
