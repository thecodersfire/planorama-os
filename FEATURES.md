# Built-in features for planorama-os

Purpose: project management

1. **organize work and records** — run planorama-os-workspace. It creates ~/Documents/planorama-os-workspace/ with Tasks, Records, Reference folders.
2. **plan a focused work session** — run planorama-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/planorama-os-session-plans/.
3. **check records and task readiness** — run planorama-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/planorama-os-workspace features/planorama-os-plan features/planorama-os-check "$HOME/.local/bin/"
