---
name: z-asana-procedures
description: Create, repair, organize, assign, review, and complete routine Asana projects, tasks, and subtasks using ZedBiz procedures.
---

# Zed Asana Procedures

## Job and boundaries

Use for routine Asana project setup, task and subtask creation, sections, descriptions, template use, assignment, and delivery checks. Produce understandable work that is complete before its first assignment notification.

Do not use for unrelated business execution, general writing without an Asana assignment, or designing a venture implementation master. Use the separately maintained venture procedure for that specialized work. Its templates do not override the assign-last rule when releasing routine work.

This skill defines work quality and sequence. It does not supply an Asana connection, grant permissions, or replace the existing `z-asana-agent-control` and `z-advanced-asana-control` skills. Apply the appropriate access/authority skill before Asana calls. Use `z-agent-communication` for human-facing descriptions and messages.

## Sources and quick navigation

- [Main ZedBiz Asana guide](https://app.notion.com/p/3dca3e33d5818053a98df9635d006906): explanations and approved business guidance.
- [Operational SOP](https://app.notion.com/p/3dea3e33d58181bf896dd06bc39818bd): how people use this skill.
- [Projects](references/projects.md): choosing structure, project briefs, sections, views, and closeout.
- [Tasks and subtasks](references/tasks.md): descriptions, useful breakdowns, real subtask sections, ownership, and visibility.
- [Fields, rules, and templates](references/workflow.md): reuse, dates, dependencies, fields, rules, forms, and recurrence.
- [Review and completion](references/delivery.md): daily work, handoff, evidence, and completion.
- [Brief formats](assets/briefs.md): reusable project, task, subtask, review, and finish formats.
- [OpenClaw operation](references/openclaw.md): dependencies, discovery, approved tools, and read-back.
- [Source map](references/sources.md): guide coverage and official feature documentation.

Load only the reference needed for the request. Use installed procedures for routine work; do not fetch the entire guide on every task. Open the relevant guide section when the case is unfamiliar, an instruction conflicts, or the user asks for a current guide check. Treat current explicit user instructions as authoritative within allowed scope. Report unresolved source conflicts rather than silently mixing standards.

## Confirm the request and route

- Read the complete request and its actual source files. Extract intended outcome, scope, destination, deliverables, roles, reviewer, timing, links, preservation requirements, and approval limits.
- Verify the agent identity, workspace, approved PAT-backed MCP route, and required capabilities. Resolve exact object and user IDs from live records. Never use a personal connector or guessed IDs.
- Search likely existing projects and tasks. Reuse the existing record for the same outcome; link related but distinct work. Preserve useful task IDs, comments, and proof during repairs.
- In Diagnose mode, inspect and propose without writing. In Get-er-Done mode, execute the authorized scope. Existing authorization counts; ask only for an actually missing decision.
- A routine request does not authorize deletion, broad membership changes, shared-field changes, bulk rescheduling, or unrelated project redesign. Follow the advanced control skill for these boundaries.

## Plan the smallest usable structure

- Choose a project for several independently managed deliverables, a main task for one result, and a subtask for a part requiring its own owner, timing, discussion, review, or proof.
- Keep small same-owner checks in a checklist. Do not force every action into its own subtask. Do not impose a task-count conversion rule.
- Map the result to required work once. Include production, review, corrections, delivery, and proof where applicable. Keep the normal depth to main task plus actionable subtasks.
- Record intended owners in planning without setting live assignees. Use a suitable approved Asana template if available; inspect defaults, rules, recurrence, and copied links before instantiation.
- If an input is missing, complete independent preparation and ask the responsible person for the exact missing input. Do not guess material dates, source links, decisions, or field options.

## Build unassigned

- Build the project brief, sections, main tasks, and all required subtasks with delivery assignees unset. This also applies to simple new tasks and new subtasks added to existing work.
- Fill descriptions, working/source links, output destinations, completion requirements, relevant dates, dependencies, and review gates before release. Put deliverable links near the top.
- Use real project sections and real subtask sections. If the approved tool cannot create a required native divider, report the precise capability gap; do not invent a heading task or extra nesting as a substitute.
- Prevent template defaults, imports, forms, or rules from assigning unfinished work. If that cannot be guaranteed, use a safe unassigned creation route or stop that operation.
- A Setup section, future date, label, or “details coming” comment does not suppress assignment notifications.
- For existing assigned work, do not unassign automatically. Determine whether incomplete edits require a communicated pause; prepare the complete correction before changing the active brief. Preserve existing work and approvals.

## Check the entire release batch

Read the actual Asana objects back before the first assignment. A successful tool response or matching task count is insufficient.

- Verify correct project/team, section placement, main-task/subtask relationships, native dividers, and display order.
- Read every required task description: outcome, action, source inputs, constraints, destination, review, and observable completion checks must be usable.
- Check links and intended-user access using available evidence. The creator opening a link does not prove the worker can open it. State any access that remains unverified and resolve required access before release.
- Verify dates, genuine dependencies, relevant fields, intended workers/reviewers, and what must wait. Do not assume subtasks inherit assignees or all project properties.
- Confirm no unresolved input placeholders, missing required subtasks, or auto-assignment path remains. Final result links may be marked pending because producing them is the work.
- Check the whole assignment or self-contained release batch together. Do not assign a main task while still inventing its required breakdown.

## Assign last and verify release

Only after the full readiness check passes, set the intended assignees on the ready main tasks and subtasks. Assignment is the final setup step and may notify a person or start an agent immediately.

Read assignments back. State the next action and any prerequisite that must finish before execution. A future dependent step can be assigned if its brief is complete and its wait condition is clear. Assignment is not proof of receipt or work having started; report those states separately.

If assigned too early, promptly tell the affected worker setup is incomplete and what must wait. Finish and recheck before release. Unassigning does not recall the notification. Send messages only through a route authorized by the request or governing workflow; otherwise flag the needed pause to the requester immediately.

This is an instruction-level release gate. It is not a server-side permission lock or an automated Asana validator. Never claim technical enforcement that the installed tools do not provide.

## Work, review, and complete

Follow the delivery reference. Keep the current brief in the description and decisions in comments. Keep the main task with its delivery owner while a reviewer checks the output. Complete required subtasks and acceptance checks before completing the main task.

Respect the promised result: a test task that asks to run a test and record results can finish with documented failures and owned corrections; a task promising a working result cannot finish merely because the failures were recorded. Passing acceptance or an explicitly approved exception is required for release.

## Fail safely and report

- After an ambiguous write, read the current object before retrying. Do not duplicate tasks or repeat assignments because the response was lost.
- Stop after three failed attempts, or immediately for identity, authorization, permission, or materially expanded scope problems. State what exists, what remains, and the exact decision/tool needed.
- Preserve the last usable state. Do not delete partial setup, rewrite unrelated work, or reopen completed business work merely to repair logging.
- Return exact project/task links, changes made, checks performed, assignment status, and remaining exceptions. Say whether work is ready, partially prepared, or blocked.
- Store task decisions and proof in Asana. Follow the existing agent-control skill's activity-memory requirements. Record technical changes in GitHub and significant operational activity in the Technical Journal. Use Mountain Time for timed commitments.

The assignment is ready only when its actual structure and content passed read-back, its recipients have required access, and assignment happened after preparation. Business delivery is complete only when the promised result and acceptance checks pass.
