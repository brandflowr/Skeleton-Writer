# Skeleton Writer

**Skeleton Writer is a desktop writing app designed for the [SKEL file format](https://github.com/brandflowr/openSkeleton).** Write prose and screenplays, organize your story, and save it as a structured `.skel` project.

**[Download for Windows x64 — v0.1.0 preview](https://github.com/brandflowr/Skeleton-Writer/releases/download/v0.1.0/Skeleton_0.1.0_x64-setup.exe)** · [All downloads and release notes](https://github.com/brandflowr/Skeleton-Writer/releases/tag/v0.1.0)

This preview is available free of charge. This repository contains downloads and user documentation; the desktop application source is maintained separately. The openSkeleton specification has its own repository and license.

> **Unsigned preview:** These installers are not yet code-signed. Windows may show an unknown-publisher or SmartScreen warning. Some Windows security settings or managed computers may block installation. This is an early preview, not a certified final release.

## Built for the SKEL file format

**SKEL (Story Keyframe Extensible Layout)** is an open format for screenplays, storyboards, and visual narratives, defined in the [openSkeleton repository](https://github.com/brandflowr/openSkeleton). It keeps the writing and the structure of a story together in a file that people can read and software can validate.

- **`.skel`** is the native YAML authoring format: a plain-text story document.
- **`.skel.json`** is the JSON interchange form of the same data model.
- **Acts, scenes, and shots** are stored as separate collections connected by IDs, so tools can work with the relationships between story elements.

Skeleton Writer uses SKEL as its native project format. You can begin with prose or Fountain scene writing and develop the outline, characters, and locations around it; shots can stay empty while you write. Keep the `.skel` file as your full project when exporting to other writing formats.

SKEL is also the native story format of Genlock Studio and is designed for use across compatible writing, storyboard, and production tools. Writer's current Genlock workflow limitations are documented in the [preview limitations](docs/preview-limitations.md).

Explore the [format specification](https://github.com/brandflowr/openSkeleton/blob/main/spec/skel-spec.md), read an [annotated example `.skel` file](https://github.com/brandflowr/openSkeleton/blob/main/spec/example.skel), or visit [openSkeleton](https://github.com/brandflowr/openSkeleton) for schemas, reference tools, and documentation.

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
