# VideoCapture Host downloads

## Development build 0.7.1

[Download the complete Windows x64 Host package](https://github.com/retiangson/VideoCapture-Downloads/releases/download/host-v0.7.1-dev-41787523509-1/VideoCapture-Host-0.7.1-win-x64-development.zip) · [Release notes](https://github.com/retiangson/VideoCapture-Downloads/releases/tag/host-v0.7.1-dev-41787523509-1)

SHA-256: 3054fd11ac647d5927be5e02d0bb5c7534c005acbde4aad78d4bee30e066c288

Extract the entire ZIP and keep all bundled files and licenses together. For **Mirror over Wi-Fi / LAN**, run VideoCapture.MonitorHost.exe directly and select Mirror; no VideoCapture driver or certificate installation is needed. Windows can still warn about or block the development-signed executable. For **Extend desktop or Direct USB**, run VideoCapture.MonitorSetup.exe and explicitly approve the development driver/certificate setup. The EXE alone is not the complete package.

**Development only — not a customer release.** This package uses a build-specific, self-signed development certificate. Installing requires explicit administrator and local certificate-trust approval. CI never installs drivers or trusts certificates, disables Secure Boot, or bypasses Windows signature enforcement. Each CI run uses a different development signer; this is not a supported customer update channel. Production Microsoft driver signing and paid entitlement enforcement remain pending.

The installer is downloadable during both trial and paid access. Paid features must be enforced by verified mobile-app entitlements, not by hiding downloads. This development build does not implement purchase enforcement.

Source commit: 971c43304ef7cbc5158438fa9bec3e8c64f7116f · [Build and validation logs (source repository access required)](https://github.com/retiangson/VideoCapture/actions/runs/41787523509)

This public repository contains download metadata and compiled release assets only. Private application source history is not copied here. Installers are GitHub Release assets, avoiding Git's 100-MiB file limit. Keep this downloads repository public so users can download without signing in.

Hardware playback, USB reconnect, sustained performance and pen latency need physical-device testing. A green hosted CI run does not certify those properties. Included third-party notices and corresponding-source distribution obligations still apply.
