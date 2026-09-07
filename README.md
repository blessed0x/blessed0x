# Blessed0x · `0x` — ship the bytes

iOS reverse engineering & tooling, written in pure Go.
One static binary walks into any machine — no Python env, no drama.

## Focus

- **iOS reverse engineering** — Mach-O internals, dylib injection, IPA tweaking & sideloading
- **Apple device protocols** — usbmuxd / lockdownd clients and developer tunnels, all in Go
- **macOS internals** — launchd, service debloating, single-binary CLI tooling
- **Model Context Protocol** — headless runtimes that give AI agents real tools

## Arsenal

| tool | what it does |
|---|---|
| [xkvm-ios-injector](https://github.com/blessed0x/xkvm-ios-injector) | inject tweaks & dylibs into IPA files — byte-faithful, pure Go |
| [idev](https://github.com/blessed0x/idev) | your iPhone/iPad from the terminal: pair, install, launch, stream logs, screenshots, port-forward |
| [macos-debloater](https://github.com/blessed0x/macos-debloater) | disable the macOS services you don't use — mode 1–4, TUI, or manual pick |
| [scratch-unified-mcp](https://github.com/blessed0x/scratch-unified-mcp) | headless Scratch VM over MCP — 108 tools for AI agents to build & playtest |

## Elsewhere

- site → [blessed0x.github.io](https://blessed0x.github.io/)
- building in public: bytes, binaries, and the machines that run them
