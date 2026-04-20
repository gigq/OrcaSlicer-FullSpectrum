# Snapmaker Orca Full Spectrum v0.9.4.1

Patch release for the `0.9.4` line focused on versioning and release plumbing.

## Highlights

### Four-Part Version Support
- Added support for parsing `AA.BB.CC.DD` style application versions in the shared semver wrapper.
- Updated CMake version extraction so build metadata and Windows resource versions keep the `.1` patch suffix.

### Release Packaging
- Enables this fork to publish a branch-driven `v0.9.4.1` GitHub release cleanly from `main`.

## Notes

- No feature-level changes beyond the versioning/release support needed for this patch release.
- macOS builds from this fork are unsigned and not notarized.
