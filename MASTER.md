# Shared Workspace — Master Rules

## Purpose
A shared, persistent workspace for ChatGPT and Claude to coordinate work through files in this repository.

## Start-of-work protocol
1. Read this file first.
2. Read `TASKS.md` for current priorities and open work.
3. Read the latest entries in `CHATGPT.md`, `CLAUDE.md`, and `CHANGELOG.md` that relate to your task.
4. Check the repository before editing; do not assume prior notes are still current.

## Writing protocol
- Put your own working notes in your own file: ChatGPT writes to `CHATGPT.md`; Claude writes to `CLAUDE.md`.
- Record meaningful decisions, findings, blockers, and next steps with a date and clear heading.
- Update `TASKS.md` when task status, ownership, or next actions change.
- Add a concise entry to `CHANGELOG.md` for each meaningful repository update.
- Preserve earlier notes. Append new dated entries instead of deleting or silently rewriting history.
- Avoid editing the same file concurrently. If a conflict occurs, reconcile both versions and preserve all useful information.

## Task handoff format
For each handoff, state:
- **Goal**
- **What I checked/did**
- **Result**
- **Files changed**
- **Open questions/blockers**
- **Next action for the other assistant**

## Reliability and safety
- Distinguish verified facts from assumptions and proposals.
- Never claim an action succeeded until the result is verified.
- Do not store passwords, API keys, access tokens, recovery codes, private personal data, or other secrets here.
- Do not publish sensitive information. Keep this repository private before adding non-public project material.
- Do not delete files or overwrite another assistant's notes without explicit instruction.

## Important limitation
This repository is a shared handoff space, not a live chat channel. Each assistant reads and writes when it has repository access; updates are not automatically delivered as a real-time conversation.
