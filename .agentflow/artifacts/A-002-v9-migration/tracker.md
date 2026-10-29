# Tracker

## Identity

- **Work key:** A-002-v9-migration.

- **Active Ask:** A-002.

- **Goal:** Migrate the personal fork to v9.1 while preserving custom behavior.

- **Last update:** 2026-10-29 19:50:42 +0800.

- **Evidence commit:** uncommitted.

## Overall state

- **State:** active.

- **Reason:** Work remains.

- **Total:** 3.

- **Completed:** 0.

- **Remaining:** 3.

## Accepted task checklist

- [ ] **T-1:** Inventory every personal delta and map it to the pinned v9 implementation or an explicit port; retain the design contract and source revision. Proof: Git-tree comparison and independent read-only inventory. Source: A-002, "Migrate to v9 while preserving my custom features".

- [ ] **T-2:** Import v9 and preserve T3, OpenCode, local environment links, Windows equivalents, portable disposal and legacy local-hook discovery. Scope: skills/agentflow plus README/provenance documentation. Proof: red-first regression tests and complete packaged suite. Stop any unsupported or incompatible behavior rather than silently drop it. Source: A-002, "Migrate to v9 while preserving my custom features".

- [ ] **T-3:** Verify a real terminal journey, independent exact-source result review, local hook retirement, unchanged unrelated files and personal-only Git delivery. Proof: saved test/review results and commit/remote identity. Source: A-002, "Migrate to v9 while preserving my custom features".

## Accepted scope changes

- None.

## Current recovery

- **Current item:** T-1.

- **Last proven result:** None.

- **Active blocker or running process:** None.

- **Next safe action:** Finish inventory and import pinned v9, then port missing custom behavior.

- **Expected changed files:** skills/agentflow/, README.md, .agentflow/devlog.md, .agentflow/artifacts/A-002-v9-migration/.

## Completion proof

- **All accepted tasks checked:** no.

- **Blocking accepted decision:** none.

- **Operation running:** no.

- **Next action remaining:** T-1.

- **Evidence status:** current.

- **Judgment:** active.

## Update meaning

- Saving this tracker is a recovery checkpoint, not a stop signal.

- For completed work, Evidence commit names the Git evidence commit, or is not applicable in a plain folder. Local file and test proof is still required.

- Work continues with the next unfinished item unless an independent stop condition applies.
