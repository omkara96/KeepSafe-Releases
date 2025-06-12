# KeepSafe-Releases
KeepSafe Android Application Releases APK files, Release Notes and Documentation
# 📱 KeepSafe – Public Version

Welcome to the official **public repository** for the **KeepSafe Android App**.

Here you can:
- 📥 Download the latest APK builds
- 🧪 Help test new features
- 🐞 Report bugs or issues
- 🌟 Suggest improvements
- 🧭 Track progress of upcoming releases

---

## 🔐 What is KeepSafe?

**KeepSafe** is a personal security and privacy-focused Android app that helps you manage:
- Personal Notes
- Passwords (with private mode): Store your passwords securely
- Bug reporting and feedback submission

It securely stores data using:
- ☁️ Firebase Auth, Firestore, and Storage
- 🛡️ Encrypted fields for private data
- 🧠 Smart cloud sync and restore --In Progress

---

## ✅ Current Features (Beta v0.0.1)

- 🔐 **Login/Signup** using Firebase Authentication
- 🔑 **Password Manager** (comment-based `@Private` detection)
- 🧭 Navigation Drawer + Bottom Navigation
- 🧾 Runtime permission handling (Read Storage)
- 🛠️ **Bug Reporting**: Raise feature requests, bugs or suggestions with screenshot upload
- 🔄 Offline storage and auto-sync when online

---

## 🐞 Known Bugs & Issues

| ID | Bug Description | Status |
|----|------------------|--------|
| B-101 | Crash on loading issue reports due to wrong type cast for `screenshotUrl` | ✅ Fixed |
| B-102 | Prompt warning in spinner XML | ✅ Fixed |
| B-103 | Some private passwords showing in public list | 🔄 In progress |
| B-104 | Bottom nav button highlight does not reset properly | 🧪 Investigating |
| B-105 | No alert for failed screenshot uploads | 🕐 Pending |

---

## 🔜 Planned for Next Releases (v0.2+)

- ✅ Replace quick buttons with Bottom NavigationView
- 📝 **Notes** with public and private mode (Cypher protected)
- 📂 **Restore from Cloud**: Button to import data after reinstall
- 🚀 Manual Sync with Firebase and Azure (for passwords)
- 🧮 **Notes/Passwords count check** vs Firebase
- 🌐 Sync log activities (app usage, calls, notifications) to Firebase
- 🔔 **Firebase Cloud Messaging** integration
- 🧪 **Search Functionality** for both notes and passwords
- 🎨 UI Enhancements: Animations, transitions, and UX polish
- 📊 Developer dashboard to track user reports (admin-only)

---

## 📥 Download APKs

- Visit the [Releases](https://github.com/YOUR_USERNAME/keepsafe-apk/releases) tab to download the latest APKs.
- 📌 Make sure to enable `Install Unknown Apps` on your Android device.
- 💡 Testers: Always uninstall older versions before installing fresh.

---

## 🗣️ How to Report Bugs or Suggest Features

1. Use the in-app **Report Issue** feature (preferred).
2. Or open an [Issue on GitHub]([https://github.com/YOUR_USERNAME/keepsafe-apk/issues](https://github.com/omkara96/KeepSafe-Releases/issues)).
3. Include:
   - Steps to reproduce
   - Screenshots (if any)
   - App version and device details

---

## 🔒 Data & Privacy Notice

- Your account and data are protected via **Firebase Authentication**.
- All private content is **encrypted locally** and not shared.
- Media & screenshots are uploaded securely to **Firebase Storage**.

---

## 📆 Release Timeline

| Version | Status | Key Additions |
|---------|--------|---------------|
| v0.1.0  | ✅ Released | Core UI, Firebase Firestore, Firebase Auth |
| v0.1.1  | ✅ Released | Bug fixes, Screenshot uploads, Cloud Sync |
| v0.2.0  | ⏳ In Progress | Bottom nav, Restore cloud data, Azure sync |

---

## 🤝 Contributions

This repo is for **APK hosting and public issues and discussions**.

---

## 🛡️ License

MIT License © 2025 Omkara Varma

---

