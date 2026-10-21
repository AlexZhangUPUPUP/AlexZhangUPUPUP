<div align="center">

# Alex Zhang

**I build agent harnesses — the runtime layer between a model and a codebase.**

<sub>TypeScript · Bun · React · MCP · ACP · OS-level sandboxing</sub>

[Documentation](https://alexzhangupupup.github.io/micro-harness/) · [Latest release](https://github.com/AlexZhangUPUPUP/micro-harness/releases) · [GitHub](https://github.com/AlexZhangUPUPUP)

</div>

---

## Now

**[micro-harness](https://github.com/AlexZhangUPUPUP/micro-harness)** `v0.2.1` — a general-purpose agent harness built from scratch.

- **Own loop.** Model calls, tool dispatch, context compaction, and one event stream that is simultaneously the session log, the SSE feed, the replay source and the inspector.
- **Explicit boundaries.** Four permission presets, per-call approvals, and OS-level sandboxing (Seatbelt / bubblewrap) that fails closed and hides credential stores by default.
- **Both directions of protocol.** MCP client for external tools, MCP server for other agents, ACP server for editors — one kernel behind the CLI, the web UI and the editor.
- **Measured, not claimed.** ~13.4k lines of TypeScript, 238 tests, a 26-task eval suite, and CI on macOS and Linux.

## Selected work

| Project | What it is |
| --- | --- |
| **[micro-harness](https://github.com/AlexZhangUPUPUP/micro-harness)** | Agent harness: loop, tools, multi-agent, sandbox, evals. `v0.2.1` · [Docs](https://alexzhangupupup.github.io/micro-harness/) |
| **[PiStudio](https://github.com/AlexZhangUPUPUP/PiStudio)** | Desktop GUI for [pi](https://github.com/earendil-works/pi) — parallel sessions, image paste, streaming transcript. Electron + React. |

## Toolbox

`TypeScript` `Bun` `React` `SQLite` `MCP` `ACP` `Seatbelt` `bubblewrap`

## Principles

> Readable kernels · explicit boundaries · honest numbers.

<details>
<summary>中文</summary>

做 **Agent Harness**——模型与代码库之间的运行时层。

目前在维护 [micro-harness](https://github.com/AlexZhangUPUPUP/micro-harness)：从零实现的通用 Agent Harness，自有循环、OS 级沙箱（Seatbelt / bubblewrap）、MCP + ACP，CLI 与 Web 共享同一内核；约 1.34 万行 TypeScript、238 个测试。

</details>
