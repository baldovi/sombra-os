# Sombra OS

A Debian-based setup that turns a fresh machine into a ready-to-work Claude Code station in minutes.

> Status: idea / early planning. Nothing usable yet.

## Goal
One script (later, an ISO) that installs and configures:
- Claude Code, with sane defaults
- MCP servers for common work (git, files, browser)
- A simple workflow: orders in → reports out, tracked in a git "mailbox" repo
- Basic hardening (firewall, SSH keys only, unattended upgrades)

## Roadmap
- [ ] v0.1 — `install.sh` for Debian 13: Claude Code + base tools + hardening
- [ ] v0.2 — templates for CLAUDE.md, MCP config and the orders/reports mailbox
- [ ] v0.3 — restore-from-backup flow
- [ ] v1.0 — bootable ISO

## License
MIT
