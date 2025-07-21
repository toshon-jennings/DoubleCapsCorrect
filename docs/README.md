
---

## 📘 `README.md` – Top-Level GitHub Version

```markdown
# CAps v2.1.1 – DoubleCapsCorrect Utility

CAps corrects clipboard typos where the first two letters are accidentally capitalized—like `"FAster"` → `"Faster"`. Many apps miss this glitch; CAps fixes it instantly with a single shortcut.

---

## ✨ Features

- ✔ Fixes leading double-cap typos in clipboard text  
- ✔ Runs offline — no telemetry, logging, or data collection  
- ✔ Subtle UX feedback via tooltip and About dialog  
- ✔ Works on Windows 10 & 11 — no installation required

---

## 📐 How to Use

1. Copy the text you'd like to fix  
2. Press `Win + \`` (backtick key)  
3. CAps replaces the clipboard and pastes the corrected text automatically

---

## 🚀 Onboarding Experience

- First run shows a tooltip + opens [`ReadMe.txt`](./dist/ReadMe.txt)  
- A marker file is saved to `%AppData%\CAps\` to prevent repeat onboarding

---

## 🔐 Trust & Verification

CAps v2.1.1 is packaged with integrity and transparency:

- SHA-256 hashes listed in [`Verify_Hashes.txt`](./dist/Verify_Hashes.txt)  
- Digitally signed binaries using [GPG (GNU Privacy Guard)](https://gnupg.org/)  
- Public key: [`CAps_public.asc`](./dist/CAps_public.asc)  
- Step-by-step verification instructions in [`TrustGuide.md`](./docs/TrustGuide.md)

> ℹ️ `.ots` timestamp files are included for future blockchain-based proof-of-existence. Verification support is planned for v2.2+

---

## 🔧 Versioning

| File Name            | Purpose                    |
|----------------------|----------------------------|
| `CAps 2.1.1.exe`      | User-friendly executable   |
| `CAps_v2.1.1.exe`     | Automation/scripting version  
| `.sig` files          | Digital GPG signatures  
| `.asc` file           | Public key for verification  
| `.ots` files          | OpenTimestamp artifacts *(optional for now)*

---

## ❓ Frequently Asked Questions

**Why does my antivirus flag this EXE?**  
AutoHotkey utilities may trigger false positives due to clipboard automation. CAps runs locally and is digitally signed for verification.

**Why does VirusTotal say “Not signed”?**  
CAps uses [GPG signatures](https://gnupg.org) for open-source trust, not commercial Authenticode certificates.

**Can I verify the EXE hasn’t been modified?**  
Yes — follow [`TrustGuide.md`](./docs/TrustGuide.md) or use the provided `.sig` files and hash checks.

**Does CAps send or store data?**  
No. All clipboard processing happens entirely offline and leaves no trace.

---

## 📫 Feedback & Contributions

Found a bug or want to suggest a feature?  
Open an issue at [github.com/toshon-jennings/DoubleCapsCorrect/issues](https://github.com/toshon-jennings/DoubleCapsCorrect/issues)  
Or email: [toshon.tech@gmail.com](mailto:toshon.tech@gmail.com)

---

## 📄 License

CAps is licensed under the **GNU Affero General Public License v3**.  
You're welcome to use, modify, and redistribute it under the terms of that license.

---