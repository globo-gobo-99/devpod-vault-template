---
sensitivity: public
created: 2026-11-02
modified: "2026-11-02T22:08"
---
# Settings profile first boot

Install the reviewed settings without nesting or overwriting an existing profile accidentally.

1. Connect this starter vault to your intended existing remote vault. Each device has its own Sync settings.
2. If hidden profile files do not arrive, temporarily transfer copies of the five JSON files in a visible `gobsidian` folder. On the receiver enable **Settings → Sync → Selective sync → Sync all other types**, restart, and wait for every JSON file. A README arriving alone does not prove the JSON files downloaded.
3. Close Obsidian. If `.gobsidian` does not exist, rename the local visible folder. If it already exists, back up the current five settings files outside the vault and copy the starter JSON files directly into `.gobsidian`. Do not create `.gobsidian/gobsidian/`. Preserve workspace files, appearance preferences and backups.
4. Select **Settings → Files and links → Override config folder → `.gobsidian`** and restart. Reconnect the existing remote vault if the new profile requires Sync setup; do not create a replacement remote.
5. Enable **Main settings**, **Hotkeys**, **Active core plugin list**, and **Core plugin settings** under Vault configuration sync. Let Sync complete, then restart.
6. Verify Daily notes uses `Sessions` and `Templates/Daily.md`, and Templates uses `Templates`. Select the actual template with the picker if a manually entered path reports file not found. Test hardware shortcuts separately.

For several devices, establish one working source first. Keep other devices paused while repairing the source. Resume the source and verify its config uploads before reconnecting another device. If remote settings are replaced with defaults or files are deleted, preserve backups and inspect the actual Sync events before restoring again. An upload receipt does not prove another device loaded the profile.

**Sync all other types** permits the visible bootstrap JSON files. **Vault configuration sync** governs the selected hidden profile; these are separate controls. Hidden source/Git files remain outside ordinary Sync rules. The visible folder is one-time transport and is not a second sync engine.

References: [Settings and profiles](https://obsidian.md/help/sync/settings), [Configuration folder](https://obsidian.md/help/configuration-folder).

## See also

- [[Wiki/Setup]]
- [[Templates/README]]
- [Vault home](../README.md)
