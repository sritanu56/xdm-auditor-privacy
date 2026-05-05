# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-05-05

### Added
- Implemented a dynamic payload count badge on the extension launcher icon via `background.js`. It updates per tab based on the stored payload count and resets correctly when payloads are cleared or the tab is closed.
- Added UI expansion persistence in `popup.js`. The extension now saves the state of manually opened payload cards and nested tree branches per tab. Reopening the popup restores the expanded state for older payloads, while new payloads stack at the top.
- Integrated a new camera button feature to capture snapshots of the current audit state.

## [1.0.0] - 2026-05-[Insert Original Publish Date]

### Added
- Initial Chrome Web Store release of XDM Auditor.
- Core features including zero-configuration payload interception, active environment badge, multi-dimensional search, and smart CSV export.
- Light and Dark mode UI implementations.
