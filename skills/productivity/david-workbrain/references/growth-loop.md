---
type: reference
title: David Workbrain Growth Loop
description: How Hermes should safely grow while working on David Workbrain tasks.
domain: shared
resource: markdown
agent_ready: true
sensitive_handling: Store procedures, not sensitive raw data.
tags:
  - david-workbrain
  - hermes
  - growth-loop
timestamp: 2026-06-22
---

# David Workbrain Growth Loop

## Safe Growth

Hermes grows by capturing repeatable procedures, not raw private data.

Safe to store:

- classification rules
- command templates
- SOP improvements
- recurring document structures
- review checklists
- GitHub safety checks
- lessons from mistakes

Not safe to store:

- personal data
- applicant names
- attendance details
- account numbers
- passwords
- private contacts
- contract contents
- settlement evidence details

## After Each Task

Hermes should ask:

1. Did this task reveal a reusable rule?
2. Did Codex need a better command template?
3. Did a safety rule prevent a mistake?
4. Did the Obsidian structure need a new MOC/SOP pattern?
5. Should the lesson be added to `david-workbrain` or this Hermes skill?

## Where to Save New Knowledge

| Knowledge type | Save location |
|---|---|
| Project rule | `E:\Obsidian\2026david\david-workbrain\docs` |
| Agent workflow | `E:\Obsidian\2026david\david-workbrain\agents` |
| Codex command | `E:\Obsidian\2026david\david-workbrain\agents\hermes_to_codex_command_templates.md` |
| SOP | `E:\Obsidian\2026david\david-workbrain\templates` or Obsidian Vault |
| Hermes-specific reusable procedure | `E:\4종에이전트\hermes-agent-main\skills\productivity\david-workbrain` |

## Commit Rule

Every growth update should be committed after safety checks.

```bash
git status --short
git diff --cached --name-only
```

Do not commit original source files or sensitive documents.

