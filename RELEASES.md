# Release channels

English | [简体中文](RELEASES.zh-CN.md)

## Official sources

- [Product information](https://github.com/Superoutman/Bubboo)
- [All releases and downloads](https://github.com/Superoutman/Bubboo/releases)
- [Latest stable release](https://github.com/Superoutman/Bubboo/releases/latest)
- [Stable release metadata](https://api.github.com/repos/Superoutman/Bubboo/releases/latest)

The current stable version is **0.1.5 (build 6)** for Apple Silicon Macs running macOS 14.0 or later.

## Release conventions

- Stable tags use `v<major>.<minor>.<patch>`, such as `v0.1.3`.
- Titles contain only the product name and version. Release notes default to English and include system requirements and supported architectures.
- Installers use `Bubboo-<version>-<arch>.zip` or `.dmg`, with `arm64`, `x86_64`, or `universal` matching the actual build.
- Releases include `SHA256SUMS`. Third-party licenses and notices stay inside the app bundle; no separate notices attachment is uploaded.
- Prereleases are marked accordingly and are not designated as the latest stable release.
- Published installers are not replaced. Corrections ship as a new version.

## In-app updates

Fixed feed: https://raw.githubusercontent.com/Superoutman/Bubboo/main/appcast.xml

Bubboo uses Sparkle to check for, download, verify, and install updates. Background downloads can be installed when the app quits; clicking the green version prompt lets you update immediately. About provides controls for automatic checks and downloads.

The appcast currently offers the signed 0.1.5 update. Entries must point to published installers in this repository’s Releases and include the Sparkle EdDSA signature, build number, display version, minimum macOS version, and hardware requirements. Verify public downloads before updating the feed, and retain entries needed by older systems and architectures.

Installed clients depend on this feed URL. Do not remove or migrate it without a compatibility plan.
