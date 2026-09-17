# Implementation profile

## Ownership and sources

- Publisher: ZedBiz; identifier `z-asana-procedures`; display name Zed Asana Procedures.
- Technical source: this repository, branch `main`.
- Operational source: main guide in A-Guides and the linked SOP in z-Skills.
- Tracking: repository issue #1 and the existing Cody Technical Journal entry for 2026-09-16.
- Distribution: user-designated GitHub repository and Amanda only. No marketplace or fleet publication is authorized by this release.
- Licensing: no new third-party license is imposed; see NOTICE.md. Preserve this repository's ownership and attribution.

## Platform and package

Target: Amanda's existing OpenClaw runtime on VPS1. Use the live-discovered workspace skills root. Keep platform-specific routing in references/openclaw.md. No additional server, background job, hook, credential, or integration is needed.

The package is a procedural skill because it selects and sequences existing capabilities. A future machine-enforced release tool would be a separate implementation and test effort, not an implied feature of this package.

## Authority and rollout

Jack explicitly authorized building, publishing, creating the SOP, deploying to Amanda, and removing the overlapping asana-executable-project learned skill after replacement. The asana-implementation-template learned skill is preserved unchanged. Jack will perform practical testing with Amanda afterward.

Ordinary skill execution respects Get-er-Done or Diagnose mode and the existing control skills. No production Asana test assignments are part of package validation. A fresh-session read-only scenario test is permitted for the skill pilot. Broader rollout requires a separate request after the pilot.

## Safeguards and evidence

No secrets, full configs, private task data, or user message transcripts belong in this public repository. Use secure runtime credentials through existing approved tools. No bundled script executes shell commands, writes Asana, or makes network requests.

Validate metadata, direct references, source alignment, trigger boundaries, installation paths, loaded source, and deployed file hashes. Stop after three failed attempts, or immediately for identity/access/scope failures. The deployment document defines recovery. Report structural and scenario results separately from Jack's live acceptance testing.
