# BEAMppt

PowerPoint and Keynote show control for events: sets up Presenter View on the right screens, a stage timer, a phone remote, OSC and HTTP control, slide sync across several Macs and PCs, and Stream Deck support. By [BEAM Events](https://beamevents.com).

This repository only holds the **Mac and Windows installers and updates**.

## Download
Get the latest version from **[Releases](https://github.com/BEAMevents/BEAMppt/releases/latest)**.

**Mac** (macOS 14 or later, Apple silicon or Intel)
- **BEAMppt-x.y.z.dmg**: open it and drag BEAMppt into Applications. Use this one for a first install.
- **BEAMppt-x.y.z-mac.zip**: the same app, used by BEAMppt to update itself.

BEAMppt isn't notarized by Apple yet, so the first time you open it macOS may block it: go to **System Settings → Privacy & Security** and click **Open Anyway**. When BEAMppt first runs, allow **Accessibility**, **Local Network** and control of PowerPoint/Keynote when asked.

**Windows** (Windows 10 or 11, PowerPoint)
- **BEAMppt-Setup-x.y.z.exe** installs BEAMppt and **updates itself automatically**. Use this one.
- **BEAMppt-Portable-x.y.z.exe** runs without installing. It tells you when a newer version is out, but doesn't update itself.

The installers aren't code-signed yet, so Windows SmartScreen may warn on first launch: click **More info → Run anyway**. When Windows Firewall asks, allow BEAMppt on **Private and Public** networks so Macs, PCs and phones can reach it.

Macs and PCs work together: they share one slide-sync group, the same phone remote, HTTP API, OSC commands and Stream Deck layout.

## Updates
BEAMppt checks for updates in the background.
- **Mac:** the menu bar icon gets a green dot and the menu shows **Update x.y.z ready**. Click it, then **Install & Restart**.
- **Windows:** the tray icon gets a green dot; open **Settings** and click the update button, then **Install & restart**.

Updates never install while a slide show is running.
