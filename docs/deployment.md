# Deployment and recovery

## Approved target

Amanda only, existing VPS1 OpenClaw agent `main`. Verify these locations again before applying an update:

- Container package: `/home/node/.openclaw/workspace/skills/z-asana-procedures`.
- Host workspace root: `/opt/openclaw/agents/amanda/workspace/skills`.
- Retired learned package: `/home/node/.openclaw/agents/main/agent/workshop-skills/asana-executable-project`.
- Preserved learned package: `/home/node/.openclaw/agents/main/agent/workshop-skills/asana-implementation-template`.

## Release order

- Validate and commit the package to GitHub before copying it into the workspace.
- Capture the old routine skill as a non-installable historical text file in GitHub. Keep recovery outside all runtime discovery roots.
- Transfer the exact committed package and compare its files and hashes on the target.
- Confirm OpenClaw discovers the intended workspace package as enabled, eligible, and model-visible.
- Verify the old routine skill still matches the inspected hash before removing its exact package directory. Never remove unrelated workshop proposals or skills.
- Verify the old skill is no longer discoverable and the venture skill's hash is unchanged.
- Use a new session for selection and read-only behavior tests. Do not disrupt active chats with an unnecessary gateway restart.
- Record the deployed commit, file manifest, discovery, retirement, tests, and limitations in issue #1 and the Technical Journal.

## Recovery

If the new package causes a material failure, stop affected Asana setup and preserve existing task state. Reinstall the last approved package from its Git commit. For an initial-release rollback, remove only the verified new package and restore the historical routine skill from its exact Git-backed text source if the responsible owner chooses that fallback. The old source contains the early-assignment defect, so restoration is not a fix and requires the assign-last instruction to remain explicit.

Never retain backup SKILL.md trees inside active skill roots. Do not restore the old routine package alongside the replacement as competing active instructions. Resume only after discovery and fresh-session verification pass.
