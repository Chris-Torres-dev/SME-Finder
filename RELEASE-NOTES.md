# SME Finder v0.1.0-rc2

**Release Candidate / Pre-release**

This is a pre-release build intended for controlled testing before broader distribution.

## Included in this release

- New installations use the correctly branded local SQLite filename, `sme_finder.sqlite3`.
- Existing installations that have only the legacy `smi_finder.sqlite3` filename continue to use it safely without automatic deletion, duplication, or overwrite.
- Release metadata records the exact private source commit used for the build through machine-derived provenance.
- Windows file properties report numeric file version `0.1.0.2` and product version `0.1.0-rc2`.
- PDF and other supported document/profile importing.
- Structured spreadsheet and directory importing.
- Standard Search across stored profiles.
- AI Scout for assisted discovery and comparison.
- Profile comparison using supported search and discovery workflows.
- Supported enhancement of existing profiles.
- Workspace-specific profile organization and data access.
- Profile and search-data exports.
- A per-user Windows desktop installer.

## Upgrade notes

- RC1 can be upgraded in place using the RC2 installer.
- The installer identity and Start Menu shortcut remain stable.
- Supported local configuration and existing SQLite data are preserved during upgrade and uninstall.
- RC1 remains available as a historical pre-release.

## Known limitations

- The installer is unsigned, so Windows may display a reputation or security warning.
- This is a release candidate and should be evaluated before production-wide use.
- Automatic updates are not yet implemented; install updates by downloading a newer installer.
- Live external research may be unavailable. When appropriate, AI Scout may fall back to stored evidence.
