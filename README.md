# Morphent

**Scientific AI Research Platform** · *Annotate. Train. Discover.*

Morphent is a Windows application for scientific image segmentation: research projects,
dataset import and validation, and AI-assisted annotation of images with full-resolution
segmentation masks.

This repository contains **only** the official Morphent downloads, checksums and release notes.

## Download

Open **[Releases](../../releases)** and choose the latest version:

| File | What it is |
| --- | --- |
| `Morphent-<version>-Setup.exe` | **Installer (recommended).** No administrator rights needed. Upgrades keep your projects, settings and models. |
| `Morphent-<version>-Windows.zip` | **Portable edition.** Unzip and run `Morphent.exe`. |
| `SHA256SUMS.txt` | Checksums of the files above |

### Verify your download

In PowerShell:

```
Get-FileHash .\Morphent-<version>-Setup.exe -Algorithm SHA256
```

The result must match the line for that file in `SHA256SUMS.txt`.

### "Windows protected your PC"

Morphent isn't code-signed yet, so Windows SmartScreen may show this message. Click
**More info → Run anyway** only if you downloaded the file from this page and the checksum
matches. Please don't disable Windows security features.

## Uninstall

Windows **Settings → Apps → Installed apps → Morphent → Uninstall**. Your research projects,
settings and downloaded models are kept.

## Privacy

Morphent works offline and doesn't collect telemetry. Cloud storage (e.g. Google Drive) is used only
when you connect your own account; sign-ins are kept in memory and never saved.

## Updates

Morphent can check for new versions (optional, can be turned off). Updates are never installed
without your approval, and every download is verified against signed release information.

---
Morphent is proprietary software. Licence terms are provided with each release.
