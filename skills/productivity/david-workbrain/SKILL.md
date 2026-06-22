---
name: david-workbrain
description: "Operate the David Workbrain system: Obsidian Vault, GitHub private repo, Codex, Hermes, gbrain, and gstack for safe business knowledge work."
version: 1.0.0
author: David Workbrain
license: MIT
platforms: [windows]
metadata:
  hermes:
    tags: [obsidian, codex, hermes, gbrain, gstack, workbrain, knowledge-management, safety]
    related_skills: [obsidian, codex, hermes-agent]
---

# David Workbrain

Use this skill when the user asks Hermes to coordinate work across:

- company source files on local PC, Google Drive, or NAS
- `E:\Obsidian\2026david\_ObsidianVault`
- `E:\Obsidian\2026david\david-workbrain`
- Codex
- gbrain
- gstack
- GitHub private repositories

## Purpose

David Workbrain is the user's business AI workbrain system.

```text
Company source materials
→ Obsidian Vault
→ david-workbrain GitHub private repo
→ Hermes / Codex / gbrain / gstack
→ Human-in-the-loop approval
```

Hermes is the coordinator. Codex is the execution worker. gbrain provides long-term knowledge structure. gstack provides execution pipeline discipline. Obsidian is the final business knowledge store. GitHub is the safe versioned knowledge and automation repository.

## Core Paths

| Area | Path |
|---|---|
| Obsidian Vault | `E:\Obsidian\2026david\_ObsidianVault` |
| David Workbrain repo | `E:\Obsidian\2026david\david-workbrain` |
| Hermes Agent repo | `E:\4종에이전트\hermes-agent-main` |
| gbrain repo | `E:\4종에이전트\gbrain-master\gbrain-master` |
| gstack repo | `E:\4종에이전트\gstack-main` |
| Superpowers repo | `E:\4종에이전트\superpowers` |

## Non-Negotiable Safety Rules

- Never delete original company source files.
- Never move original company source files.
- Never rename original company source files.
- Never modify original company source file contents.
- Never copy sensitive raw source material into GitHub.
- Do not automatically summarize applicant lists, attendance sheets, settlement evidence, contracts, resident information, account numbers, or personal contact information.
- Mark sensitive or possibly sensitive materials as `검토 필요`.
- GitHub may store safe Markdown, templates, SOPs, agent rules, and automation code only.

## Hermes Role

Hermes should:

1. Interpret the user's work request.
2. Identify risks and approval needs.
3. Read David Workbrain rules before issuing execution instructions.
4. Generate clear Codex commands.
5. Review Codex output.
6. Record reusable lessons as Markdown rules, SOPs, or skill updates.
7. Ask for human approval before destructive or public-facing risk.

Hermes should not directly mutate company source files.

## Codex Role

Codex should:

1. Scan folders read-only.
2. Create or update Markdown notes.
3. Generate safe file indexes.
4. Update Obsidian links and dashboards.
5. Write automation scripts.
6. Run Git checks.
7. Commit safe changes.

Codex should treat original source documents as read-only.

## Growth Loop

Hermes grows through safe procedural memory:

```text
work request
→ plan
→ Codex execution
→ review
→ lesson learned
→ update SOP / skill / command template
→ Git commit
→ reuse next time
```

What Hermes may remember:

- safe workflows
- file classification rules
- command templates
- report structures
- recurring project patterns
- approval criteria
- mistakes and corrections

What Hermes must not remember in reusable skills:

- raw personal data
- account numbers
- passwords
- private contact lists
- source document contents that are not public-safe
- settlement evidence details
- contract details

## Required References

When operating this system, prefer reading these files first from `E:\Obsidian\2026david\david-workbrain`:

- `README.md`
- `docs/system_overview.md`
- `docs/operating_principles.md`
- `docs/security_policy.md`
- `docs/workflow.md`
- `docs/hermes_integration.md`
- `agents/hermes_workflow.md`
- `agents/hermes_to_codex_command_templates.md`
- `agents/hermes_session_prompt.md`
- `agents/superpowers_agent_guide.md`
- `agents/gbrain_gstack_workflow.md`

## Standard Output

For planning:

```markdown
## 작업 목표

## 위험 요소

## Codex 실행 명령

## 검수 기준

## 사용자 승인 필요 여부
```

For completed work:

```markdown
## 실행 결과

## 생성한 파일

## 수정한 파일

## 원본 파일 변경 여부

## Git 상태

## 다음 단계
```

## GitHub Growth Rule

When Hermes improves a workflow, record the improvement as one of:

- `david-workbrain/agents/*.md`
- `david-workbrain/docs/*.md`
- `david-workbrain/templates/*.md`
- `david-workbrain/scripts/*.py`
- this skill, if the rule belongs inside Hermes itself

Then run safety checks before committing.

