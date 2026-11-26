# Sessions

## 2026-11-22

- Added the goESP32 Windows amd64 channel, following RTKbridge Gitea issue #40. Source commit eb67275 on codex/4-app-update; PR #5 remains open.
- Released goesp32-v0.0.2 with the existing signing identity. ZIP SHA-256 4e01d84369bff19134958880b7f2a71ca08b75a8932d4ae0a275f3245d9f19cd. Attachments published before stable/version catalogs. No binary added to Git history; other app directories preserved.
- Preserve the old same-origin docs feed and migration package for v0.0.1 clients. Client redirect/download policy tests, go test ./..., go vet ./..., Windows build and signed packaging passed. Public channel verification follows publication.

- Final verification: the v0.0.2 updater successfully checked and downloaded via this public stable channel and GitHub's official asset CDN. The original v0.0.1 updater implementation separately verified the old docs same-origin migration package. Both signatures, sizes, and SHA-256 match. Same release public key retained; actual runtime replacement/restart not exercised. Gitea goESP32 PR #5 remains open.

## 2026-11-22 Remote directory rename

- Jacky requested nano_fw_flasher as the canonical remote directory. Moved current metadata and historical records; retained goesp32 stable catalog/README solely for installed-client compatibility. Other apps unchanged.
- Published signed v0.0.3 from source 936b80c, with the same public key and new embedded feed. ZIP SHA-256 ef347ae03b2458a16c309c525f099eda8d4bf937e83b451586697b327503d05d. Package filenames and existing Release tag prefix preserved. Tests/vet/Windows build/signed packing passed; public old/new channel verification follows.

- Public verification passed: v0.0.3 actual client downloaded via nano_fw_flasher stable channel and validated the signature/size/SHA-256. Original v0.0.2 client code with its embedded old goesp32 endpoint and public key independently checked/downloaded v0.0.3. Both release identities match. No runtime replacement/restart was executed.

## 2026-11-22 Hyphen correction

- Jacky corrected the canonical directory to nano-fw-flasher. Moved current/history metadata there; preserved both earlier stable catalogs for installed v0.0.2/v0.0.3 clients. Other apps unchanged.
- Published signed v0.0.4 from d59ba89, same release identity. ZIP SHA-256 0ea0d8f1b92c4633291e5c4819ab272281a4a7b212c6466b9deadff52e3b0b31. Public channel checks follow publication.

- Verified public v0.0.4 download/signature/size/SHA-256 through nano-fw-flasher. Original v0.0.2 and v0.0.3 updater code independently checked/downloaded v0.0.4 through their embedded legacy channels. Same signing public key retained; runtime replacement/restart not executed.

## 2026-11-22 v0.0.5

- Jacky explicitly confirmed publishing/uploading v0.0.5 for upgrade testing. Published the previously prepared signed candidate from source 5802b72, with independent app progress beside the version and no firmware progress/status writes.
- Both public Release assets matched local bytes before publishing stable catalogs. ZIP 8,126,040 bytes, SHA-256 fd04d42c8224ffe299c36b1734a16bfef1301ba6b3104bf0aad719ce5932daed. Same release signing identity. Updated canonical and both compatibility catalogs; other apps/history unchanged.
- Windows build, native UI lifecycle/isolation checks, tests and vet passed during candidate preparation. Public client verification follows catalog publication.

- Final verification succeeded after GitHub Raw cache refresh: actual updater checked/downloaded v0.0.5 from the default canonical main URL and validated signature, length and SHA-256. Original v0.0.2/v0.0.3 updater implementations also checked/downloaded v0.0.5 via compatibility catalogs. Jacky will verify actual UI replacement/restart; no hardware accessed.

## 2026-11-23 v0.0.7
- Published verified Windows signed package and Mac ARM64 test bundle in goesp32-v0.0.7; public attachments match local candidates. Windows SHA256 93fedc2081c28dde8b22717364bae938b21458afed37dd023d3f99254ca9c13d.
- Synchronized canonical and two compatibility catalogs; retained historical releases and signing identity. Source PR9 merged to dev b5d6d0d. No hardware or real in-place restart validation.

## 2026-11-23 v0.0.8
- Published Windows signed update and Mac ARM64 test bundle from dev6c0c55c. Update notices are inline before the version, centered vertically, and hide after four seconds; old timers cannot dismiss new results.
- Public attachments match local bytes. Windows ZIP SHA256 a2afe7d2141c5561d3beede1a0bb29fce0291ed238f9bcf5a948282cb7fbf74b. Existing signing identity retained, canonical and two compatibility feeds synchronized; historical versions unchanged.

## 2026-11-26 v0.0.9

- Published the Windows x64 signed update and macOS ARM64 test bundle from goESP32 dev dc63703. Added official firmware discovery and verified download, v3.5D CLAS and PPP model labels, and prominent flash status.
- All public assets matched the local build before switching the stable catalogs. Windows ZIP is 7,957,439 bytes. SHA-256 c1ba04131adb6f5e669bf96a983717f2cf85b04ab8d001ae3dc1cf1e08088cbe. Existing signing identity retained.
