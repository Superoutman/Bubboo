<p align="center"><img src="assets/AppIcon.png" width="128" alt="Bubboo app icon"></p>

# Bubboo

English | [简体中文](README.zh-CN.md)

Bubboo is a polished, native macOS alternative to PopClip. Select text to reveal a customizable floating toolbar, and import compatible PopClip extensions for more actions.

## Features

- Copy, paste, and search the web.
- Import `.popclipext` / `.popclipextz` extensions, with support for selected URL, Shell, AppleScript, and JavaScript actions.
- Customize the toolbar and manage extensions in native macOS settings.
- Built-in actions show a lock instead of a delete button. The Dock icon appears while Settings is open.
- Remove installed extensions to the Trash; find new packages in PopClip's extension directory.
- English and Simplified Chinese follow your system’s preferred language. Other languages fall back to English.

## Downloads and updates

**Requires macOS 14.0 (Sonoma) or later.**

**Current version: 0.1.7 · Apple Silicon (M-series chips).**

The app is signed with Developer ID and notarized by Apple. An Intel build is not currently available.

This repository is the official source for product information, downloads, and updates. Installers are available in Releases. Click the version number in Settings to check for updates; a green prompt appears when an update is available. Automatic checks and downloads can be managed in About. The app uses this repository’s appcast for updates.

## Getting started

Extract the download, move `Bubboo.app` to Applications, and open it. Allow Bubboo in **System Settings → Privacy & Security → Accessibility**, then select text to use the toolbar.

New or modified extensions are disabled until you explicitly enable them. Script extensions can perform local operations, so only enable extensions you trust. JavaScript network access requires approval for each domain.

<a id="extensions"></a>

## Extensions

Browse and download extensions from the [official PopClip extensions directory](https://www.popclip.app/extensions/).

Download an extension package, then choose **Import Extension** in Bubboo Settings and enable it. Configure any available options there. New or changed extensions require your approval before they can run.

Bubboo supports many PopClip extensions, but compatibility depends on the extension and the target app. Some extensions use PopClip features that Bubboo does not yet support or require another app or online service. Install packages from sources you trust.

Bubboo no longer maintains a separate curated extension catalog. Bubboo and PopClip are independent products.

## Feedback

Report bugs or suggest improvements through [Issues](https://github.com/Superoutman/Bubboo/issues). Include your macOS version, Bubboo version, and steps to reproduce. Do not share selected text, passwords, or other private information.

## About this repository

This repository contains product documentation and release files. The app’s source code is maintained separately and is not public. Public visibility does not grant an open-source license to the code or brand assets.

Bubboo is an independent product and is not affiliated with PopClip. Third-party licenses and notices are included in the app bundle.

See [Release channels](RELEASES.md) for distribution details.
