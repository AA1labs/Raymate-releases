# RayMate — Releases

Binaries and the auto-update manifest for [RayMate](https://raymate.app), a Raycast-style AI assistant for macOS.

The application source is closed; this repository carries only the published artifacts.

## Install

Download the latest `.dmg` from [Releases](../../releases/latest) and drag RayMate to Applications.

## Updates

RayMate checks `latest.json` on this repository and updates itself. Every archive is
signed with the project's minisign key and verified before it is applied, and the app
bundle is signed and notarized by Apple.

Settings → General → Check for updates triggers a check by hand.

## Licence

The RayMate binaries are proprietary. See [LICENSE](LICENSE).
