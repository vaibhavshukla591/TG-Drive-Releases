# TG Drive

Created by **Vaibhav Shukla**.

[Download the latest signed APK](https://github.com/vaibhavshukla591/TG-Drive-Releases/releases/latest)

## Installation

Install over your existing personal TG Drive. Android should offer Update. Do not uninstall or clear app data. Keep an external AES-key backup.

Install version 1.6.0 manually once to enable the updater. Later, open Settings > App updates > Check for updates. Automatic checks run when the app opens, at most once every six hours. Download starts only after your tap; Android asks for installation approval. There is no silent installation or instant background push.

## Publishing an update

Create a tested APK with a higher versionCode and the same private signer. Create a stable release here (for example v1.6.1), attach only that signed APK, and paste the generated release notes including the TGDRIVE_UPDATE_V1 metadata line. Publish as the latest release. Apps discover it on their next check.

The updater verifies package, version, SHA256 and the installed signing certificate. Android source, tests, credentials and signing keys remain private. This repository contains release documentation and compiled APK assets only. Third-party notices are bundled in the APK.

Checks contact GitHub, which receives normal network information such as IP and app-version user agent. No Telegram credentials, AES keys or personal files are sent.

[GitHub](https://github.com/vaibhavshukla591) | [LinkedIn](https://www.linkedin.com/in/vaibhavshukla591/)
