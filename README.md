# StreamCraft Releases

Public download mirror for **StreamCraft** — real-time **webcam, screen share, and voice** in
Minecraft, rendered on in-world blocks via LiveKit WebRTC. Talk to nearby players, watch shared
screens together, and stream your camera above your head.

- 🌐 **Website:** https://streamcraft.live
- 📦 **Modrinth:** https://modrinth.com/mod/streamcraft-live
- 🟠 **CurseForge:** https://www.curseforge.com/minecraft/mc-mods/streamcraft-live
- 📥 **GitHub Releases (this repo):** https://github.com/slashdaemon/StreamCraft-Releases/releases

The source repo is private; this repo mirrors the release artifacts so anyone can download builds
directly without a launcher.

## Where to get it

| Channel | Best for |
|---------|----------|
| [Modrinth](https://modrinth.com/mod/streamcraft-live) | Prism / launcher install with auto-update (Fabric + Quilt + NeoForge) |
| [CurseForge](https://www.curseforge.com/minecraft/mc-mods/streamcraft-live) | CurseForge App |
| [GitHub Releases](https://github.com/slashdaemon/StreamCraft-Releases/releases) | Manual install / pinning a specific build |

## Supported Minecraft versions

- **Fabric** (also loads under **Quilt**): 1.20.1, 1.20.5, 1.21.1, 1.21.2, 1.21.4, 1.21.6, 1.21.9,
  1.21.11, **26.1.x**, and **26.2** (Vulkan line).
- **NeoForge:** 1.20.6, 1.21.1, 1.21.2/1.21.3, 1.21.4, 1.21.6/1.21.8, 1.21.9/1.21.10, 1.21.11,
  **26.1.x**, and **26.2** (beta — NeoForge 26.2 is still beta upstream).

> **Multiplayer only.** StreamCraft must be installed on **both the client and the dedicated
> server**, and both must run the **same version**.

## Which file do I download?

Each release attaches one JAR per (Minecraft version × loader × platform). Pick the file matching
your Minecraft version and loader, then your OS:

| Your OS | File suffix |
|---------|-------------|
| **Windows** | *(no suffix)* — e.g. `streamcraft-<ver>+mc1.21.1.jar` |
| **Linux (x86_64)** | `…-linux.jar` |
| **Linux (ARM64)** | `…-linux-aarch64.jar` |
| **macOS (Apple Silicon)** | `…-macos-arm64.jar` |
| **macOS (Intel)** | `…-macos-x86_64.jar` |

NeoForge users: pick the file with `-neoforge` in the name. The Windows variant is the default
download (no platform suffix); the Mac/Linux variants bundle the platform-specific native capture
stack.

## What's in a release

**96 JARs** per release — 19 (Minecraft band × loader) combinations × 5 platforms, plus one extra:

- 10 Fabric bands (1.20.1 → 26.2) + 9 NeoForge bands (1.20.6 → 26.2)
- × 5 platforms each: `windows`, `linux`, `linux-aarch64`, `macos-arm64`, `macos-x86_64`
- plus an `-android-aarch64` variant of the 26.1 Fabric band (for the TBS Android launcher)

## License & terms

StreamCraft is proprietary. The mod is free and fully usable; an optional paid hosted service
(see [streamcraft.live](https://streamcraft.live)) covers the real-time relay infrastructure. Use
is governed by the published terms:

- **Terms of Service:** https://streamcraft.live/terms
- **Privacy Policy:** https://streamcraft.live/privacy
- **Acceptable Use Policy:** https://streamcraft.live/acceptable-use
