# Podiom Home Assistant Apps

This repository is the Home Assistant app (add-on) store channel for
[Podiom](https://github.com/Podiom/Podiom) — agentic AI colleagues
(Claude Code & Codex) with a web UI, safely exposed through Home Assistant.

## Installation

1. In Home Assistant, open **Settings → Add-ons → Add-on store**.
2. Open the ⋮ menu → **Repositories**, and add:

   ```
   https://github.com/Podiom/ha-app
   ```

3. Install **Podiom** from the store, start it, and open it from the sidebar.

Installs that already use `https://github.com/Podiom/homeassistant-addons` keep
working through GitHub's repository redirect. Do not add a new repository at the
old name.

See the add-on's [documentation](podiom/DOCS.md) for the first-run walkthrough
(gateway token, CLI logins, backups, and security notes).

## Contents

| App | Description |
| --- | ----------- |
| [Podiom](podiom/) | The full Podiom stack: `podiomd`, web UI, the `claude` and `codex` CLIs, and a web onboarding terminal — behind Home Assistant Ingress. |

> This repository is generated: the sources live in
> [Podiom/Podiom](https://github.com/Podiom/Podiom) under `ha/addon/`, and
> release CI pushes each new version here. Please file issues and PRs against
> the main repository.
