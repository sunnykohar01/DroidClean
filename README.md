🧹 DroidClean

Advanced Android Debloating & Package Management for Dioxamine

""Platform" (https://img.shields.io/badge/Platform-Android-green.svg)" (https://www.android.com/)
""Dioxamine" (https://img.shields.io/badge/Powered%20by-Dioxamine-blue.svg)" (https://rhythmcache.github.io/Dioxamine/)
""Inspired by" (https://img.shields.io/badge/Inspired%20by-UAD--ng-orange.svg)" (https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation)
""Version" (https://img.shields.io/badge/Version-1.1.0-purple.svg)" (#)
""Author" (https://img.shields.io/badge/Author-sunnykohar01-black.svg)" (https://github.com/sunnykohar01)

DroidClean is an advanced Android package management and debloating plugin for Dioxamine, inspired by the package database and safety classifications of Universal Android Debloater Next Generation (UAD-ng).

It allows users to inspect, manage, disable, uninstall and restore Android packages directly through Dioxamine's Android debugging environment.

---

✨ Features

📦 Package Management

- 🔍 Search installed packages
- 📋 Scan Android package list
- 📝 Package descriptions
- 🔗 Dependency information
- 🔄 "neededBy" information
- 🟢 Enable packages
- ⛔ Disable packages
- 🗑️ Uninstall packages for User 0
- ♻️ Restore packages
- 🧹 Clear package data
- 🛑 Force stop applications

---

🛡️ UAD-ng Inspired Safety System

DroidClean uses removal classifications inspired by UAD-ng:

Level| Meaning
🟢 Recommended| Generally intended for removal according to the database
🟡 Advanced| Requires more knowledge
🟠 Expert| Intended for experienced users
🔴 Unsafe| Potentially dangerous
⚪ Unlisted| No removal recommendation

🔐 Unsafe Mode

Unsafe packages are locked by default.

To access them:

Tools
  ↓
Unlock Unsafe
  ↓
Warning #1
  ↓
Recovery / Backup confirmation
  ↓
Warning #2
  ↓
Type YES
  ↓
Unsafe packages unlocked

Unsafe mode is session-only and automatically returns to locked state when DroidClean is restarted.

«⚠️ Unlocking an Unsafe package does not make it safe. It only removes DroidClean's UI protection.»

---

🔎 Powerful Package Search

Search using:

- Package name
- Description
- Labels

Example:

com.google.android.gms
youtube
facebook
systemui

You can also filter by:

Google
OEM
AOSP
Carrier
Misc

---

📱 Device Information

DroidClean displays:

- Manufacturer
- Device model
- Android version
- Android SDK
- Build information
- Installed package count

Example:

Xiaomi 14
Android 16
SDK 36
HyperOS Build ...

---

🧰 Device Tools

DroidClean includes additional device utilities:

- 🔄 Refresh package database
- 📱 Refresh device information
- 📋 Export selected packages
- 🔄 Reboot device
- 📝 Action log

---

♻️ Restore Packages

DroidClean uses Android's user-level package management instead of requiring root for normal User 0 operations.

Uninstall:

pm uninstall --user 0 PACKAGE_NAME

Restore:

cmd package install-existing --user 0 PACKAGE_NAME

This means many system packages can be removed from the current user without physically deleting their APK from the system partition.

---

🧠 Why UAD-ng?

DroidClean does not try to invent its own package safety database.

It uses the work of the Universal-Debloater-Alliance / UAD-ng project as the primary source of package classifications and metadata.

UAD-ng provides information such as:

- Package description
- Manufacturer/list
- Removal recommendation
- Dependencies
- Packages that depend on it
- Labels

🔗 UAD-ng

https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation

---

⚡ Installation

Requirements

- Android device
- Dioxamine
- Wireless debugging / ADB connection
- Android 6+ recommended
- Dioxamine plugin support

Install

1. Download the latest DroidClean ".zip"
2. Open Dioxamine
3. Open Plugins
4. Select Install Plugin
5. Select the DroidClean ZIP
6. Connect your Android device through ADB
7. Launch DroidClean

---

🔌 Dioxamine

DroidClean is designed specifically as a Dioxamine plugin.

Dioxamine provides the Android debugging environment and ADB bridge used by DroidClean.

🔗 https://rhythmcache.github.io/Dioxamine/

---

⚠️ Safety Warning

Android packages are highly dependent on:

- Device manufacturer
- ROM
- Android version
- Region
- Carrier
- Google services configuration
- Package dependencies

A package that is removable on one device may be essential on another.

Do not blindly uninstall packages.

Before debloating:

- Keep important data backed up
- Know how to reconnect through ADB
- Understand the package you're removing
- Avoid modifying critical system packages unless you know exactly what you're doing

DroidClean's safety classifications are guidance, not a guarantee.

---

🧪 Project Status

Current release:

DroidClean v1.1.0

Current focus

- Package management
- UAD-ng database integration
- Safety classifications
- Dioxamine integration
- User 0 operations

Planned improvements

- 📊 Package statistics
- 💾 Debloat profiles
- 📤 Import/export profiles
- 🔄 One-click restore profiles
- 👥 Multi-user support
- 📦 APK information
- 🔐 More granular safety controls
- 🎨 UI improvements
- 📱 OEM-specific recommendations
- 🧪 Better package-state detection

---

👨‍💻 Developer

sunnykohar01

GitHub:

https://github.com/sunnykohar01

---

🙏 Credits

Special thanks to the open-source Android debloating community.

Universal-Debloater-Alliance

DroidClean is inspired by and uses package metadata/classification concepts from UAD-ng.

https://github.com/Universal-Debloater-Alliance/universal-android-debloater-next-generation

Dioxamine

DroidClean is built for the Dioxamine plugin ecosystem.

https://github.com/rhythmcache/Dioxamine

---

📄 License

License information will be added with the project release.

---

⭐ Support the Project

If DroidClean is useful to you:

⭐ Star the repository
🐛 Report bugs
💡 Suggest features
🔧 Contribute improvements
📢 Share the project with other Android power users

---

<div align="center">🧹 DroidClean

Clean Android. Stay in Control.

Made by "sunnykohar01" (https://github.com/sunnykohar01)

</div>
