# Verify the Windows Download

You can verify the downloaded installer with Windows PowerShell. Open PowerShell in the folder containing the installer and run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\SME-Finder-Setup-0.1.0-rc4.exe'
```

The reported SHA-256 value must exactly match:

```text
d2d158ebdcdf4f6badcfbba34ca39ecf8e7bbd27d4ddcb2662cf77c5ea516dcf
```

Also compare it with the value in `SHA256SUMS.txt` supplied with the release. Do not run the installer if the values differ.
