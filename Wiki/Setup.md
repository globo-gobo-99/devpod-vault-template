---
created: 2026-11-02
modified: "2026-11-02T17:36"
---
# Starter setup

Activate `.gobsidian` explicitly; do not copy it into an existing personal config folder.
Core daily notes are configured to open today's note on startup. Date format is `YYYY-MM-DD`
and uses the device's current timezone; choose one convention across devices before use.
Templates use Obsidian's native `{{date}}`/`{{time}}` tokens, not invented historical dates.

Ctrl-backtick copies the file path; Ctrl-Shift-Enter toggles source. Ctrl-Shift-Left/Right
are assigned to previous/next tab. Alt+`|` and Alt+`-` are proposed splits and need real device
checks. Rootshell/tmux settings are a separate remote-terminal contract.

Recent Edits was present in the supplied reference; install it yourself through Obsidian's
reviewed community-plugin flow if desired. This starter includes no plugin binaries or plugin
data. Lean Terminal is desktop-only and is not required for essential flows.

Sync code/other files only after inspecting and preserving current settings. Hidden files are
excluded by native Sync; transport selected hidden source files separately with filtered rsync
and handle Git metadata with Git-aware operations. Keep dependencies, caches and secrets out
of synced project source. One human chooses one writing host per project; there is no lock,
presence detector or automatic host-switch orchestrator.

## See also

- [[README]]
