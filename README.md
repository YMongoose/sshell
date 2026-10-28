# sshell

Native SSH, SFTP and local terminal client for Windows x64.

## Download

- [Portable sshell.exe](https://github.com/YMongoose/sshell/releases/latest/download/sshell.exe): download and run a single executable.
- [Windows installer](https://github.com/YMongoose/sshell/releases/latest/download/sshell-setup.exe): per-user installation, Start menu integration and an optional desktop shortcut. Administrator rights are not required.

Windows 10 version 1809 or newer is required for the local terminal. Uninstalling preserves hosts, preferences, credentials and private keys.

## Application lock

Enable an optional 6–12 digit PIN in **Settings → Application security**. Once enabled, every launch requires the PIN before showing the workspace. Automatic locking defaults to five minutes of inactivity and minimizing; these options can be changed. Lock manually with **Ctrl+Shift+L**. Active sessions and unsaved documents stay open while locked.

Only a salted Argon2id verifier is kept in the operating system credential store. This protects access through the app interface; it does not replace Windows account security or protect against administrators and malware. Configure protection separately on each device and remember the PIN: it cannot be recovered.

## Updates

Starting with v0.2.0, use **Settings → Application updates** to check for new versions. Automatic checks run at startup and every six hours and can be disabled. Downloading an update requires your approval. Installation happens after you close the client normally; active sessions and unsaved edits are not interrupted automatically. The next ordinary launch uses the new version.

Keep the executable in a writable folder. Hosts, preferences and encrypted credentials are stored separately on the device and are not included in release files.

## Repository contents

This repository distributes compiled releases only. Application source code is maintained separately and is not published here. GitHub's automatically generated source archives contain only the files in this distribution repository, not the application's source code.
