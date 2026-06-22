---
type: integration_doc
title: David Workbrain Integration
description: Hermes Agent local integration notes for David Workbrain.
domain: shared
resource: markdown
agent_ready: true
sensitive_handling: No original source files or sensitive raw data are stored here.
tags:
  - david-workbrain
  - hermes
  - integration
timestamp: 2026-06-22
---

# David Workbrain Integration

## Purpose

This document records how the local Hermes checkout should work with the user's David Workbrain system.

Hermes should coordinate work, generate safe Codex instructions, review output, and grow by saving reusable procedures as Markdown skills or project rules.

## Local Repositories

| Repository | Path | Role |
|---|---|---|
| Hermes Agent | `E:\4종에이전트\hermes-agent-main` | Coordinator and self-improving agent |
| David Workbrain | `E:\Obsidian\2026david\david-workbrain` | Safe project knowledge and automation repo |
| Obsidian Vault | `E:\Obsidian\2026david\_ObsidianVault` | Final operational knowledge base |
| gbrain | `E:\4종에이전트\gbrain-master\gbrain-master` | Long-term knowledge structure reference |
| gstack | `E:\4종에이전트\gstack-main` | Execution pipeline reference |

## Operating Model

```text
Human request
→ Hermes interprets and checks risk
→ Hermes reads David Workbrain rules
→ Hermes generates Codex command
→ Codex executes Markdown/scripts/Git work
→ Hermes reviews result
→ reusable lesson becomes skill/SOP/template
→ GitHub commit
```

## Recommended Hermes Usage

Load the skill when starting David Workbrain work:

```text
/skill david-workbrain
```

or start Hermes with the skill preloaded if supported by the active interface:

```bash
hermes -s david-workbrain
```

## Growth Policy

Hermes may grow by storing:

- project workflow rules
- approval criteria
- command templates
- SOP structures
- file classification patterns
- review checklists

Hermes must not store:

- raw personal information
- applicant lists
- attendance sheets
- settlement evidence
- contracts
- account numbers
- passwords or tokens
- private contact details

