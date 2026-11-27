# NANO RTK Flasher

Portable firmware utility for Windows x64, with macOS test bundles.

- [Windows x64 v0.0.10](https://github.com/datagnss/app-releases/releases/download/goesp32-v0.0.10/nano-rtk-flasher-v0.0.10-windows-amd64.zip)
- [Stable update catalog](windows-amd64/stable/releases.json)
- [Release history](https://github.com/datagnss/app-releases/releases?q=goesp32-)

Packages and signed manifests are GitHub Release assets. Stable and version catalogs are kept here; ZIP files never enter Git history. Keep historical versions immutable. The program validates the existing goESP32 Ed25519 identity, signed size/SHA-256, and archive contents before installation.

v0.0.1 continues to use its existing docs.datagnss.com address. A same-origin v0.0.2 migration package remains there so that the old updater can transition to this channel. The release identity is unchanged. The Windows amd64 NSGo GUI is delivered; device firmware and CLI are separate.

The canonical remote application directory is `nano-fw-flasher/`. The previous `goesp32/windows-amd64/stable/releases.json` remains a synchronized compatibility channel for installed v0.0.2 clients. New v0.0.4 builds use this new directory. Historical release assets and the `goesp32-` tag prefix are unchanged.

The earlier `nano_fw_flasher/windows-amd64/stable/releases.json` is also retained as a compatibility mirror for installed v0.0.3 clients. The canonical directory uses hyphens: `nano-fw-flasher/`.

Extract and run `nano-rtk-flasher.exe`. This version uses the nano-rtk-flasher asset names; old goESP32 updaters require a manual download.

macOS v0.0.10 test bundles: [Apple Silicon](https://github.com/datagnss/app-releases/releases/download/goesp32-v0.0.10/nano-rtk-flasher-macos_arm64-app-6cbf2bd.zip) and [Intel](https://github.com/datagnss/app-releases/releases/download/goesp32-v0.0.10/nano-rtk-flasher-macos_x64-app-6cbf2bd.zip). Mac runtime and hardware checks are pending. These bundles lack Developer ID signing and notarization.
