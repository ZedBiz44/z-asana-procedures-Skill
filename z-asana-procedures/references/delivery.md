# Define delivery, review, and completion

Use this reference when creating or repairing tasks. Workers use `z-asana-agent-control` to execute and complete the assignment; they do not need to load this setup reference for ordinary work.

## Make the finish condition observable

- Name the exact output, format, destination, required proof, reviewer, and approval needed. Provide source and destination links before assignment.
- Give each subtask its own observable result. Define the main assignment's full result separately so one finished step cannot be mistaken for the whole delivery.
- State which agent owns the main assignment and which action subtasks it must work through. Mark work owned by other people and genuine wait conditions clearly. Put the next-step instruction in each item that can arrive as a separate notification.
- Keep the current instructions in the description and decisions in comments. Provide slots for working files, final output, and proof where useful.

## Set up review without a dependency cycle

- Keep the main task with its delivery owner. Prepare any review task fully before assigning it.
- Make review depend on the saved draft or handoff, not on completing a main task that requires that review.
- Define an initial review as a response: acceptance or specific requested corrections. Corrections can then proceed, followed by final acceptance. Do not make corrections depend on final approval.
- Name the reviewer, exact version to review, checks, and place to return the decision. Specify what the worker may continue while waiting and what must wait for approval.

## Match the checks to the promised result

- Research needs a recommendation, sources, uncertainty, and the requested decision.
- Content and design need editable files, required versions, checks, and exports. Require publication proof only if publishing is authorized.
- Websites and technical work need checks of the actual result, including the relevant customer paths or behavior.
- Administration needs the saved record or file and a check that the requested changes are present.

A task to run and record a test can finish with documented failures and owned corrections. A task promising a working result needs passing checks or an expressly approved exception. Moving unfinished required work into a follow-up does not change the original promise without approval.

Set the main task's finish condition to require all necessary subtasks, saved outputs, checks, approvals, and handover. Setup is complete when the assignment is ready and properly released; business delivery is a separate result.
