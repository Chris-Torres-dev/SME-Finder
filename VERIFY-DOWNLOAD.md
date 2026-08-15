# Verify the Windows Download

You can verify the downloaded installer with Windows PowerShell. Open PowerShell in the folder containing the installer and run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\SME-Finder-Setup-0.1.0-rc2.exe'
```

The reported SHA-256 value must exactly match:

```text
968a10f9c50dc9d782efdb113cbcbec5f956f89860714a3a9abf773c5c1b94c7
```

Also compare it with the value in `SHA256SUMS.txt` supplied with the release. Do not run the installer if the values differ.
