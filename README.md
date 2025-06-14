# 🔐 KeepSafe – APK Releases Repository

Welcome to the **official public repository** for APK releases, issue tracking, and release documentation of the **KeepSafe Android App**.

---

## 🚀 About KeepSafe

**KeepSafe** is a privacy-first personal organizer that helps users securely manage:

- 📝 Personal Notes (Private + Public)
- 🔐 Passwords (with `@Private` marker-based encryption)
- 🐞 Feedback submission with screenshots
- 🔄 Offline data + Cloud Sync (Firebase & Azure – in progress)

It ensures security with:
- 🔐 **Firebase Authentication**
- ☁️ Firestore + Firebase Storage
- 🛡️ Encrypted local storage
- 🔁 Sync and restore capability (on reinstall or new device)

---

## ✅ Current Features (Beta v0.1.1)

- 🔐 Firebase Login/Signup (with email verification)
- 🔑 Password Manager (detects `@Private`)
- 🧭 Navigation Drawer + Bottom Navigation UI
- 🧾 Runtime permissions: Call log, SMS, Notifications, Storage
- 🐞 In-app bug reporting with screenshot upload
- 🌙 Light/Dark theme support
- 💾 Offline-first Room DB syncing with Firestore
- 🔄 Manual and auto cloud sync (notes + passwords)

---

## 📲 APK Downloads

| Version | Download | Release Notes |
|---------|----------|----------------|
| ✅ Latest (v0.1.1) | [🔗 Download APK]([https://github.com/omkara96/KeepSafe-Releases/raw/refs/heads/main/KeepSafe_V0.0.2.apk]) | Bug fixes, Screenshot uploads, Sync improvements |

📌 **Install Instructions**
- Enable `Install Unknown Apps` from settings.
- Uninstall previous version before installing new one.

---

## 🔔 In-App Update Checker

- App checks `version.json` hosted in this repo to determine if a newer APK is available.
- If a newer version is available:
  - 🔄 You’ll see a **popup at app launch**
  - 📲 Tap "Download" to update via GitHub
- A “Check for Updates” option is available in the Navigation Drawer

[Version Check JSON File](https://raw.githubusercontent.com/omkara96/KeepSafe-Releases/main/version.json)

---

## 🐞 Known Bugs

| ID | Description | Status |
|----|-------------|--------|
| B-101 | Crash: `screenshotUrl` type mismatch | ✅ Fixed |
| B-102 | Spinner warning dialog prompt missing | ✅ Fixed |
| B-103 | Private passwords appearing in public list | 🔄 In Progress |
| B-104 | Bottom nav highlight not resetting | 🧪 Investigating |
| B-105 | No error shown for screenshot upload failure | 🕐 Pending |

---

## 🧭 Roadmap (v0.2+)

- ✅ Replace quick buttons with BottomNavigationView
- 🛠️ CreateNoteActivity + animations
- 📝 Public/Private Notes support
- 🔄 Restore from Cloud (manual + auto)
- ☁️ Azure SQL + Firestore syncing (for passwords)
- 🔔 Firebase Cloud Messaging for notifications
- 🧮 Compare cloud vs local data counts
- 🕵️ Background logging (calls, SMS, app usage)
- 🧪 Search across notes/passwords
- 🎨 UI enhancements and polish
- 📊 Admin-only bug report dashboard

---

## 📆 Release Timeline

| Version | Status | Highlights |
|---------|--------|------------|
| v0.1.0 | ✅ Released | Core UI, Firebase Auth/Firestore |
| v0.1.1 | ✅ Released | Screenshot uploads, update checker |
| v0.2.0 | 🏗️ In Progress | Bottom nav, restore data, Azure sync |

---

## 📣 Report Bugs or Suggest Features

- ✅ Use in-app “Report Issue” screen with screenshot support
- 🐞 Or open a GitHub [Issue here](https://github.com/omkara96/KeepSafe-Releases/issues)

Please include:
- Steps to reproduce
- Screenshots/logs
- App version + device details

---

## 🔐 Privacy Notice

- 🔐 Firebase Auth is used for user identity
- 📁 Screenshots stored in Firebase Storage (secure path)
- 🔒 Local data is encrypted
- ❌ No private data is shared publicly

---

## 🤝 Contributing

This repository is primarily for:
- 🧪 Distributing APKs
- 🐞 Public bug tracking
- 📢 Discussing upcoming features

Feel free to open issues or submit feedback.

---

## 🛡️ License

MIT License © 2025 [Omkara Varma](https://github.com/omkara96)

---

