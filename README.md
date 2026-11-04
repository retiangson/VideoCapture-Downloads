# VideoCapture Host downloads

## Development build 0.10.0

[Download the complete Windows x64 Host package](https://github.com/retiangson/VideoCapture-Downloads/releases/download/host-v0.10.0-dev-41846663616-1/VideoCapture-Host-0.10.0-win-x64-setup.exe) · [Release notes](https://github.com/retiangson/VideoCapture-Downloads/releases/tag/host-v0.10.0-dev-41846663616-1)

SHA-256: f603bc357498899c908246772fc5c825e2e2627556fcb80b950183602e64de3a

Run the downloaded setup EXE. It installs the complete package into Program Files, adds Start Menu/optional desktop shortcuts and registers an uninstaller. Network Mirror is the default; Direct USB/Extend drivers are optional and require explicit development-certificate trust approval. Configure per-user Windows startup, notification-area launch and saved-profile reconnection in the Host. No separate runtime download is needed.

**Development only — not a customer release.** This package uses a build-specific, self-signed development certificate. Installing requires explicit administrator and local certificate-trust approval. CI never installs drivers or trusts certificates, disables Secure Boot, or bypasses Windows signature enforcement. Each CI run uses a different development signer; this is not a supported customer update channel. Production Microsoft driver signing and paid entitlement enforcement remain pending.

The installer is downloadable during both trial and paid access. Paid features must be enforced by verified mobile-app entitlements, not by hiding downloads. This development build does not implement purchase enforcement.

Source commit: 80550c4b851e9426c4ad3cdbde36b35377fbf956 · [Build and validation logs (source repository access required)](https://github.com/retiangson/VideoCapture/actions/runs/41846663616)

This public repository contains download metadata and compiled release assets only. Private application source history is not copied here. Installers are GitHub Release assets, avoiding Git's 100-MiB file limit. Keep this downloads repository public so users can download without signing in.

Hardware playback, USB reconnect, sustained performance and pen latency need physical-device testing. A green hosted CI run does not certify those properties. Included third-party notices and corresponding-source distribution obligations still apply.
