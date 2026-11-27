> [!NOTE]
> **Legacy milestone · FORM 8.4.** This repository documents an earlier development version. For the newest public FORM development line, visit [FORM 15](https://github.com/chris101010s/FORM_10_LIVING_WORKOUT1). Do not treat this repository as the current release.

---

# FORM 8.4 — FRESH START

Bestehendes ATHLETE OS / FORM Expo-Projekt, jetzt mit leerer, eigener Datenbank, Mehrblock-Training, Backup-Center, nativen iOS-Tabs und Jahresjournal. Keine persönlichen Defaultwerte. Kein Konto.

- [Release-Report und offene Anforderungen](RELEASE_REPORT.md)
- [Windows → iPhone](BUILD_WINDOWS_TO_IPHONE.md)
- [Datenbank und Fresh Start](MIGRATION_V7_TO_V8.md)
- [Backupformat](BACKUP_FORMAT.md)
- [Testmatrix](TEST_MATRIX.md)

Lokale reine Logiktests: `npm run test:all`; vollständige Prüfung mit installierten Paketen: `npm run check`. Apple-Kryptografie: `bash scripts/test-apple-crypto.sh` auf macOS. Die neue Version ist noch nicht nativ gebaut oder auf iPhone getestet.
