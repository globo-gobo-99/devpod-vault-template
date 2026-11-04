---
sensitivity: public
created: 2026-11-02
modified: "2026-11-02T22:08"
---
# Starter setup

Activate `.gobsidian` explicitly. If that folder already exists, back it up before copying the reviewed JSON files directly into it; do not nest another `gobsidian` directory inside it. See [[Wiki/First boot]] for the download and profile-recovery sequence.
The main `openBehavior: daily` setting opens today's daily note on startup. The daily-note template path includes its extension: `Templates/Daily.md`. Date format is `YYYY-MM-DD`
and uses the device's current timezone; choose one convention across devices before use.
Templates use Obsidian's native `{{date}}`/`{{time}}` tokens, not invented historical dates.

## Hotkey baseline
// Nine reviewed bindings preserve Cut and give tabs and navigation consistent directional controls.

| Action | Binding |
| --- | --- |
| Copy current path | Ctrl + backtick |
| Toggle source | Ctrl + Shift + Enter |
| Split vertically | Alt + pipe |
| Split horizontally | Alt + minus |
| Close active tab | Mod + W |
| Previous / next tab | Alt + Mod + Left / Right |
| Back / forward | Alt + Mod + Up / Down |

Mod is Command on macOS and Control on Windows/Linux. Mod+X remains available for Cut. The proposed Z/zoom binding is not included. JSON shape and duplicate chords were checked; test the physical keys and OS/app conflicts on each device. Rootshell/tmux settings remain a separate terminal contract.

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
