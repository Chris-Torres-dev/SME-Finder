# Changelog

## v0.1.0-rc2 — Release Candidate

- Updated the default local SQLite filename to `sme_finder.sqlite3` for new installations.
- Preserved access to an existing legacy `smi_finder.sqlite3` database when the new filename is absent; neither database is automatically deleted or overwritten.
- Added machine-derived source-build provenance to release metadata.
- Added deterministic Windows file-version metadata (`0.1.0.2`) while retaining the semantic product version (`0.1.0-rc2`).
- Preserved the localhost-only launcher, installer identity, configuration behavior, and application security boundaries from RC1.

RC1 remains available as a historical pre-release. RC2 is recommended for continued controlled testing.

## v0.1.0-rc1 — Release Candidate

- Added a per-user Windows desktop installer with Start Menu integration and uninstall support.
- Added professional-profile and supporting-document imports.
- Added structured directory and spreadsheet imports.
- Added Standard Search for stored profiles.
- Added AI Scout for assisted discovery and comparison.
- Added supported profile enhancement workflows.
- Added workspace-specific data access.
- Added profile and search-data exports.
- Preserved user configuration during supported installer upgrades and uninstall.

This pre-release build is intended for controlled testing before broader distribution.
