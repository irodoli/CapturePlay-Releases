# CapturePlay-Releases

Public update backend for installed CapturePlay clients.

## Purpose
- This repository is for **in-app updates only**.
- First-time installation is distributed as the full offline Setup from `https://dl.irodoli.com/` (Basic Auth protected).
- Do not use this repository as the normal first-install download page.

## Update assets
Each published CapturePlay version uses GitHub Releases and must keep the exact accepted build bytes. The release assets required by the Electron updater are:
- `CapturePlay-Setup.exe`
- `CapturePlay-Setup.exe.blockmap`
- `latest.yml`

Release notes may be attached/published alongside those assets.

## Safety
- Never rebuild, repackage, or resign an already user-accepted Setup only for publication.
- Verify SHA-256 before and after publication.
- Update checks may be automatic, but update download and installation follow the application's explicit user-consent settings.
- Recording or other protected active work must prevent update installation.

Canonical product/source/release state is maintained outside this repository under the CapturePlay project SSOT.