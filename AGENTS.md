# Instructions for AI Coding Agents

You are working on Pixel Candy Glass. Read this file and the relevant specification before proposing or making changes.

## Authority and approval

- The project owner is the final authority on product decisions.
- Approved specifications are the source of product requirements.
- If documents conflict, do not silently choose one. Identify the conflict and ask the owner.
- Starter documents are not proof that a feature has been approved or implemented.
- Do not invent app inventory, progression formulas, companion mechanics, data rules, visual references or platform decisions.

## Mandatory preservation rule

This project grows from earlier Mochi Calendar / Mochi Workspace work. Before modifying source:
1. Inspect the current branch and working tree.
2. Read the relevant spec and existing implementation.
3. Identify existing behaviors and data affected.
4. Propose a small implementation plan.
5. Obtain owner approval for removals, rewrites, migrations or material behavior changes.

Never delete, replace, rename or silently simplify existing apps, features, routes, data, assets or interactions. Never replace a working feature with a placeholder. Prefer the smallest safe incremental change.

## Visual direction

- Candy Glass governs the mobile shell, navigation, productivity interfaces, forms and controls.
- Pixel art is a deliberate art language for the world, environments, companions, props and collectibles.
- Do not apply pixelation to the whole UI.
- Do not flatten the design into generic pastel SaaS, generic bento layouts or blur-only glassmorphism.
- Preserve approved typography and custom assets.
- Every visible control must work and have interaction states.
- Rich visuals must not compromise hierarchy, touch usability, contrast, accessibility or performance.

## Implementation discipline

- Antigravity is the planned primary implementation owner.
- Do not have multiple agents edit the same working tree concurrently.
- Parallel agents should perform read-only analysis or use isolated branches/worktrees.
- Work in small, reviewable increments tied to GitHub Issues.
- Do not make speculative framework changes or full rewrites.
- Keep domain data and transient UI state appropriately separated.
- Prevent duplicate event processing and duplicate rewards.
- Do not claim a durable save or reward until it has actually persisted.
- Never commit secrets, credentials, private user data or unlicensed assets.

## Required workflow for each task

1. Read the linked specification and issue.
2. Inspect existing code and dependencies.
3. Report a concise plan, affected files, risks and tests.
4. Wait for approval when scope affects existing behavior or data.
5. Implement only the agreed scope.
6. Run tests and inspect the result at relevant mobile sizes.
7. Verify persistence, navigation, error states and relevant regressions.
8. Record evidence and commit SHA.
9. Update issue implementation and verification status separately.
10. Provide a handoff: completed, not completed, known issues, decisions needed and next task.

## Completion standard

A task is not verified because it compiles, renders or an AI reports success. It needs acceptance evidence. For UI work include mobile screenshots and interaction checks. For data work include persistence/reload and duplicate-event checks. For changes to existing features include regression evidence.

If requirements are unclear, stop and ask one focused question rather than guessing.
