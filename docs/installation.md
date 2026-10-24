# Install Skeleton Writer

The v0.1.0 preview targets Windows 11 on x64 PCs. Use a writable local NTFS folder for stories; new-file creation requires hard-link support.

## Download

Open the [v0.1.0 release](https://github.com/brandflowr/Skeleton-Writer/releases/tag/v0.1.0) and choose one:

- **Skeleton_0.1.0_x64-setup.exe** — setup executable, the primary download.
- **Skeleton_0.1.0_x64_en-US.msi** — alternative Windows Installer package.

Do not download GitHub's automatically generated source-code ZIP/TAR as the application installer. Those archives contain this repository's documentation.

Run the chosen installer, then launch **Skeleton** from the installed shortcut. Select a folder you own and follow the [quick start](quick-start.md). Microsoft Edge WebView2 is required; installation may require internet access to download it. Node.js and Rust are not required to run the desktop app. The optional assistant kit's standalone validator requires Node.js 22+.

## Unsigned preview

Both installers are unsigned. Windows may show an unknown-publisher or SmartScreen warning, and some managed PCs or security configurations may block installation. Use your organization's approved installation process where applicable. Code signing is pending.

## Verify the download

Download `SHA256SUMS.txt` from the same release. In PowerShell, run this in your Downloads folder, substituting the MSI filename if needed:

```powershell
Get-FileHash -LiteralPath './Skeleton_0.1.0_x64-setup.exe' -Algorithm SHA256
```

Compare the result with the matching filename in `SHA256SUMS.txt`. A matching checksum confirms that the bytes match the published release; it is not a publisher signature.

## Updates and existing work

Updates are manual. Check this repository's Releases page for later versions and read their notes. Back up your story folder before trying this preview or changing installed versions. Standard-user clean installation, missing-WebView2 handling, upgrades, and uninstall preservation have not yet completed acceptance testing for these exact installers. See [preview limitations](preview-limitations.md).
