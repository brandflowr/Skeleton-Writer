# v0.1.0 preview limitations

This is an early, unsigned Windows x64 preview. Keep backups of important work.

- Initial target: Windows 11 x64. Windows 10, Windows ARM64, macOS, and Linux have not been accepted for this release.
- Clean-machine and standard-user installation, missing-WebView2 behavior, upgrades, and uninstall preservation remain unverified for the exact published installers.
- Historical developer and native-app checks do not establish a complete installed-user journey for these installer bytes. The exact source revision that produced these existing installers has not been established.
- New-file creation requires a filesystem supporting hard links, such as NTFS. Other destinations are not accepted for this preview.
- Autosave and recovery checkpoints are local recovery tools, not remote backups. Edits after the last completed checkpoint may not be recoverable.
- DOCX, basic FDX, and PDF exports support limited subsets. Dual dialogue is sequential in these formats; professional revision/page locking and full external-editor round trips are not established. Read the export preview before relying on interchange.
- Genlock transfer and revision workflows still need end-to-end production acceptance. File validation alone does not prove a completed production transfer.
- Native accessibility, spellcheck/custom dictionary, and longer human writing trials remain incomplete.
- Automatic app updates are not configured; obtain later installers from Releases.

The application and installer display name is **Skeleton**. This download repository uses the name **Skeleton Writer**.

Report reproducible problems in [Issues](https://github.com/brandflowr/Skeleton-Writer/issues), with private story content removed.
