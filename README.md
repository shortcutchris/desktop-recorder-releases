# desktop-recorder-releases

Public release binaries and update metadata for Knowledge Recorder.

- `feeds/macos/appcast.xml` is the Ed25519-signed Sparkle feed. New entries are generated only
  after the matching notarized DMG has been uploaded to its GitHub release.
- Windows discovers the exact `DesktopRecorder-Setup.exe` asset through the GitHub Releases API,
  verifies its SHA-256 digest and its trusted BIK GmbH Authenticode signature before installation.
Public release binaries + release notes for Desktop Recorder. Source is private; this repo only carries downloadable builds and the version feed the app's update check reads.
