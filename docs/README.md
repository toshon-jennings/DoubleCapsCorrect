# CAps v2.1.1 – Clipboard Auto-Correction Utility

CAps fixes clipboard typos where the first two letters are accidentally capitalized—like `"FAster"` → `"Faster"`. 
This release introduces onboarding polish, verified distribution, and a trust flow that’s friction-free.

---

## 🔧 What’s New in v2.1.1

- Refined onboarding: tooltip + fallback ReadMe.txt
- Trustable binaries: SHA-256 hashes + GPG signatures
- Maintainer identity verified via signed public key
- Docs for onboarding, trust verification, and changelog
- New icon: rebuilt for clarity, crop consistency, and transparency

---

## Included Files

| File                     | Purpose                                 |
|--------------------------|------------------------------------------|
| `CAps 2.1.1.exe`         | User-friendly executable                 |
| `CAps_v2.1.1.exe`        | Automation/scripting version             |
| `.sig` files             | GPG signatures for both EXEs             |
| `CAps_public.asc`        | Maintainer public key for verification   |
| `Verify_Hashes_2.1.1.txt`| SHA-256 hashes for integrity check       |
| `TrustGuide.txt`         | Instructions for verifying trust locally |
| `ReadMe.txt`             | Offline onboarding for ZIP users         |

All binaries were signed using the verified key:  
**Toshon Jennings** `<toshon.tech@gmail.com>`  
**Fingerprint:** `7239 D2A1 0270 A354 8EA0  CBF0 A1F8 3168 9219 73B1`

> ✨ No telemetry, logging, or internet dependency—CAps runs fully offline.

---

## 🧪 How to Verify

Follow [`TrustGuide.md`](https://github.com/toshon-jennings/DoubleCapsCorrect/blob/main/docs/TrustGuide.md) or use Kleopatra / GPG CLI to confirm:

- SHA-256 hashes match the originals
- GPG signatures confirm author identity
- Public key fingerprint matches `README.md`

---

## License

CAps is licensed under the **GNU AGPL v3**. You’re welcome to inspect, reuse, and redistribute it under its terms.

---
