# StreamCraft Releases

Public download mirror for [StreamCraft](https://modrinth.com/mod/streamcraft-live) — a real-time video conferencing mod for Minecraft (webcam, screen share, voice rendered on in-world blocks via LiveKit WebRTC).

The source repo is private. This repo only holds release artifacts so non-collaborators can download builds directly.

## Where to get StreamCraft

- **Modrinth** (primary, auto-update via launcher): https://modrinth.com/mod/streamcraft-live
- **CurseForge** (primary, CurseForge App): _link pending review_
- **GitHub Releases** (this repo, manual install): see the [Releases](https://github.com/slashdaemon/StreamCraft-Releases/releases) tab

## What's in a release

Each release attaches up to 80 platform-specific JARs:

- 8 Fabric MC bands × 4 platforms (windows, linux, linux-aarch64 + macos)
- 6 NeoForge MC bands × 4 platforms
- 2 quarantined bands (MC 26.1, 26.2 Vulkan snapshot) × 4 platforms

The `windows` variant has no platform suffix and is the default download. Mac/Linux variants carry the platform-specific native capture stack.

## License

StreamCraft is proprietary. See the in-mod license terms.
