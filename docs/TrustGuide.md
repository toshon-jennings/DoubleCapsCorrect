# 🔐 TrustGuide – Verifying CAps v2.1.1

Thank you for downloading CAps v2.1.1. This guide shows how to confirm the integrity and authenticity of the EXE files included in this release.

---

## Included Trust Assets

| File                      | Description                                |
|---------------------------|---------------------------------------------|
| `CAps 2.1.1.exe`          | User-friendly binary                        |
| `CAps_v2.1.1.exe`         | Automation-friendly binary                  |
| `CAps 2.1.1.exe.sig`      | Digital signature (signed with GPG)         |
| `CAps_v2.1.1.exe.sig`     | Digital signature for automation EXE        |
| `Verify_Hashes_2.1.1.txt` | SHA-256 hashes for both EXEs                |

---

## Step 1: Verify the SHA-256 Hash

Use PowerShell or Command Prompt:

```powershell
Get-FileHash "CAps 2.1.1.exe" -Algorithm SHA256
Get-FileHash "CAps_v2.1.1.exe" -Algorithm SHA256

Step 2: Verify the Digital Signature
Option A: Using Kleopatra
- Import Toshon's public key (linked in README.md)
- Right-click the .sig file → Decrypt / Verify
- Kleopatra should confirm: "Signature is valid and verified"
Option B: Using GPG CLI
gpg --verify CAps 2.1.1.exe.sig CAps 2.1.1.exe
gpg --verify CAps_v2.1.1.exe.sig CAps_v2.1.1.exe


You should see a Good signature message if verification succeeds.

What This Means
- A matching hash confirms the file hasn’t been modified
- A valid signature proves the file came from Toshon and wasn’t tampered with
- Timestamping .ots files are bonus proof-of-existence—coming soon

Note
OpenTimestamp .ots files and full verification support are expected beginning with an upcoming release.
