DoubleCapsCorrect – CAps v2.1.1
-------------------------------

This tool automatically corrects clipboard text that starts with accidental double capitals (e.g., "FAster" → "Faster"). 
This is frequently missed by autocorrect in various applications.

✔ Corrects common double-cap errors
✔ Local-only, no data collection
✔ Clean UX with brief notification tooltip and About dialog

Privacy:
- All processing happens offline.
- No clipboard data is stored or transmitted.

Usage:
- Copy the text you'd like to fix.
- Press Win + ` (the backtick key).
- The corrected version replaces the clipboard and is pasted automatically.

First Run:
- On first launch, CAps 2.1.1 shows a brief tooltip and opens this README.
- A marker file is placed in %AppData%\CAps\ to prevent repeat onboarding.

Versioning:
- CAps 2.1.1.exe → for everyday use (clean name)
- CAps_v2.1.1.exe → for scripting/automation (no spaces)

_______________________________

🔐 TRUST & TRANSPARENCY

CAps v2.1.1 is built with privacy and consumer confidence in mind:

• Local-only operation — no network activity, no telemetry, no data collection
• Digitally signed binaries (.sig) using RSA-4096 GPG keys
• Included public key file (CAps_public.asc) for independent signature verification
• SHA-256 hashes published for both EXEs to ensure file integrity
• Fully offline, self-contained — runs directly on your system without external dependencies
• Executables run locally without installation


To verify integrity:

	1. SHA-256 hashes provided for both EXE files.
		CAps 2.1.1.exe: 91CB94D8CC10C404F20DEF0C840569BA7A1B22FB676094E8137C775CDBD4F6BE 
		CAps_v2.1.1.exe: 871C673D46FC7A9D6BA0DF0F7FC5CB7FBF70B1C4F615DB4540D5FA9F0729B37A

	
To verify authenticity:

	1. Import the public key:
  	 	gpg --import CAps_public.asc

	2. Verify the signature:
  	 	gpg --verify CAps_v2.1.1.exe.sig CAps_v2.1.1.exe

	If valid, you’ll see a message confirming a good signature from:
	
		Toshon Jennings, toshon.tech@gmail.com
	
		Public Key Fingerprint: 
		pub rsa 4096 2025-07-21 [SC] [expires: 2027-07-21]
      		7239 D2A1 0270 A354 8EA0  CBF0 A1F8 3168 9219 73B1


Confidentiality, integrity, and authenticity build trust. We deserve tools that make that visible.

_______________________________

FAQs

Q: Why does my antivirus or VirusTotal flag this EXE?
A: AutoHotkey scripts often trigger false positives due to clipboard automation. CAps v2.1.1 is fully offline, self-contained, and signed with a GPG key. All verification instructions are provided so you can confirm safety independently.

Q: Why does VirusTotal say “Not signed”?
A: CAps is signed with a GPG public key (CAps_public.asc), not a commercial Authenticode certificate. This protects open-source workflows without requiring centralized infrastructure.

Q: How can I verify the file hasn’t been tampered with?
A: Use the provided `.sig` files or compare SHA-256 hashes in README and `hashes_v2.1.1.txt`. Step-by-step commands are included above in this ReadMe.

Q: Can I use CAps on any Windows version?
A: Yes—CAps is compiled with AutoHotkey v2 and runs on Windows 10 and 11 without external dependencies.

Q: Does CAps collect or transmit any data?
A: No. CAps runs locally, processes your clipboard, and exits silently. It doesn't send, save, or log anything externally.

-------------------------------

THIS UTILITY IS PROVIDED UNDER A GNU AFFERO GENERAL PUBLIC LICENSE.


