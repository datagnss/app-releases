# Sessions

## 2026-11-22

- Added the goESP32 Windows amd64 channel, following RTKbridge Gitea issue #40. Source commit eb67275 on codex/4-app-update; PR #5 remains open.
- Released goesp32-v0.0.2 with the existing signing identity. ZIP SHA-256 4e01d84369bff19134958880b7f2a71ca08b75a8932d4ae0a275f3245d9f19cd. Attachments published before stable/version catalogs. No binary added to Git history; other app directories preserved.
- Preserve the old same-origin docs feed and migration package for v0.0.1 clients. Client redirect/download policy tests, go test ./..., go vet ./..., Windows build and signed packaging passed. Public channel verification follows publication.

- Final verification: the v0.0.2 updater successfully checked and downloaded via this public stable channel and GitHub's official asset CDN. The original v0.0.1 updater implementation separately verified the old docs same-origin migration package. Both signatures, sizes, and SHA-256 match. Same release public key retained; actual runtime replacement/restart not exercised. Gitea goESP32 PR #5 remains open.

## 2026-11-22 Remote directory rename

- Jacky requested nano_fw_flasher as the canonical remote directory. Moved current metadata and historical records; retained goesp32 stable catalog/README solely for installed-client compatibility. Other apps unchanged.
- Published signed v0.0.3 from source 936b80c, with the same public key and new embedded feed. ZIP SHA-256 ef347ae03b2458a16c309c525f099eda8d4bf937e83b451586697b327503d05d. Package filenames and existing Release tag prefix preserved. Tests/vet/Windows build/signed packing passed; public old/new channel verification follows.
