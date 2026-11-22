# Sessions

## 2026-11-22

- Added the goESP32 Windows amd64 channel, following RTKbridge Gitea issue #40. Source commit eb67275 on codex/4-app-update; PR #5 remains open.
- Released goesp32-v0.0.2 with the existing signing identity. ZIP SHA-256 4e01d84369bff19134958880b7f2a71ca08b75a8932d4ae0a275f3245d9f19cd. Attachments published before stable/version catalogs. No binary added to Git history; other app directories preserved.
- Preserve the old same-origin docs feed and migration package for v0.0.1 clients. Client redirect/download policy tests, go test ./..., go vet ./..., Windows build and signed packaging passed. Public channel verification follows publication.
