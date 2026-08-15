# Verify the Windows Download

You can verify the downloaded installer with Windows PowerShell. Open PowerShell in the folder containing the installer and run:

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\SME-Finder-Setup-0.1.0-rc3.exe'
```

The reported SHA-256 value must exactly match:

```text
72840f67f8d046d3f6dedb9118a41dd936bb2e96769f376a7115abe287ec799c
```

Also compare it with the value in `SHA256SUMS.txt` supplied with the release. Do not run the installer if the values differ.
