# PRYSM releases

Signed APK releases for [PRYSM](https://github.com/issac-xt/prysm).

Download the latest from the [Releases page](https://github.com/issac-xt/prysm-releases/releases/latest),
install it, and follow the setup wizard — PRYSM downloads, patches and installs the target apps
itself. No root required.

PRYSM checks this repository hourly for new versions and offers to update itself.

## Notes

- Releases are tagged `v<versionName>`; the update check compares that tag against the installed
  version, so the tag format is load-bearing.
- Each release carries exactly one `.apk` asset.
- Source lives in a separate (private) repository; this one exists so an unauthenticated client can
  read `/releases/latest`.
