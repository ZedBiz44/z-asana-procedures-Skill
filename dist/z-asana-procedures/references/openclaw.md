# OpenClaw operation

## Dependencies and routing

The host must supply an approved agent-specific PAT-backed Asana MCP connection plus `z-asana-agent-control`, `z-advanced-asana-control`, and `z-agent-communication`. This package adds no credentials or tool server.

Inspect available tool schemas for the exact requested operation. Use supported current-user, object lookup, task/project reads, create/update, section, ordering, and dependency tools. Do not invent method names, HTTP endpoints, arguments, enum values, or IDs. Native subtask sections require their own verified capability; project-section support alone is insufficient.

Readiness uses actual object reads and human-readable evidence. No bundled program enforces the assignment boundary. The agent must follow the core sequence and the host's authority controls.

## Installation and discovery

Install the directory `z-asana-procedures` in the target agent's active workspace skills root. Inspect actual runtime paths before deployment. Use the current OpenClaw skills list/info command with explicit agent ownership where required. Confirm the package resolves from the intended workspace, is eligible, enabled, and model-visible.

Use a fresh session to test selection; existing sessions may retain old skill metadata. Do not restart a busy gateway merely to refresh a test. The maintainer's deployment record identifies the exact committed package and host paths.

## Scope of this procedure

Select this skill for routine project/task quality and structure. Apply access controls alongside it. Select the specialized venture implementation skill for venture master design; do not import its blanket every-action-is-a-subtask rule into routine work.

When the user asks only for a plan or review, produce that result without Asana writes. Do not automatically message workers, create test assignments, or change production projects during a skill smoke test.
