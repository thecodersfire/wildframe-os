# Built-in features for wildframe-os

Purpose: wildlife and nature photography, RAW image development, and photo editing

1. **prepare a creative project** — run wildframe-os-workspace. It creates ~/Documents/wildframe-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run wildframe-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/wildframe-os-session-plans/.
3. **check project and export readiness** — run wildframe-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/wildframe-os-workspace features/wildframe-os-plan features/wildframe-os-check "$HOME/.local/bin/"
