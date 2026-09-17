# Validation and acceptance

## Package checks

- Run the ZedBiz skill-development validator against `z-asana-procedures`.
- Confirm the folder and frontmatter name match, description is under 160 characters, shared frontmatter has only name/description, and SKILL.md is under 500 lines.
- Check every relative link resolves and required references are linked directly from SKILL.md.
- Inspect the package for secrets, unsupported API names, hidden side effects, duplicated conflicting rules, and scope creep.
- Confirm the core includes unassigned construction, whole-batch read-back, assign-last, uncertain-write handling, and inherited access controls.

## Fresh-session scenario tests

Use Amanda's existing runtime in new isolated session keys with no channel delivery. Do not change the model, credentials, gateway configuration, live assignments, or venture skill.

| Case | Prompt shape | Expected behavior |
| --- | --- | --- |
| Positive | Plan a routine Asana website project with tasks and subtasks; do not write | Select this skill, use local references, build unassigned, verify before release |
| Paraphrased positive | Organize a team assignment with a main task and separately owned review | Same procedure without requiring its exact name |
| Boundary | Repair an already assigned incomplete task | Communicate required pause; do not silently unassign or duplicate |
| Boundary | One owner needs two small checks | Checklist allowed; no blanket every-action subtask rule |
| Boundary | Tool supports project sections but not subtask dividers | Report missing native capability; do not create fake heading tasks |
| Negative | Write unrelated marketing copy without Asana work | Do not select this skill |
| Specialized | Design a venture implementation master | Route to specialized venture procedure; preserve that skill |

Inspect actual skill reads and response, not only a self-reported “passed.” A classification exercise does not prove automatic triggering; capture fresh positive and negative behavior separately.

## Practical acceptance with Jack

Jack supplies the real test assignment and authorizes its changes. Amanda reviews the guide, SOP, and installed files and returns specific gaps. Verify a simple task and a multi-person project in Asana: actual sections, descriptions, subtasks, links, fields as needed, dates, dependencies, notification timing, ownership, and completion proof.

Record observed findings in the issue. Do not mark the SOP Pilot Passed or Active until the corresponding test evidence and acceptance exist.
