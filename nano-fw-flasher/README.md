# NANO RTK Flasher

Windows amd64 portable firmware utility.

- [Download v0.0.7](https://github.com/datagnss/app-releases/releases/download/goesp32-v0.0.7/nano-rtk-flasher-v0.0.7-windows-amd64.zip)
- [Stable update catalog](windows-amd64/stable/releases.json)
- [Release history](https://github.com/datagnss/app-releases/releases?q=goesp32-)

Packages and signed manifests are GitHub Release assets. Stable and version catalogs are kept here; ZIP files never enter Git history. Keep historical versions immutable. The program validates the existing goESP32 Ed25519 identity, signed size/SHA-256, and archive contents before installation.

v0.0.1 continues to use its existing docs.datagnss.com address. A same-origin v0.0.2 migration package remains there so that the old updater can transition to this channel. The release identity is unchanged. The Windows amd64 NSGo GUI is delivered; device firmware and CLI are separate.

The canonical remote application directory is `nano-fw-flasher/`. The previous `goesp32/windows-amd64/stable/releases.json` remains a synchronized compatibility channel for installed v0.0.2 clients. New v0.0.4 builds use this new directory. Historical release assets and the `goesp32-` tag prefix are unchanged.

The earlier `nano_fw_flasher/windows-amd64/stable/releases.json` is also retained as a compatibility mirror for installed v0.0.3 clients. The canonical directory uses hyphens: `nano-fw-flasher/`.

Extract and run `nano-rtk-flasher.exe`. Version v0.0.7 uses only the new nano-rtk-flasher asset names; old goESP32 updaters require a manual download.

Mac ARM64 test bundle: [v0.0.7 .app ZIP](https://github.com/datagnss/app-releases/releases/download/goesp32-v0.0.7/nano-rtk-flasher-macos_arm64-app-2abeaec.zip). Includes the application icon; no Developer ID signing or notarization, and Mac runtime/hardware remains unverified.
