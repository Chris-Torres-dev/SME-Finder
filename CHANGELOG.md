# Changelog

## v0.1.0-rc4 — Release Candidate

- Improved SME Finder naming consistency across the Windows desktop experience and release packaging.
- Improved backward compatibility for supported settings and existing local SQLite data.
- Preserved the installer identity, customer configuration, local data, localhost-only security boundary, and Quit behavior from RC3.
- Made no customer-data or hosted-service changes.

RC1, RC2, and RC3 remain available as historical pre-releases. RC4 is recommended for continued controlled testing.

## v0.1.0-rc3 — Release Candidate

- Added a customer-visible **Quit SME Finder** control to the Windows desktop application.
- Added an explicit confirmation step and a clear final message before the local application closes.
- Improved local application lifecycle handling so Quit stops the SME Finder localhost service and its owned processes.
- Preserved the installer identity, configuration compatibility, legacy SQLite filename compatibility, and application security boundaries from RC2.

RC1 and RC2 remain available as historical pre-releases. RC3 is recommended for continued controlled testing.

## v0.1.0-rc2 — Release Candidate

- Updated the default local SQLite filename to `sme_finder.sqlite3` for new installations.
- Preserved access to an existing legacy SQLite database when the new filename is absent; neither database is automatically deleted or overwritten.
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
