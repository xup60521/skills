* _2026-10-29 19:51:53 +0800 (gpt-6.1-sol/medium)_

# Personal Agentflow v9 migration

The owner chose "Migrate to v9 while preserving my custom features" after the v8/v9 comparison. Import pinned upstream 9.1.0 at `6c3537debc38e207da24ab6f25dcacbe98051541`, retaining the collection layout and personal behavior. Delivery is exclusively to `xup60521/skills`; no upstream PR or push.

## Requirements and scope

- R-1: Replace `skills/agentflow/` with the v9 skill, including its feature CLI, parallel-group looper, assets and references. Preserve Apache licensing, pin provenance and document updating the personal fork. Keep the unrelated HTML-summary skill and historical v8 changelog.
- R-2: Preserve T3-native delegation using actual provider/model capabilities, complete fresh-context assignments, truthful pending/stopped results and no silent substitution. Adapt the instructions to current T3 tools. Do not restore the obsolete v8 runner API or contradict host orchestration rules.
- R-3: Preserve OpenCode provider/model and optional variant selection for external workers, including the looper. Keep literal arguments, complete Unicode stdin, bounded assignment, exact attempt result validation and error reporting. Do not revive the absent repository-root OpenCode hook plugin or claim CLI permissions are a sandbox.
- R-4: Preserve `.env.local` and `.env.production` links in feature worktrees, including nested application directories, existing-target preservation and Windows hard-link fallback. Skip Git, dependencies, record directories and nested checkouts. Never print secret bytes or stage these files. A linking failure warns without stranding successful feature preparation.
- R-5: Retain the equivalent v9 Windows shell, literal-command/shim, CRLF/Unicode, physical path and process-tree protections. Retire old notebook/bootstrap/Stop-hook code with the corresponding v8 subsystem, rather than maintaining two incompatible ordinary runtimes. Detect `.claude/settings.local.json` as well as the upstream migration surfaces. Preserve portable recoverable disposal where applicable; never claim native Windows proof from Linux tests.
- R-6: Keep personal installations on the personal source. Upstream release discovery may suggest comparison, but may not replace personal files with a stock upstream installation. Save an explicit upstream revision and local patch inventory.

## Approach and boundaries

1. Inventory the local delta against preserved v8. The host owns requirements/specification and synthesis; a fresh read-only native worker checks the inventory. The current v8 runtime is snapshotted at `/tmp/agentflow-migration-17w84_uf/v8` solely to finish this already-open notebook round after replacing the skill source.
2. Import the pinned v9 tree, removing tracked obsolete v8 files. Add the smallest ports at the existing v9 feature, provider and instruction boundaries. Add regression tests first, observe their failures against stock v9, then implement the ports.
3. Run the complete shipped v9 suite because this replaces the whole skill runtime, plus focused fork contracts and a real PTY feature journey. Provider sessions/native Windows require actual available tools; disclose unavailable observations without fabricating them.
4. Commit the implementation, obtain one independent acceptance/security/result review of the exact source, resolve concrete in-scope defects, then close and push the personal repository.

This request updates the shipped skill. The repository's active `ag.json` and historical notebook are retained for this v8-recorded round; the next v9 activation follows its guarded project migration. Before delivery, retire or safely rebind this task's installed local v8 hook so it cannot refer to deleted source. No global shell/profile/plugin installation is replaced. Existing user projects and queues are not automatically migrated.

## Invariants

- INV-1: Starting with the current personal repository, only the Agentflow skill, relevant source/provenance documentation and this round's records change. Unrelated owner content/history remains byte-identical. Any upstream publication, unrelated edit or historical rewrite fails this invariant.
- INV-2: Starting with independent v9 groups, their worktrees, notebook ownership, fresh sequential task sessions, queue claims and serialized integration remain intact. A custom provider or environment link must not bypass attempt identity, stopped-writer or integration checks.
- INV-3: Starting with an environment file or existing feature target, linking never copies secret bytes to a report, replaces an existing destination or stages local environment files. Failures remain visible and nonfatal to otherwise successful feature preparation.
- INV-4: Starting with an explicit provider/model/variant, argv and stdin preserve the selection and content literally. Unsupported controls fail clearly; no model/provider substitution, shell interpolation or invented permission enforcement is allowed.
- INV-5: Starting with a project containing mixed old hooks, migration removes only proven Agentflow-owned units, including local Claude settings, and preserves foreign settings and all conversation bytes. Ambiguity stops dependent migration.

## Acceptance criteria

- AC-1 / INV-1: The installed skill identifies v9.1.0 and its package tests run without v8 script dependencies. Verify the pinned-tree delta contains only documented personal ports and packaging records; unrelated collection files remain unchanged.
- AC-2 / INV-2, INV-4: A fake OpenCode executable receives the exact provider/model and non-default variant plus Unicode stdin and returns one attempt-bound result; default variant adds no variant flag. Malformed, failed or stale output refuses acceptance. Existing Codex/Claude/Copilot and concurrent-group tests continue passing.
- AC-3 / INV-3: New feature creation links nested environment files; existing targets remain unchanged; a symlink-permission refusal uses a hard link; unrelated files and record/dependency/nested-checkout paths are excluded. Tests and a real terminal creation journey prove observable behavior.
- AC-4 / INV-4: T3 instructions require capability discovery, supported exact selection, complete bounded assignments, new delegate calls for review rounds, cancellation of replaced work and compliance with the host's returned next action. Static contract checks detect contradictory polling/checkout instructions.
- AC-5 / INV-1, INV-5: Migration instructions explicitly inspect both Claude settings files and Codex hooks; the README records personal update source, removed v8 runtime contracts and Windows/provider proof limits. No dangling internal Markdown/script references remain.
- AC-6 / INV-2: Linux feature preparation and merging retain recoverable owned-marker handling, with no permanent-delete fallback for foreign/untracked data. Windows equivalents use upstream safe command/path handling; unsupported disposal remains a disclosed refusal rather than fabricated support.

## Minimality check

The smallest complete outcome is the stock v9 skill plus ports for behavior absent from it, source/provenance notes and regression checks. Keeping v8 alongside it would duplicate incompatible configuration, hooks, queues and notebook machinery. Copying all local v8 modules would defeat the requested migration. Reuse v9's existing worker launch, feature lifecycle, ownership and process-observation mechanisms; add no new scheduler, provider selection hierarchy or visual design.

## Gates and review

The current recorded configuration has `away-gates: on`; the skill permits automatic Design Go/Result Go only after their evidence passes. User authorization supplies the migration outcome, not fabricated human sign-offs. Preserve owner-only decisions. The inventory and this contract precede source changes; the final independent pass covers outcome, minimality, conformance and affected trust boundaries. Any actual incompatible custom requirement is reported before abandoning it.

Self-check: This contract distinguishes preserved behavior from v8 implementation details superseded by the explicitly selected v9 architecture; native-platform proof remains separate from code portability.
