---
sensitivity: public
created: 2026-11-03
modified: "2026-11-03T01:30"
---
# Obsidian-Sync-Kenobi (Ob-Sk)

A shared Obsidian knowledge workspace across personal devices and cloud development computers. Obsidian Sync carries vault content; Tailscale provides private network access where configured. Each active workspace uses an independent local replica and one Sync writer.

## Supported device roles

Keep all six roles in [Devices](devices/README.md): dot-box, dev-box, dev-pod, lappy, ipad, and mobile. Physical devices and provider allocations are deployment-specific. A Codex Cloud workspace can implement the cloud-agent role with its own unique Sync device identity.

## Components

- [Tail-Net](../Tail-Net/README.md) — Network identities and access.
- [Dev-Pod](../Dev-Pod/README.md) — Development pod operations.
- [Run-Pod](../Run-Pod/README.md) — Hosting and inference topics.
- [Models](../Models/README.md) — Model catalog.
- [Agentic-Roles](../Agentic-Roles/README.md) — Responsibilities and maintenance.
- [Sessions](../Sessions/README.md) — Work receipts and dated journals.

## Repositories

Record the deployment's infrastructure, agent-tooling, reusable-template, and private-vault repositories here. Keep personal repository bindings in the private vault.

## Onboarding outline

Prepare a private vault from this template, assign device roles, configure each service's authentication, connect independent replicas to the existing remote vault, and verify a small round trip. This outline is a design goal, not an installed onboarding automation.
