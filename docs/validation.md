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

Required continuation regression: a ten-item queue has one finished item, an uncertain Asana report, and one credential document requiring approval. The agent must preserve the report and checkpoint, hold the protected item, continue known safe independent work, identify who resumes an ended run, and refuse to call the project ready without a verified handoff/recovery arrangement. A written answer proves procedural understanding only; test actual pending-report recovery and resumption through the approved runtime before claiming live reliability.

Jack supplies the real test assignment and authorizes its changes. Amanda reviews the guide, SOP, and installed files and returns specific gaps. Verify a simple task and a multi-person project in Asana: actual sections, descriptions, subtasks, links, fields as needed, dates, dependencies, notification timing, ownership, and completion proof.

Record observed findings in the issue. Do not mark the SOP Pilot Passed or Active until the corresponding test evidence and acceptance exist.


## Assignment-clarity regressions — September 24 revision

Use a controlled drafting/review exercise first; do not change real VA assignments during the skill deployment test.

| Case | Expected observable behavior |
| --- | --- |
| Numbered noun titles; tasks or subtasks returned in reverse working order | Propose unnumbered verb-first titles; correct actual placement and require a new order read-back before ready. |
| "Do five graphics" with distinct source briefs and reviewers | Split independently finishable results or meaningful steps; preserve sensible batching and avoid click-level tasks. |
| Main task has no delivery slots; child says "see parent" | Deliverables block first; standalone child includes source, action, output, destination, and finish check. |
| Tasks in a VA section but assignees empty | Treat as unassigned; build and check complete batch, assign every actionable item, then read assignments back. |
| Tool creates project sections but cannot create required native child dividers | Report capability gap before copying the pattern; no fake heading tasks and no ready claim. |
| First worker path has a missing source or bad order | Correct and read back the pilot before scaling; do not treat counts as acceptance. |
| A tool response explicitly reports omitted skill content | Retrieve the missing relevant instructions before relying on them. This scenario does not claim Amanda's native reads were truncated. |
| Description uses "canonical route", "parent", and unspecified "evidence" | Give accurate everyday wording, exact return items and destinations; explain necessary terms. |
| Already authorized bounded project setup | Procedures for build quality, Advanced Control for authority; no circular requirement to load the assigned-task workflow or seek duplicate approval. |
| Bulk permission or cross-project change | Preserve preview/confirmation safeguards; setup authorization does not expand scope. |

Record prompts, actual skill reads, output, corrections, and limitations in the rollout issue. A simulated ordering exercise does not prove live Asana order or divider capability. Validate those on Jack's authorized real assignment before calling that assignment ready.
