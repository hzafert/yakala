# Axiom Project Contract

This repository is a project module in Zafer's Axiom operating system. Canonical cross-project context and authority rules live in `hzafert/axiom`.

## Rules
1. Preserve this repository's project-specific source of truth and history.
2. Axiom may read and analyze this repository when relevant to an active goal or project.
3. Axiom may prepare diffs, drafts, recommendations and proposed changes without write authority.
4. Writing, deleting, merging, publishing, changing permissions, or other consequential mutations require Zafer's explicit approval for the identified target and bounded change/batch.
5. After an approved write, verify the resulting repository state before reporting completion.
6. Never treat access as standing write permission; unrelated future writes require new approval.
7. Never commit secrets, credentials, tokens, or private keys.
8. If project-specific rules conflict with generic Axiom defaults, surface the conflict and preserve the stricter/project-specific constraint unless Zafer explicitly changes it.

## New repository standard
Every Zafer repository managed through Axiom should contain an `AGENTS.md` linking it to the canonical `hzafert/axiom` authority and context model.