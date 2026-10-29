# Tracker

## Identity

- **Work key:** A-002-v9-migration.

- **Active Ask:** A-002.

- **Goal:** Migrate the personal fork to v9.1 while preserving custom behavior.

- **Last update:** 2026-10-29 20:33:46 +0800.

- **Evidence commit:** uncommitted.

## Overall state

- **State:** active.

- **Reason:** Work remains.

- **Total:** 3.

- **Completed:** 2.

- **Remaining:** 1.

## Accepted task checklist

- [x] **T-1:** Inventory every personal delta and map it to the pinned v9 implementation or an explicit port; retain the design contract and source revision. Proof: Git-tree comparison and independent read-only inventory. Source: A-002, "Migrate to v9 while preserving my custom features".

- [x] **T-2:** Import v9 and preserve T3, OpenCode, local environment links, Windows equivalents, portable disposal and legacy local-hook discovery. Scope: skills/agentflow plus README/provenance documentation. Proof: red-first regression tests and complete packaged suite. Stop any unsupported or incompatible behavior rather than silently drop it. Source: A-002, "Migrate to v9 while preserving my custom features".

- [ ] **T-3:** Verify a real terminal journey, independent exact-source result review, local hook retirement, unchanged unrelated files and personal-only Git delivery. Proof: saved test/review results and commit/remote identity. Source: A-002, "Migrate to v9 while preserving my custom features".

## Accepted scope changes

- None.

## Current recovery

- **Current item:** T-3.

- **Last proven result:** Full suite 317 tests, 307 pass, 0 fail, 10 platform skips, twice consecutively; real PTY terminal journey runs on Linux; independent review findings fixed with red-first tests; v8 Codex hook and git pre-commit hook retired to Trash.

- **Active blocker or running process:** Push to origin awaits owner confirmation.

- **Next safe action:** Owner confirms push of local commits to xup60521/skills origin/main; then close the round.

- **Expected changed files:** skills/agentflow/, README.md, .agentflow/devlog.md, .agentflow/artifacts/A-002-v9-migration/.

## Completion proof

- **All accepted tasks checked:** no.

- **Blocking accepted decision:** none.

- **Operation running:** no.

- **Next action remaining:** T-3.

- **Evidence status:** current.

- **Judgment:** active.

## Update meaning

- Saving this tracker is a recovery checkpoint, not a stop signal.

- For completed work, Evidence commit names the Git evidence commit, or is not applicable in a plain folder. Local file and test proof is still required.

- Work continues with the next unfinished item unless an independent stop condition applies.
