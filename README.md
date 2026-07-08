# Pro Stylez Flow — Releases

Public installer feed for **Pro Stylez Flow**. The application's source code lives in a
separate, private repository; this repo holds **only release binaries** so the app's
built-in auto-updater can download them without any credentials.

## How it works

Pro Stylez Flow checks this repo's **latest release** shortly after launch and every few
hours. When a newer version is available it downloads the installer quietly in the
background and installs it **the next time you close the app** — never mid-session.

Each release contains:

- `ProStylezFlow-Setup-<version>.exe` — the Windows installer (per-user, no admin required).
- `ProStylezFlow-Setup-<version>.exe.sha256` — checksum the updater verifies before installing.

## Install manually

Download the latest `ProStylezFlow-Setup-<version>.exe` from the
[Releases](../../releases) page and run it. It upgrades any existing install in place and
keeps your settings, dictionary, history, and scratchpad.
