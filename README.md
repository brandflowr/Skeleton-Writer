# Skeleton Writer

A desktop writing app for prose, screenplays, and structured stories in the [openSkeleton format](https://github.com/brandflowr/openSkeleton).

**[Download for Windows x64 — v0.1.0 preview](https://github.com/brandflowr/Skeleton-Writer/releases/download/v0.1.0/Skeleton_0.1.0_x64-setup.exe)** · [All downloads and release notes](https://github.com/brandflowr/Skeleton-Writer/releases/tag/v0.1.0)

This preview is available free of charge. This repository contains downloads and user documentation; the desktop application source is maintained separately. The openSkeleton specification has its own repository and license.

> **Unsigned preview:** These installers are not yet code-signed. Windows may show an unknown-publisher or SmartScreen warning. Some Windows security settings or managed computers may block installation. This is an early preview, not a certified final release.

## Get started

1. Download and run the setup EXE above. An MSI alternative is available in the release; choose one installer.
2. Launch **Skeleton** and select a local folder you own. Use an NTFS folder for new stories.
3. Choose **New story**, start writing, and save with **Ctrl+S**.

Initial preview target: **Windows 11 x64**, with Microsoft Edge WebView2. The installer may need internet access to obtain WebView2. The desktop app does not require Node.js or Rust. Windows 10, Windows ARM64, macOS, and Linux are not validated targets for this preview.

## Writing tools

- Write prose and Fountain screenplays; organize scenes in Outline.
- Maintain characters and locations in Bible, and story threads in Map.
- Save SKEL documents locally, with autosave, snapshots, and recovery tools.
- Import and export supported story formats; review each export's limitations.
- Export an optional assistant kit for use with an external AI assistant.

Core writing uses local files. Genlock and an AI assistant are optional. Marketplace refreshes use the public Genlock registry; installed items can be used offline. Sharing a draft with an external assistant is a separate action.

## Documentation and support

- [Installation and download verification](docs/installation.md)
- [Quick start](docs/quick-start.md)
- [Preview limitations](docs/preview-limitations.md)
- [Report a problem](https://github.com/brandflowr/Skeleton-Writer/issues)
- [openSkeleton specification](https://github.com/brandflowr/openSkeleton)

When reporting a problem, include the app version, Windows version, reproduction steps, and expected/actual behavior. Issues are public: remove private manuscript content and credentials from examples.
