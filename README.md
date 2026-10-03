# PeakOS

A desktop app for people who work with Claude Code. It keeps your goals, your
running agent sessions, what they cost, and how you are holding up in one
place.

## Download

Get the latest installer from the
[Releases page](../../releases/latest):

- **`PeakOS_x.y.z_x64-setup.exe`**: the installer most people want.
- **`PeakOS_x.y.z_x64_en-US.msi`**: the same app as an MSI, for managed machines.

## Requirements

- Windows 10 or 11, 64-bit. macOS and Linux builds are not available yet.
- [Claude Code](https://claude.com/claude-code), installed and signed in, for
  everything that tracks your sessions. The app opens without it.

## Install

1. Run `PeakOS_x.y.z_x64-setup.exe`.
2. Windows may show **"Windows protected your PC"**. The installer is not
   code-signed yet, so Windows does not recognise the publisher. Click
   **More info**, then **Run anyway**.
3. Open PeakOS and press **Get started**. It signs you in through Claude
   Code's own login page, then adds the PeakOS plugin to your Claude Code so
   your sessions report to the app. You can connect or disconnect later from
   **Profile**.

## Your data

PeakOS stores your data in a local database on your computer. It has no
account of its own. Claude Code sign-in is handled by Claude Code itself, and
PeakOS does not read your Claude credentials.

## Updating

Download the newer installer from the Releases page and run it. It installs
over the existing version.

## Reporting a problem

Open an issue in this repository. Include your PeakOS version (shown on the
Releases page you downloaded from) and what you did before the problem
appeared.
