# DoubleCApsCorrect
**Version 2.1**
A background executable for keyboard perfectionists.
  
Created by Toshon | Powered by AutoHotkey v2  

---

## What It Does
Fixes common double-capital typing errors across any app. For example:  
`THis` → `This`  
`FAster` → `Faster`  
Runs silently and instantly when activated via hotkey.

---

<details>
<summary>Activation & Usage</summary>

**Hotkey:** `Windows Key + \`` (Win + backtick)  
Type in any app (Notepad, Word, etc.), then press the hotkey to clean up text.  

Some apps may block simulated input — see Compatibility below.

</details>

---

<details>
<summary>Installation Instructions</summary>

1. Download `DoubleCapsCorrect.exe`  
2. Save it anywhere (e.g. Desktop)  
3. Double-click to run — look for the “DoubleCapsCorrect” logo or green “H” in the tray  
4. To auto-launch at startup:
   - Open File Explorer  
   - Type `shell:startup` in the address bar  
   - Place a shortcut to the `.exe` there

</details>

---

<details>
<summary>How It Works Behind the Scenes</summary>

- Selects all text in the current window (`Ctrl + A`)  
- Copies it to the clipboard (`Ctrl + C`)  
- Applies smart regex to fix doubled uppercase patterns  
- Pastes the cleaned text back (`Ctrl + V`)  

</details>

---

<details>
<summary>Compatibility</summary>

**✅ Works In:**
- Notepad, WordPad, Microsoft Word, LibreOffice Writer  
- Outlook, Obsidian, Craft, browser address bar

**❌ May Not Work In:**
- Web-based chat apps (Copilot, Discord, etc.)  
- Some email websites  
- OpenOffice Writer

</details>

---

<details>
<summary>Customization</summary>

Want a different hotkey or rule set?  
Edit the script with [AutoHotkey v2](https://www.autohotkey.com/) or contact Toshon at `toshon.tech@gmail.com`.

</details>

---

<details>
<summary>Verifying the File</summary>

You can verify this tool’s authenticity using a digital signature.

**Files Provided:**
- `DoubleCapsCorrect.exe`
- `DoubleCapsCorrect.sig`
- `Toshon_GPG_PublicKey.asc`

**Verify with:**

```bash
gpg --import Toshon_GPG_PublicKey.asc
gpg --verify DoubleCapsCorrect.sig DoubleCapsCorrect.exe
```
```
SHA256: 137d4c250f11b2415cb660cfeb8ce440f5341292f29640b09ec833af60740181
```

**VirusTotal File Scan Report:** https://www.virustotal.com/gui/file-analysis/ZmMzYzFmMTE3OTQ0MTFiODdiZTkzMThhYWRlOTc1YTE6MTc1Mjk0MzIzMQ==

