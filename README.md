# Scruto Releases

Signed and notarized macOS builds of [Scruto](https://scruto.app) — a desktop app for analyzing, browsing, and searching video and photo libraries.

**Source code is private.** Download the latest build from [scruto.app](https://scruto.app) or the [Releases](https://github.com/Auuufff/scruto-releases/releases) tab here.

## Integrity

Every DMG is:

- Code-signed with Apple Developer ID
- Notarized by Apple
- Stapled for offline Gatekeeper validation

You can verify any download with:

```shell
xcrun stapler validate Scruto-*.dmg
spctl --assess --type open --context context:primary-signature Scruto-*.dmg
```

Both commands should report success on an unmodified download.

## Support

Questions, bugs, feature requests: hello@scruto.app
