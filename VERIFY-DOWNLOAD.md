# Verify the Windows Download

You can verify the downloaded installer with Windows PowerShell. Open PowerShell in the folder containing the installer and run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\SME-Finder-Setup-0.1.0-rc1.exe'
```

The reported SHA-256 value must exactly match:

```text
033692af0a53ee2c9fdc0f8292db95cae4714c6b3b50a3d531f6b492028a796f
```

Also compare it with the value in `SHA256SUMS.txt` supplied with the release. Do not run the installer if the values differ.
